This is forked project of Xieve's Musicord which it is written in Lua. I changed the code to adapt the current version of Discordia. This won't be easy ofc, especially to those who don't use Windows Server as VPS and Linux users who don't know Linux VPS very well.

Below is the original of this Readme with edits.

# musicord
A simple music-bot to stream from YouTube written in Lua with the [Discordia](https://github.com/SinisterRectus/Discordia) and the [youtube-dl](https://rg3.github.io/youtube-dl/) library

## Installation
First, follow the instructions [here](https://github.com/SinisterRectus/Discordia#installation) to install Discordia and [here](https://github.com/SinisterRectus/Discordia/wiki/Voice#acquiring-audio-libraries) to aquire the audio libraries Discordia-Voice needs, [here](https://rg3.github.io/youtube-dl/) you can download youtube-dl for your platform, run ```lit install creationix/coro-split``` in your bash/commandline and finally download main.lua in the folder where you installed everything else. ~To start the bot, just execute ```luvit main.lua TOKEN```, where TOKEN is your bot's token that you get after creating a discord application online.~
"Just insert your token at ```client:run ('Bot TOKEN')``` where you'll replace TOKEN with your real token." - Mobile

## Available commands:
- ``audio.play URL``      for playing single videos
- ``audio.playlist URL``  for playing YouTube-playlists
- ``audio.pause``         to pause the current stream
- ``audio.resume``        to resume the paused stream
- ``audio.skip``          to skip the playing video and go on with the next item on the YouTube playlist

## To-Do for Xieve:
A queue for audio.play (Hopefully very soon, it's been almost 2 years. ;-;)
