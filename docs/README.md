# Discord.JS Colors
List of the colors used in [Discord.JS](https://discord.js.org)'s Type Definition, [ColorResolvable](https://discord.js.org/#/docs/main/stable/typedef/ColorResolvable).

Here's how to do this:

Install the package.
```
npm install kowasaur/discordjs-colors
```

Then do something like this.
```js
const Discord = require("discord.js");
const client = new Discord.Client();
const colors = require("discordjs-colors");

client.on("message", (message) => {
    let embed = new Discord.RichEmbed()
    .setTitle("Red color")
    .setColor(colors.red);

    message.channel.send(embed);
})
```

You can find the color list [here](COLORS.md).
