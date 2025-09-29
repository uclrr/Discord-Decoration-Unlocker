Discord Avatar Decoration Bot

An advanced Discord bot that lets users enhance their profile pictures with stylish animated effects. It offers a wide range of decorations, including official Discord avatar styles and country flags.

✨ Key Features

Profile Effects: Add animated decorations to your Discord avatar.

Large Collection: Includes Discord’s official decorations and international flag styles.

Channel Control: Limit the bot’s usage to chosen channels.

Simple Interface: Organized menus with clean navigation for easy use.

Randomizer: Instantly apply a random effect with one command.

Slash Command Ready: Fully supports Discord’s modern slash commands.

Classic Commands: Legacy prefix commands (like !effect) are also available.

Anti-Spam Cooldowns: Prevents overuse with built-in cooldown management.

Stable & Reliable: Strong error handling for smooth operation.

High Quality: Produces crisp, high-resolution animated GIFs of avatars.

📋 Requirements

Node.js 16.9.0 or higher

A Discord Bot Token

Discord.js v14

🚀 Installation

Clone the repository:

git clone https://github.com/claire/discord-avatar-decoration-bot.git
cd discord-avatar-decoration-bot


Install dependencies:

npm install


Configure the bot in config.js:

module.exports = {
  token: "TOKEN", // Your bot token
  guildId: "ID", // Your server ID (for guild commands)
  
  // COMMAND SETTINGS
  defaultPrefix: "!", // Prefix for commands
  cooldown: 5, // Command cooldown in seconds
  
  allowedChannelIds: ["ID"], // Channel IDs
  
  avatarSize: 512, // Avatar size
  gifQuality: 10, // GIF quality (1-30)
  frameDelay: 100, // Delay between frames in ms
};


Start the bot:

npm start

💻 Usage
Commands

/effect - Opens the avatar decoration menu (slash command)

/help - Shows bot help and information

/ping - Checks bot response time and connection status

!effect - Text command to open the avatar decoration menu

How to Use

Type /effect or !effect in any allowed channel

Choose a decoration category from the dropdown menu

Select your desired effect

The bot replies with your customized avatar as a GIF

Channel Restrictions

Restrict usage: Add specific channel IDs to allowedChannelIds.

Disable everywhere: Set allowedChannelIds to [].

Allow all channels: Set allowedChannelIds to null.

🛠️ Development

Run with auto-restart:

npm run dev


Check for linting issues:

npm run lint

🔧 Advanced Configuration

Customize navigation buttons with custom emojis.

Adjust avatar size and GIF quality for better visuals.

Manage command cooldowns to prevent spam.

⚠️ Troubleshooting

Make sure the bot has permissions (Send Messages, Embed Links, Attach Files).

Verify your bot token is valid.

Check that required intents are enabled in the Discord Developer Portal.

🙏 Credits

Created by CLAIRE

Built with Discord.js for functionality

Uses Canvas and gif-encoder-2 for image processing

📄 License

MIT License — Copyright (c) 2025 CLAIRE
