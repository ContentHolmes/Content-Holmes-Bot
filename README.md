# Content-Holmes-Bot
A chat-bot for accessing and managing the settings of Content Holmes. It can be used by parents to easily tweak CH's settings without a learning curve.

The chatbot uses Microsoft Bot Framework along with LUIS to enable recognition of natural language input.

## Setting up

1. Install latest version of nodejs and npm.

2. Install the required node modules in the root directory of the project.

This can be done by:
	
	$ npm install
 
3. Install the mircrosoft bot emulator. You require this to connect to the bot and run it.

# Project Structure

All dialogs in Content-Holmes-Bot have been neatly classified into libraries which reside at ./bot/dialogs. Dialogs in each library are mutually exclusive and perform a specific class of tasks. These are as follow:

Library | Description
--------|-------------
productivity.js | It houses all dialogs relevant to the productivity module of Content Holmes. This includes blocking, unblocking, sessioning etc.
report.js | It houses all dialogs relevant to fetching reports and details on the user's browsing activity
user.js | It contains all dialogs that either change or retrieve user's personal information
utilities.js | It consists of all dialogs that can help the users navigate the bot more easily.

## Contributing

**We love contributions!**

When contributing, follow the simple rules:

* Don't violate [DRY](http://programmer.97things.oreilly.com/wiki/index.php/Don%27t_Repeat_Yourself) principles.
* [Boy Scout Rule](http://programmer.97things.oreilly.com/wiki/index.php/The_Boy_Scout_Rule) needs to have been applied.
* Your code should look like all the other code – this project should look like it was written by one person, always.
* If you want to propose something – just create an issue and describe your question with as much description as you can.
* If you think you have some general improvement, consider creating a pull request with it.
* If you add new code, it should be covered by tests. No tests – no code.
* If you add a new feature, don't forget to update the documentation for it.
* If you find a bug (or at least you think it is a bug), create an issue with the library version and test case that we can run and see what are you talking about, or at least full steps by which we can reproduce it.

## License

All Content Holmes source code is made available under the terms of the GNU Affero Public License (GNU AGPLv3).
