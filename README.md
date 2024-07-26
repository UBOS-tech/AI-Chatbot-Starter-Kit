<div align="center">

<img src="https://github.com/user-attachments/assets/05e922cb-dfd8-42d7-bbd8-d9f31607974a" alt="logo" width="200" height="auto" />

# AI Chatbot Starter Kit

An  README for template AI Chatbot Starter Kit

[![contributors](https://github.com/user-attachments/assets/45df29b9-b0ee-484e-84b4-dcb9d7dfe212)](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/graphs/contributors)
[![last update](https://github.com/user-attachments/assets/09182d4a-5411-43f9-a60f-87c3688d35b1)](https://github.com/UBOS-Asset-Store/Generative-AI-Bot-NR/commits/master/)
[![forks](https://github.com/user-attachments/assets/faac0d93-fa7d-4325-ae00-f66950380f9a)](https://github.com/UBOS-Asset-Store/Generative-AI-Bot-NR/network/members)
[![stars](https://github.com/user-attachments/assets/c0a3ffa4-841a-42c8-9b44-7f9651a3ab19)](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/stargazers)
[![open issues](https://github.com/user-attachments/assets/9afe0b10-4bc1-4af3-84b3-0528c6123ff6)](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/issues)
[![license](https://github.com/user-attachments/assets/68582236-5197-4dfe-8827-af9c983ea9b2)](https://github.com/Louis3797/awesome-readme-template/blob/master/LICENSE)

#### [View Demo](https://platform.ubos.tech/?aiBotV3=true) · [Report Bug](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/issues) · [Request Feature](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/issues)

</div>


## 📔 Table of Contents

- [:star2: About the Project](#star2-about-the-project)
  - [:camera: Screenshots](#camera-screenshots)
  - [:space_invader: Tech Stack](#space_invader-tech-stack)
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

### :camera: Screenshots

<div align="center">
  <img src="https://ubos.tech/wp-content/uploads/2023/07/demo_pages_analytics.png" alt="demo_pages_analytics" width="30%" />
  <img src="https://ubos.tech/wp-content/uploads/2024/07/20240726-143713-jpeg.webp" alt="start page" width="30%" />
  <img src="https://ubos.tech/wp-content/uploads/2023/07/demo_pages_setupconfig.png" alt="start page" width="30%" />
</div>

### :space_invader: Tech Stack

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
  <summary>Node-RED Nodes</summary>
  <ul>
    <li><a href="https://flows.nodered.org/node/node-red-contrib-fs">node-red-contrib-fs</a></li>
    <li><a href="https://flows.nodered.org/node/node-red-contrib-loop-processing">node-red-contrib-loop-processing</a></li>
    <li><a href="https://flows.nodered.org/node/node-red-contrib-openai-ubos">node-red-contrib-openai-ubos</a></li>
    <li><a href="https://flows.nodered.org/node/node-red-contrib-telegrambot">node-red-contrib-telegrambot</a></li>
    <li><a href="https://flows.nodered.org/node/node-red-node-mongodb">node-red-node-mongodb</a></li>
    <li><a href="https://flows.nodered.org/node/node-red-contrib-pdfparse">node-red-contrib-pdfparse</a></li>
    <li><a href="https://flows.nodered.org/node/node-red-contrib-pinecone">node-red-contrib-pinecone</a></li>
    <li><a href="https://flows.nodered.org/node/node-red-contrib-chromadb">node-red-contrib-chromadb</a></li>
  </ul>
</details>

<details open>
  <summary>Libraries</summary>
  <ul>
    <li><a href="https://github.com/jsdom/jsdom">jsdom</a></li>
    <li><a href="https://www.npmjs.com/package/@martip/node-red-xlsx">node-red-xlsx</a></li>
    <li><a href="https://www.trychroma.com/">chromadb</a></li>
    <li><a href="https://github.com/openai/openai-node">openai</a></li>
    <li><a href="https://momentjs.com/">moment</a></li>
    <li><a href="https://github.com/kelektiv/node.bcrypt.js">bcrypt</a></li>
  </ul>
</details>

![Technology Stack](https://github.com/user-attachments/assets/25bce59b-df01-4ff4-9178-317f155d47fc)

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


### :dart: Features

- `Custom GPT Training`
- `Multi-Platform Integration`
- `Advanced Knowledge Management`
- `Dynamic Behavior Configuration`
- `Multi-language Support`

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

- Implement more robust error handling and logging.
- Add support for additional vector databases.
- Enhance the context creation process for more accurate responses.
- Implement rate limiting to prevent API overuse.
- Integrate additional Large Language Models (LLMs).
- Add CRM integration.

## :wave: Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

## :warning: License

Distributed under the no License. See LICENSE.txt for more information.

## Resources

👉 How to train your custom GPT Bot – [ChatGPT Prompt Configuration](https://community.ubos.tech/vika/chatgpt-prompt-configuration-14p2?_gl=1*1doc1f*_ga*MTYyOTM3NTU4OS4xNzAyNTQ4ODg2*_ga_YERL0FNTNF*MTcwMzA4NDA0Ni45LjEuMTcwMzA4NDc0MC4zNi4wLjA.&_ga=2.254612552.1594591842.1703072755-1629375589.1702548886)

👀 [How to train ChatGPT and build knowledge base?](https://www.youtube.com/watch?v=1fspLZMhTxA&ab_channel=UBOS%3Alow-codeplatformtobuildGPTandAIapps)

Imagine being able to launch a fully customized AI chatbot on Telegram, WhatsApp, Instagram, or Facebook within minutes, without writing a single line of code. With our AI Bot Template, that dream becomes a reality.
