# Delete a player 3

If the user hits yes we want to send a message back to Elm to delete the player. If they hit cancel we don't send anything and nothing happens.

## Main

Add a new port to __src/Main.elm__ so we can get the inbound message:

```elm
port getDeleteConfirmation : Signal Int
```
