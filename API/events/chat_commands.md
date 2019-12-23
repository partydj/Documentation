# Chat Command

Event emitted when a user uses a "/" command.

This event is a Frontend only event, as it is handled within the browser itself.

Event name: API.CHAT_COMMAND

### Example Listener

```js

API.on(API.CHAT_COMMAND, function(data){
    console.log(data);
});
```

### Packet Example

```js
"/test"
```

Returns string containing the entered command

**Please Note:** the default [commands](/api/commands.md) provided by Party DJ, will not emit this event!