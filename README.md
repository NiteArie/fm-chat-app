# fm-chat-app (Chat App)

## Design Preview

Adobe XD Design: [https://xd.adobe.com/view/be6f9ce2-8760-4991-b7df-c3ade3c11d0a-eb3c/](https://xd.adobe.com/view/be6f9ce2-8760-4991-b7df-c3ade3c11d0a-eb3c/)

## Requirements

* The website looks similar to the design (Desktop and Mobile) and is available for users through a link.
* When a new user visits the Chat App, present welcome, Wizard UI to guide him through creating an account including avatar and nickname selection.
When an existing user visits the Chat App, read the account data e.g. from localStorage (compare it with server) and present the Chat App immediately instead of the welcome, Wizard UI.
* When a user opens the Chat App, Group Chat should be presented (user shall be added to it automatically), and the people counter will be increased by one.
* When a user lefts the Chat App, the people counter will be decreased by one.
Group Chat should show the number of users being online, messages from all the users (note: optionally can skip historical messages for new users or keep all the history as you will), information about new users joining, existing users leaving and an online dot indicator (green - online, gray - offline).
* Users should be able to add messages through the input with the ability to select emoji using an emoji picker. Messages should be sent by clicking on a button or/and e.g. by using Enter key.
* "My" messages should show on the right, other user's messages should show on the left.

## Additional Requirements

* Show "is typing" UI when a user is typing.
* Show "unread" messages indicator.
* Add ability to start a direct chat with a user.
* Add ability to block a user to prevent seeing his/her messages on Group Chat and prevent him/her from starting a direct chat with you or/and end any started direct chat.
* Add sound notification when a new message is received and add mute functionality to mute either group or private (DM) chat.
* Add API tests to your code, using e.g. Mocha & Chai.
* Add e2e tests to your code, using e.g. cypress.