# Ideas for Implementation Details

## Approved

### Cache Messages (Chat)

#### idea
The Message send to a groups chat are saved in the chat engines database as well as cached in a file on every device in this same group. This removes the need to reload every message on every device whenever the chat is opened.

### Clear Messages clears local cache file (Chat)

#### idea
Every user has the ability to clear their group chats. This of course does not delete any message in the database, but remove the content of the local cache file.

### Start discussion using file and messages from chat (Chat/Storage)

#### idea
When a user uploads a file through the chat, other members might start up a discussion in the chat below it without initially intending to do so. Now it is possible to select the concerning file and the messages below (like in WhatsApp) and add them to a new discussion which belongs to that file.

### "Blank" Discussions

#### idea
There may be the case somebobdy wants to start a discussion without linking it to a file, but still have it stored and saved as a single entity. For that case it would make sense to allow the creation of a discussion with a blank file or standin so to say.

## Unapproved

### Closed discussions disappear from the chat view

#### idea
Whenever a discussion is closed, it is removed from the chat to not clutter it. The discussion can be viewed from the storage and readded to the chat letter.