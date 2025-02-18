# twentyAI 🤖

https://x.com/twentyAI_BNB

https://twentyai.me

## ✨ Features

-   🛠️ Full-featured Discord, Twitter and Telegram connectors
-   🔗 Support for every model (Llama, Grok, OpenAI, Anthropic, etc.)
-   👥 Multi-agent and room support
-   📚 Easily ingest and interact with your documents
-   💾 Retrievable memory and document store
-   🚀 Highly extensible - create your own actions and clients
-   ☁️ Supports many models (local Llama, OpenAI, Anthropic, Groq, etc.)
-   📦 Just works!

## 🎯 Use Cases

-   🤖 Chatbots
-   🕵️ Autonomous Agents
-   📈 Business Process Handling
-   🎮 Video Game NPCs
-   🧠 Trading


## 🚀 Quick Start

### Prerequisites

-   [Python 2.7+](https://www.python.org/downloads/)
-   [Node.js 22+](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
-   [pnpm](https://pnpm.io/installation)

> **Note for Windows Users:** WSL is required

### Edit the .env file

Copy .env.example to .env and fill in the appropriate values

```
cp .env.example .env
```

### Edit the character file

1. Open `src/core/defaultCharacter.ts` to modify the default character

2. To load custom characters:
    - Use `pnpm start --characters="path/to/your/character.json"`
    - Multiple character files can be loaded simultaneously

### Start 21AI

After setting up the .env file and character file, you can start the bot with the following command:

```bash
pnpm i
pnpm build
pnpm start

# The project iterates fast, sometimes you need to clean the project if you are coming back to the project
pnpm clean
```

#### Additional Requirements

You may need to install Sharp. If you see an error when starting up, try installing it with the following command:

```
pnpm install --include=optional sharp
```


