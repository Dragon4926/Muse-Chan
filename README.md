<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <!-- <title>Discord Bot with OpenAI Integration</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    code {
      background-color: #f4f4f4;
      padding: 2px 5px;
      border-radius: 3px;
    }
  </style>
  --!>
</head>
<body>

  <h1>Discord Bot with OpenAI Integration</h1>

  <h2>Introduction</h2>
  <p>This Discord bot is designed to enhance your server experience by providing automated responses based on a conversation history using OpenAI's GPT-3.5-turbo model. Additionally, the bot features a dynamic status that changes periodically.</p>

  <h2>Installation</h2>
  <ol>
    <li>Clone the repository:</li>
    <code>git clone https://github.com/Dragon4926/Muse-Chan.git</code>
    <li>unzip the zip file</li>
    <code>cd Muse-Chan</code>
    <li>Install dependencies:</li>
    <code>npm install</code>
    <li>Create a <code>.env</code> file in the root directory and add the following variables:</li>
    <code>TOKEN=your_bot_token</code>
    <code>API_KEY=your_openai_api_key</code>
    <code>CHANNEL_ID=your_discord_channel_id</code>
  </ol>

  <p>Replace <code>your_bot_token</code>, <code>your_openai_api_key</code>, and <code>your_discord_channel_id</code> with your Discord bot token, OpenAI API key, and the channel ID where you want the bot to respond, respectively.</p>

  <h2>Usage</h2>
  <ol>
    <li>Run the bot:</li>
    <code>node index.js</code>
    <li>Invite the bot to your Discord server using the OAuth2 link generated in your <a href="https://discord.com/developers/applications">Discord Developer Portal</a>.</li>
    <li>Ensure the bot has the necessary permissions and is in the specified channel (<code>CHANNEL_ID</code>) to respond.</li>
  </ol>

  <h2>Features</h2>
  <h3>Dynamic Status</h3>
  <p>The bot showcases a dynamic status that changes every 3 minutes, cycling through activities like watching YouTube, listening to discord.js, and playing VALORANT.</p>

  <h3>OpenAI Integration</h3>
  <p>The bot utilizes OpenAI's GPT-3.5-turbo model to generate responses based on a conversation history. It simulates a tsundere waifu personality and responds accordingly.</p>

  <h3>Message Trigger</h3>
  <p>The bot responds to messages in the designated channel (<code>CHANNEL_ID</code>) and ignores messages starting with '!'. Adjust this condition as needed.</p>

  <h2>Configuration</h2>
  <p>Adjust the <code>status</code> array for customizing the dynamic status activities. Modify the conversation log or OpenAI parameters based on your preferences.</p>

  <h2>Credits</h2>
  <ul>
    <li><a href="https://discord.js.org/">Discord.js</a></li>
    <li><a href="https://platform.openai.com/">OpenAI</a></li>
  </ul>

  <p>Feel free to contribute and improve the functionality of this Discord bot. If you encounter any issues or have suggestions, please open an <a href="https://github.com/your-username/your-repo/issues">issue</a>.</p>

</body>
</html>
