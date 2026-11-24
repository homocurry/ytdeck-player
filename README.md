# ytdeck-player

Player page for the SynapseRack "YouTube Deck" app.

It hosts the YouTube IFrame player on an https origin (YouTube refuses embeds from `data:` pages with error 153).
The page holds no user data: the SynapseRack app writes each deck's state to `synapse.storage`, this page reads it and drives the player.
Sync model inspired by [YouTube-VJ](https://github.com/KazuProg/youtube-vj) by KazuProg.

Use: `https://homocurry.github.io/ytdeck-player/player.html?deck=A`
