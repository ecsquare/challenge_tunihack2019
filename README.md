# challenge_tunihack2019
Notifiny
Realized by DeepCode Team
Description:
Our solution is to create an add-on in the browser to analyze the user's history and generate
from them a conclusion about the percentage of orientation to a certain topic. This
information will be used for giving the user chocked conclusion about his last behavior,
without making any manipulation and will be more and more developing certain reflection on
these regular maybe unexpected judges the AI provided him.
The main idea is to give people the benefit of the doubt and increasingly build critical
thinking among them.
Technologies:
RPA: TagUI is a tool(library) used to automate web interactions. In our case, we use it to
gather user’s activities from social media ( Linkedin) and browser history.
IA (NLP & ML): To analyze user’s activities on social media( Linkedin) and browser history
by predicting their interests. And we can use this technology further based on their behavioral
changements we can predict its future interests.
Javascript: to develop the add-on.
Architecture:
Background.js: The background script is the extension's event handler; it contains listeners
for browser events that are important to the extension. It lies dormant until an event is fired
then performs the instructed logic. An effective background script is only loaded when it is
needed and unloaded when it goes idle.
Popup.js: contain ordinary HTML pages with JavaScript logic
Data gathering : gather user’s activities
Prediction: predict user’s interests
