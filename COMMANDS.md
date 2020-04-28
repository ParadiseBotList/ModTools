## Page Navigation
- [About ModTools](./README.md)
- [ModTools Information](PERFORMANCE.md)
- [ModTools Invite](https://discordapp.com/api/oauth2/authorize?client_id=634306491310145540&permissions=8&scope=bot)

## Command Categories
- [Everyone](#everyone)
- [Moderation](#mod)
- [Settings](#settings)

<a name="everyone"></a>
#### ***General:***

``` !mt help```

> Shows this message

<a name="mod"></a>
#### ***Moderation:***

```!mt enable```

> Enables automod in this channel

```!mt disable```

> Disables automod in this channel

<a name="settings"></a>
#### ***Settings:***
```!mt settings modrole @role```

> Sets the modrole. Everyone with this role can control the bot.

```!mt settings modrole```

> Shows the current modrole

```!mt settings modrole exempt [true | false]```

> Makes the modrole (not) exempt from punishments, default is false

```!mt settings modrole exempt```

> Shows the current settings for modrole exempt

```!mt settings threshold 1-99```

> This defines how confident the bot has to be that a message is toxic in order to classify it as such. Default is 85%

```!mt settings threshold```

> Shows the current value of threshold

```!mt settings tags [identity_attack | insult | obscene | severe_toxicity | threat | toxicity] [true | false]```

> Sets one of the tags to either true or false. Every message gets classified with those tags. If you set one or multiple of these tags to true messages that don't get classified with those tags will be ignored. If all tags are off the bot will react to messages that contain any of the tags

```!mt settings tags```

> Shows the current settings for the tags

```!mt settings log #logchannel```

> Sets a channel to send logs of actions performed by the bot to

```!mt settings log off```

> Disables logging

```!mt settings log```

> Shows the current logging channel

```!mt settings punishment [delete | temp_mute | kick | softban | ban] [0-1000 | off]```

> You can specify what punishment a user should recieve after x amount of infractions. e.g. !am settings temp_mute 5 will cause the bot to mute the user after every 5 toxic messages. Setting a punishment to 0 will cause it to execute on every toxic message

```!mt settings punishment```

> Shows the current settings for punishments

```!mt settings muterole @role```

> Sets the role that the bot will give to temporarily mute users. You have to set this role up yourself.

```!mt settings muterole```

> Shows the current muterole

```!mt settings muteduration 1-50000```

> Sets the mute duration in seconds

```!mt info [@user | userid]```

> Shows how often a user recieved a punishment

```!mt info reset [@user | userid]```

> Resets all info on that user
