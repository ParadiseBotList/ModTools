## Page Navigation
- [About ModTools](./README.md)
- [ModTools Commands](./COMMANDS.md)
- [ModTools Invite](https://discordapp.com/api/oauth2/authorize?client_id=634306491310145540&permissions=8&scope=bot)


Average processing time of a message. Calculated from 10 samples.

|    Performance    |  Ryzen 5 2600  | Raspberry Pi 3b+ |
| :---------------: | :------------: | :--------------: |
|   10 characters   |    40 ms       |      398 ms      |
|  100 characters   |    203 ms      |      1497 ms     |
|  1000 characters  |    1810 ms     |      12947 ms    |

*This table isn't completely correct anymore. The performance has increased a bit.*

As you can see it takes quite long especially for longer messages. If you host the bot make sure that it's not on too many servers or otherwise the bot could start lagging behind.

Note: If the bot starts lagging behind it wont skip messages. It will still check every message one after the other.
