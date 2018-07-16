# GASH - Groupme As a SHell

## Objective
The purpose of gash is to allow a user to execute simple commands on their remote computer. With some ISPs, the customer is unable or not allowed to run server programs, such as an SSH server. Gash allows such a user to access their computer remotely.

## How Does it Work?
To use gash, a user must have a Group Me API key, a Group Me bot, and that bot's bot ID and group ID. Simply add your information to the top of the `gash` file. Using this information, gash periodically checks for new messages in that group. If a message arrives from someone other than the bot, the message text is executed as a shell command, and the resulting output is posted by the bot to the group.

Remember, remote code execution can't be a vulnerability if it's a feature. Yes, this whole program, while functional, is a joke.
