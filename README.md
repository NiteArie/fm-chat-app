# fm-chat-app (Chat App)

## Requirements

* The website looks similar to the design (Desktop and Mobile) and is available for users through a link.
* When a new user visits the Chat App, present welcome, Wizard UI to guide him through creating an account including avatar and nickname selection.
When an existing user visits the Chat App, read the account data e.g. from localStorage (compare it with server) and present the Chat App immediately instead of the welcome, Wizard UI.
* When a user opens the Chat App, Group Chat should be presented (user shall be added to it automatically), and the people counter will be increased by one.
* When a user lefts the Chat App, the people counter will be decreased by one.
Group Chat should show the number of users being online, messages from all the users (note: optionally can skip historical messages for new users or keep all the history as you will), information about new users joining, existing users leaving and an online dot indicator (green - online, gray - offline).
* Users should be able to add messages through the input with the ability to select emoji using an emoji picker. Messages should be sent by clicking on a button or/and e.g. by using Enter key.
* "My" messages should show on the right, other user's messages should show on the left.