---
id: nuke
description: Learn how to use the !nuke command in StreamElements chatbot to timeout, ban or delete messages containing a specified string. Moderate your chat effectively with this powerful command.
tags:
  - chatbot
  - commands
  - moderation
keywords:
  - nuke command
  - timeout
  - ban
  - delete messages
  - moderate chat
---

# !nuke

The `!nuke` command is used to perform a timeout, ban, or deletion on messages in the chat. This command will search the chat messages for a specified string and perform the specified action on the messages if the string is found. This command will error if the string is not found in the chat.

### Arguments

- `lookback in seconds`: This is the time window in the past in which to search for the messages.
- `timeout in seconds, 'ban' or 'delete'`: This is the action to perform on the messages. It can be a timeout for a specified number of seconds, a ban, or a deletion of the messages.
- `match string, for regex, wrap in slashes /abc/`: This is the string to match in the messages. If a regular expression is used, it should be wrapped in slashes.

#### Example Input

```
!nuke 60 60 /test/
```

#### Example Output

```
Nuking 2 chatters ☢ ️ ☢ ️ ☢ ️ This will take about 1 secs ☢ ️ ☢ ️ ☢ ️
```
