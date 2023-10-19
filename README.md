# AlexMusic - Discord Music Bot

Alex is a versatile and user-friendly Discord music bot that allows you to play songs from various sources and customize your audio experience with built-in filters.

## Screenshots

## Screenshots

![Screenshot 1](https://cdn.discordapp.com/attachments/1131235535273328650/1140952237997297704/image.png)
![Screenshot 2](https://cdn.discordapp.com/attachments/1131235535273328650/1140952238219612211/image.png)
![Screenshot 3]((https://media.discordapp.net/attachments/1164400253810774109/1164401534902227034/Screenshot_97.png?ex=6543146f&is=65309f6f&hm=9b7fee609f5535614ade735fc769a23cd238708054ce4925a91331912608133c&=))


## Features

- Play songs from YouTube, Spotify, and SoundCloud.
- Customize audio with built-in filters.
- Easy-to-use commands for control and management.
- Support for playlist management and queuing.

## Getting Started

1. **Fork This Code**
    [![Muzio DIscord Bot](https://github.com/JagguFT/Alex-Music))]

2. **Configuration**
   - edit `config.json` file in the root directory with your bot token and other settings:

   ```json
   {
    "repl_user": false,
    "token" : "",
    "prefix" : "$",
    "color" : "#c50632",
    "owners" : ["900708551805268019"],
    "mongourl" : "",

    "errors" : "",
    "spotifyId" : "",
    "mongourl2" : "",
    "spotifySecret" : "",
    "topggapi" : "",
    "server" : "https://discord.gg/BEFPkccG2T",
    "invite" : "(https://discord.com/api/oauth2/authorize?client_id=1163115276620013708&permissions=552174881824&scope=bot)",
    "nodes" : [{
       "name" : "LavaLink",
        "host" : "192.168.1.250",
        "port" : 25568,
        "password" : "gearjindabad",
        "secure" : false
    }]
}
   

3. **Installation**
   - Clone this repository:

   ```sh
   git clone https://github.com/ScienceGear/muzio.git
   ```

   - Install the required packages:

   ```sh
   npm install
   ```

4. **Usage**
   - Start the bot:

   ```sh
   node src/index.js
   ```

5. **Commands**
   - `!play <song_name>`: Play a song from YouTube.
   - `!skip`: Skip the current song.
   - `!pause` and `!resume`: Pause and resume playback.
   - `!voice <value>`, `!sound <value>`, `!bass <value>`: Apply audio filters.
   - `!playlist <playlist_link>`: Play songs from supported platforms.
   - `!queue <song_name>`: Add a song to the queue.

## Support

For assistance or questions, join our [support server]((https://discord.gg/BEFPkccG2T)).

## Contributors

ALex Music Is Made By and maintained @jagguft dont claim this as yours 

## Disclaimer

Please use Muzio in compliance with Discord's [Terms of Service](https://discord.com/terms) and [Developer Terms of Service](https://discord.com/developers/docs/legal).
