# One page Static Website with Amazon Lex Chatbot
# QuickStart
- 1. Download the folder and open index.html
- 2. If you dont have any identityPoolId for Amazon Lex Chatbot/ or you dont have an existing chatbot, please create one first from here: https://console.aws.amazon.com/lex/home?region=us-east-1
- 3. After that, set up amazon cognito and create identity pool. If you already have one, jump to number 6.
- 4. After identity pool is created, You need to modify the IAM roles to allow access to Amazon Lex
- 5. From the IAM console, you find the roles and change each of them to attach the AmazonLexRunBotsOnly and AmazonPollyReadOnlyAccess policies
- 6. take the identity pool you got, change xxx of 'us-east-1:xxx' in chatbot.js with your identityPoolId.
- 7. After that you just need to start the application either with live server or from your directory.
- 8. You can immediately talk to the bot. 
# Room for improvement 
- AWS Lex has the function call lambda that can be used to take information from API and can be connected through javascript
- Add more intent to make the bot smarter.
-------------------------------------------------------------------------------------------------------------------------------------
# Features 
# Chatbot
- Chatbot has a small range of tree which is customized for basic use.
- The use can start saying something to the bot with Hi
- There are plenty of utterances that the user can try to talk with the bot. 
# Static Website 
- One page website with a scrolling system. Once the head section of the website is clicked, It will directly jump to the selected section.
- Website consists of About us, Subscribe, Main, News sections
# Below is the list of expected utterances from the user.
- Hi, Hello, etc. (Greetings)
- I want to go to your office, Can I talk to your support?, Where is the location of your office?, etc. (Contacting our office)
- What is Dracon?, What do you do?, What you guys provide?, What you guys doing?, etc. (Information about our company)
- What time do you guys open?, Do you guys open on sunday?, When is the right time to call you guys?, etc. (Business hours)
- I want to know the progress of my application, Can I know the progress of my application?, etc. (Client's progress)
# Documentation 
- License can be found in license.md
