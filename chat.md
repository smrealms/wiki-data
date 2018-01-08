<!-- TITLE: Chat Servers -->
<!-- SUBTITLE: A quick summary of SMR chat services -->


Chat is the backbone on which team play as well as socializing is done in SMR. It is recommended that whenever you are going to play SMR you check in with your alliance chat room first. Here your fellow teammates can alert you to dangers, advise you of tasks that you might be able to help with, or simply ask that you stay out of the game as to not spook an enemy trader they are trying to hunt.

# Discord
## Ways of Connecting to Discord
* Direct link: discord.me/smrealms
* **Join Chat** link on the in-game left panel

## Autopilot for alliance channels
**Autopilot** is a bot that connects the SMR game server with Discord. When invited to a private Discord server for your alliance, Autopilot can be used to enhance your coordination and efficiency. To invite Autopilot to your server, simply type `.invite` in the [public SMR discord channel](https://discord.me/smrealms), and then follow the instructions.

Once Autopilot has connected to your server, type `.help` for a list of available commands.

## Alliance Discord widget
The [widget](https://blog.discordapp.com/add-the-discord-widget-to-your-site-d45ffcd718c6) for your alliance Discord server can be added to your Alliance Message of the Day page. Having the widget accessible on a prominent game page makes it much easier for your teammates to join your server.

To set this up, you will need to do the following:
1. In your Discord App, go to `Server Settings` and then on that screen select the `Widget` link.
2. Toggle `Enable Server Widget` to the On position.
3. OPTIONAL: If you'd like people to be able to join your server through the widget, set an `Instant Invite Channel`; otherwise, the widget will be for display only. 
4. Click the `Copy` button to the right of the `Server ID` field.
5. Log into SMR and go to `Alliance`-> `Options`->`Change Alliance Stats` and then paste the ID you copied into the `Server ID` input box.
6. Click the `Change` button for it to take effect, and then verify that it displays correctly on your Alliance Message of the Day page.

**Warning:** If you set the `Instant Invite Channel`, then anyone who can see your widget will be able to join your server. If you are worried about security, but still want to use this feature, then you may want to make a separate channel with limited permissions for players to initially join.

# IRC
## Ways of Connecting to IRC
* Direct link: [mibbit web client](https://client02.chat.mibbit.com/?server=irc.theairlock.net&channel=%23smr) 
* **Join Chat** link on the in-game left panel

If you use the in-game chat link, you can just click connect and it will attach an SMR- prefix to your current game name. This will take you to the game lobby `#smr` and an alliance chat room if you are currently in an alliance and the leader has set the room under alliance options.

There are also 3rd party applications to connect to IRC servers. mIRC, xchat, icechat, pidgin, and colloquy for apple users are the most widely used. If you are familiar with any of these than you can simply connect to irc.theairlock.net using them otherwise a good option is to come to chat using the in-game applet and ask someone for help in setting it up.

## Basic IRC Commands

There are a few basic commands you should know if you have never used IRC before. 
* `/join` or `/j` is used to join a new room, room names are generally prefixed by a #. Example: `/join #smr` will take you to a friendly public room where several SMR players congregate.
* `/nick` is used to change your nickname in chat. Example: `/nick NewNick` will change your name to NewNick.

More advanced commands include registering your nickname and identifying yourself afterward:
* `/nickserv register password email` (where password is the password you would like to use and email is your own valid email address, you will receive an email with instructions on validating it)
* `/nickserv identify password` (where password is the password you set when registered) is used thereafter when you connect or switch to your registered nickname.

Be advised that we are part of a very large IRC network and your preferred name may be registered already.
Other commands are also available via nickserv and chanserv you can get an idea of these by typing `/nickserv help` and `/chanserv help`.

## Caretaker for alliance channels
**Caretaker** is an IRC bot that connects the SMR game server. It is useful for alliances that want to continue using IRC instead of Discord. When invited to your alliance IRC channel, Caretaker can be used to enhance your coordination and efficiency.

To invite Caretaker to your server, join your alliance IRC channel as an op and type `/autoconnect on`. Then go to the Alliance Stats page in-game and enter your channel name in the `IRC Channel` field.