<div align="center">

<img src="https://github.com/user-attachments/assets/05e922cb-dfd8-42d7-bbd8-d9f31607974a" alt="logo" width="200" height="auto" />

# AI Chatbot Starter Kit

An  README for template AI Chatbot Starter Kit

[![contributors](https://img.shields.io/badge/contributors-1-blue)](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/graphs/contributors)
[![last commit](https://img.shields.io/badge/last%20commit-unknown-lightgrey)](https://github.com/UBOS-Asset-Store/Generative-AI-Bot-NR/commits/master/)
[![forks](https://img.shields.io/github/forks/UBOS-Asset-Store/Generative-AI-Bot-NR?style=social)](https://github.com/UBOS-Asset-Store/Generative-AI-Bot-NR/network/members)
[![stars](https://img.shields.io/github/stars/UBOS-tech/AI-Bot-Custom-GPT?style=social)](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/stargazers)
[![open issues](https://img.shields.io/github/issues/UBOS-tech/AI-Bot-Custom-GPT?color=green)](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/issues)
[![license](https://img.shields.io/badge/license-CC0--1.0-green)](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/blob/main/LICENSE.txt)

#### [View Demo](https://platform.ubos.tech/?aiBotV3=true) · [Report Bug](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/issues) · [Request Feature](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/issues)

</div>

## 📔 Table of Contents

- [:star2: About the Project](#star2-about-the-project)
  - [:space_invader: Built With](#space_invader-built-with)
  - [:package: Dependencies](#package-dependencies)
  - [:dart: Features](#dart-features)
  - [:robot: ADA-VectorDB-ChatGPT](#robot-ada-vectordb-chatgpt)
  - [:key: Environment Variables](#key-environment-variables)
- [:toolbox: Getting Started](#toolbox-getting-started)
  - [:bangbang: Prerequisites](#bangbang-prerequisites)
  - [:gear: Installation](#gear-installation)
- [:compass: Roadmap](#compass-roadmap)
- [:wave: Contributing](#wave-contributing)
- [:warning: License](#warning-license)
- [:handshake: Contact](#handshake-contact)
- [:gem: Acknowledgements](#gem-acknowledgements)


## :star2: About the Project
The AI Bot – Custom GPT project, built by the UBOS team, leverages Node-RED for workflow orchestration, MongoDB for scalable data storage, and an intuitive UI based on Appsmith. This project empowers users to create, customize, and deploy advanced chatbots with ease.

<div align="center">
  <img src="https://ubos.tech/wp-content/uploads/2023/07/demo_pages_analytics.png" alt="demo_pages_analytics" width="30%" />
  <img src="https://ubos.tech/wp-content/uploads/2024/07/20240726-143713-jpeg.webp" alt="start page" width="30%" />
  <img src="https://ubos.tech/wp-content/uploads/2023/07/demo_pages_setupconfig.png" alt="start page" width="30%" />
</div>

### :space_invader: Built With

<details open>
  <summary>Client</summary>
  <ul>
    <li><a href="https://www.appsmith.com/">AppSmith</a> - UI Based on AppSmith</li>
  </ul>
</details>

<details open>
  <summary>Server</summary>
  <ul>
    <li><a href="https://nodered.org/">Node-RED</a></li>
  </ul>
</details>

<details open>
  <summary>Databases</summary>
  <ul>
    <li><a href="https://www.mongodb.com/">MongoDB</a></li>
    <li><a href="https://www.trychroma.com/">ChromaDB</a></li>
    <li><a href="https://www.pinecone.io/">Pinecone</a></li>
  </ul>
</details>

Please ensure these dependencies are installed and properly configured to utilize the full capabilities of the AI Bot.

![Technology Stack](https://ubos.tech/wp-content/uploads/2024/07/ubos_example-1.png)

## :package: Dependencies

Our project relies on several Node-RED nodes and additional libraries. Below is a list of the key dependencies:

### Node-RED Nodes
- `node-red-contrib-fs`: `1.4.1` - File system operations
- `node-red-contrib-loop-processing`: `0.5.1` - Loop processing
- `node-red-contrib-openai-ubos`: `1.0.4` - OpenAI integration
- `node-red-contrib-telegrambot`: `15.1.9` - Telegram bot integration
- `node-red-node-mongodb`: `0.2.5` - MongoDB integration
- `node-red-contrib-pdfparse`: `1.0.6` - PDF parsing
- `node-red-contrib-pinecone`: `1.0.7` - Pinecone integration
- `node-red-contrib-chromadb`: `1.0.0` - Chroma DB integration

### Libraries
- `jsdom`: `22.1.0` - JavaScript DOM manipulation
- `@martip/node-red-xlsx`: `1.0.2` - XLSX file handling
- `chromadb`: `1.5.11` - Chroma DB client
- `openai`: `4.14.2` - OpenAI API client
- `moment`: `2.29.4` - Date and time manipulation
- `bcrypt`: `5.1.1` - Password hashing

Please ensure these dependencies are installed and properly configured to utilize the full capabilities of the AI Bot.

![Technology Stack](https://github.com/user-attachments/assets/25bce59b-df01-4ff4-9178-317f155d47fc)

### :dart: Features

- `Multiple LLM Models: GPT-4o, GPT-4o Mini, Claude 3.5, Llama 3.1`
- `Multi-Language Support`
- `Unlimited Knowledge Bases`
- `AI Chatbot Personality Configuration`
- `Unlimited Chatbots`
- `Use Your Own OpenAI API Key`
- `Seamless Integration`


### :robot: ADA-VectorDB-ChatGPT

![image](https://github.com/user-attachments/assets/29199ec9-a548-43c1-9fff-8dc51b942c65)


1. **Input Processing**: 
   - Unifies input data (BOT_NAME, DATABASE settings, AI_SETTINGS, etc.)
   - Generates embeddings for user queries

2. **Vector Database Query**:
   - Determines the appropriate vector database (Pinecone or Chroma)
   - Queries the database with the generated embedding

3. **Context Creation**:
   - Processes retrieved vectors to create a context for the GPT model

4. **GPT Query**:
   - Formulates a prompt including the context and user query
   - Sends the prompt to OpenAI's chat completion API

5. **Response Handling**:
   - Processes the GPT response
   - Saves conversation history
   - Sends the response back to the user

### :key: Environment Variables

**Node-RED Environment Variables**
- `nodered`
- `uiUrl`
- `VECTORDB-CHROMA-HOST-NAME`
- `AIBOTDB-MONGO-HOST-NAME`
- `AIBOTDB-MONGO-DB-NAME`
- `AIBOTDB-MONGO-USER-NAME`
- `AIBOTDB-MONGO-PASSWORD`
- `OPENAI-KEY`
- `PINECONE-INDEX`
- `PINECONE-API-KEY`
- `PINECONE-URL`

**UI Environment Variables**
- `uiUrl`
- `nodeUrl`

## :toolbox: Getting Started

### :bangbang: Prerequisites

- Sign up for a free [UBOS](https://platform.ubos.tech/) account.
- Ensure you have a server with at least 2GB of RAM and 1 CPU.

### :gear: Installation

**White Label**
1. Open the Template Manager on the UBOS platform and search for "AI Chatbot Starter Kit" or use [this direct link](https://platform.ubos.tech/?templateId=6683ed1f52da610011914678).
2. Select your desired server plan.
3. Click on "Install."
4. Wait 5-7 minutes for the installation to complete and all settings to be applied.

**SAAS**
1. Access the project using [this link](https://platform.ubos.tech/?aiBotV3=true).

## :compass: Roadmap

- [x] Implement more robust error handling and logging.
- [x] Multi-Language Support.
- [x] Add Models: GPT-4o, GPT-4o Mini.
- [ ] Add support for additional vector databases.
- [ ] Enhance the context creation process for more accurate responses.
- [ ] Implement rate limiting to prevent API overuse.
- [x] Integrate additional Large Language Models (LLMs).
- [ ] Add CRM integration.


## :wave: Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

## :warning: License

Distributed under the no License. See `LICENSE.txt` for more information.

## :handshake: Contact

- support@ubos.tech;
- [discord](https://discord.com/invite/dt59QaptH2)

## :gem: Acknowledgements

- [Working with Chroma DB](https://community.ubos.tech/dmytro_mytsak/how-to-work-with-chroma-db-4oe)
- [Training Bots with Different Types of Sources](https://community.ubos.tech/vika/how-to-training-bot-by-different-types-of-source-46h9)
- [ChatGPT Prompt Configuration](https://community.ubos.tech/vika/chatgpt-prompt-configuration-14p2)
- [Setting Up a Messenger Bot: A Step-by-Step Guide](https://community.ubos.tech/olha/setting-up-a-messenger-bot-a-step-by-step-guide-2hk4)
- [Setting Up an Instagram Bot: A Step-by-Step Guide](https://community.ubos.tech/olha/setting-up-an-instagram-bot-a-step-by-step-guide-k95)
- [Guide to Setting Up a WhatsApp Bot on Facebook API](https://community.ubos.tech/olha/step-by-step-guide-setting-up-whatsapp-bot-on-facebook-api-gn3)
- [Working with Large Files in AI Chatbots](https://community.ubos.tech/vika/working-with-large-files-in-ai-chat-bot-2aap)
- [Customer Support Chatbot](https://community.ubos.tech/vika/customersupportchatbot-1ac8)

Additional Resources:
- [7-Minute Guide to Training Custom AI Chatbots with a Private Knowledge Base](#) 
- [Getting Started with UBOS.tech: A Comprehensive Platform Guide](#) – Platform overview and API connection.
- [Build AI-Powered CRUD App with Node-RED, Appsmith, MongoDB, and OpenAI API | Course Intro](#) – Guide to building CRUD applications.

