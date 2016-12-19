===================================
 Welcome to FredBoat documentation
===================================

Welcome to the FredBoat docs. FredBoat is an open-source general-purpose bot developed in Java. The bot is based off of `JDA <https://github.com/DV8FromTheWorld/JDA>`_ and was created by `@Frederikam <https://frederikam.com/>`_. You'll be able to get a link back to this website simply by invoking `;;help`.

Additionally, I am also developing FredBoat♪♪ **which is in beta** and is a music bot. This is a seperate bot and must therefore be invited using `this link <https://discordapp.com/oauth2/authorize?&client_id=184405253028970496&scope=bot>`_. See the commands below on how to use it.

--------------------
 Setting up the bot
--------------------
Getting FredBoat running on your server is simple. You can invite the bot by authenticating it with your account using `this link <https://discordapp.com/oauth2/authorize?&client_id=168686772216135681&scope=bot>`_. Bear in mind that you must have the "Manage Server" permission to be able to do this. 

--------------------------
 Setting up the music bot
--------------------------
The music bot has it's own 
`invite link <https://discordapp.com/oauth2/authorize?&client_id=184405253028970496&scope=bot>`_.


----------
 Commands
----------
+------------------------------+-----------------------------------------------------------------------+
| Command                      | Description                                                           |
+==============================+=======================================================================+
| ;;help                       | Sends a PM with instructions and a link to this site                  |
+------------------------------+-----------------------------------------------------------------------+
| ;;say \<text\>               | Make the bot echo something                                           |
+------------------------------+-----------------------------------------------------------------------+
| ;;avatar                     | Displays the avatar of a user                                         |
+------------------------------+-----------------------------------------------------------------------+
| ;;brainfuck \<code\> [input] | Executes Brainfuck code                                               |
+------------------------------+-----------------------------------------------------------------------+
| ;;lua \<code\>               | Executes Lua code                                                     |
+------------------------------+-----------------------------------------------------------------------+
| ;;riot \<text\>              | Text command                                                          |
+------------------------------+-----------------------------------------------------------------------+
| ;;lenny                      | Returns a lenny face                                                  |
+------------------------------+-----------------------------------------------------------------------+
| ;;leet \<text\>              | m@k3$ y0u 50Und l1k3 a 5cr1p7 k1dd13                                  |
+------------------------------+-----------------------------------------------------------------------+
| ;;mal \<search term\>        | Searched MyAnimeList for animes and users                             |
+------------------------------+-----------------------------------------------------------------------+
| ;;dump \<1-2000\>            | Dumps up to 2000 messages to `Hastebin <http://hastebin.com/>`_       |
+------------------------------+-----------------------------------------------------------------------+
| ;;facedesk                   | Uploads an image                                                      |
+------------------------------+-----------------------------------------------------------------------+
| ;;roll                       | Uploads an image                                                      |
+------------------------------+-----------------------------------------------------------------------+

----------------
 Music commands
----------------
(`Requires the music bot <https://discordapp.com/oauth2/authorize?&client_id=184405253028970496&scope=bot>`_).

+------------------------------+-----------------------------------------------------------------------+
| Command                      | Description                                                           |
+==============================+=======================================================================+
| ;;play <url>                 | Plays a song from URL or starts searching for one                     |
+------------------------------+-----------------------------------------------------------------------+
| ;;list                       | Displays the current queue                                            |
+------------------------------+-----------------------------------------------------------------------+
| ;;nowplaying                 | Displays the current track                                            |
+------------------------------+-----------------------------------------------------------------------+
| ;;skip                       | Skips the current track                                               |
+------------------------------+-----------------------------------------------------------------------+
| ;;stop                       | Clears the entire queue                                               |
+------------------------------+-----------------------------------------------------------------------+
| ;;pause                      | Pauses the player                                                     |
+------------------------------+-----------------------------------------------------------------------+
| ;;unpause                    | Unpauses the player                                                   |
+------------------------------+-----------------------------------------------------------------------+
| ;;join                       | Summons the bot to your voice channel                                 |
+------------------------------+-----------------------------------------------------------------------+
| ;;leave                      | Gets the bot to leave the voice channel                               |
+------------------------------+-----------------------------------------------------------------------+
| ;;repeat                     | Toggles repeat mode                                                   |
+------------------------------+-----------------------------------------------------------------------+
| ;;shuffle                    | Toggles shuffle mode                                                  |
+------------------------------+-----------------------------------------------------------------------+
| ;;volume <0-150>             | Sets the volume                                                       |
+------------------------------+-----------------------------------------------------------------------+

----------------
 Music commands
----------------
The music bot supports media from many sites and even supports playlists from sites like YouTube and Soundcloud. The bot will not be able to play songs blocked in France (usually from copyright infringements on YouTube).

------------------------------
 Adding music to the playlist
------------------------------
Adding music to the playlist is pretty simple. To start playing a song, simply use the ;;play command. Here are two examples:

```
;;play https://www.youtube.com/watch?v=dQw4w9WgXcQ
;;play rick roll

```

You can either explicitly state the URL, or you can get the bot to search YouTube and give you some choices. Here's an example response:

```
Please select a video with the ';;select n' command:
1: Rick Astley - Never Gonna Give You Up (03:33)
2: YOUTUBERS REACT TO RICKROLL (Ep. #5) (09:20)
3: I Rick Roll My Entire Chemistry Class! (05:55)
4: The New Rick Roll! (04:26)
5: Melania Trump's RNC RICKROLL (00:19)
```

You can then choose your song with the `;;select <number>` command.

**Supported sites:**
* YouTube
* SoundCloud (single tracks only)
(TODO: Add remaining)

Let me know if you want other sites supported by suggesting in the `suggestion channel <https://discord.gg/Rdsp666>`_ .

-------------------------------
  Frequently Asked Questions
-------------------------------

Question: How do I play music with the bot?

Answer: Please read this fine manual. Specifically the part with the music commands.


Question: How do I add an entire playlist to the queue?

Answer: Simply link a playlist with the following syntax:

```;;play <url-to-playlist>```

Question: How do I restrict music commands to a specific channel or role?
The bot will only listen to music commands invoked in channels it can actually **write** to. Simply override it such that the music bot can only talk in the channels you want the bot to be usable from.

If you want to restrict the bot to a specific role, you can always just restrict the bot to a channel only accessible by a specific set of roles.

### How do I self host the bot?
It's difficult. I do not advise it.

### Why is the music bot slow to respond to commands?
Lots of people are using the music bot 24/7 on a relatively cheap server. I do have a [Patreon campaign](https://www.patreon.com/fredboat) to allow me to receive funding for additional hardware for the music bot and improve the bot response time. The music quality shuld be fine for the most part though. 

### The music bot is telling me it doesn't have permission to connect/play music. How do I give it permission?
You are trying to play music in a voice channel, but your __Discord server permissions__ prevents it from connecting or speaking. You would need to change the permissions of the channel to allow the bot to connect and speak, as you would do with a user. For official help on this topic, see [Discord's support center](https://support.discordapp.com/hc/en-us/articles/206029707).

## Join FredBoat Hangout!
We invite everyone to join FredBoat hangout, which is a place to discuss suggestions and request for support. I'm very willing to take suggestions for the bot so don't hesitate to say what you have in mind! [Click here to join!](https://discord.gg/0yXhQ9c36F4zsJMG)

## Credits
FredBoat is developed by Fre_d (aka Frederikam).

Thanks to JDK#0216 for designing the [FredBoat](http://i.imgur.com/1WOFPLy.png) logo!

## Legal
We are required to have you agree to our [Privacy Policy](http://hs.frederikam.com/zuyom.txt). You agree to this by using the bot.

Steam data is provided "as is" without any liability or warranty.
