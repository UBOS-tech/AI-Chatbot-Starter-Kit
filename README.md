<div align="center">

<img src="https://github.com/user-attachments/assets/05e922cb-dfd8-42d7-bbd8-d9f31607974a" alt="logo" width="200" height="auto" />

# AI Chatbot Starter Kit

An  README for template AI Chatbot Starter Kit

[![contributors](https://img.shields.io/badge/contributors-3-blue)](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/graphs/contributors)
[![last commit](https://img.shields.io/github/last-commit/UBOS-Asset-Store/Generative-AI-Bot-NR?color=blue)](https://github.com/UBOS-Asset-Store/Generative-AI-Bot-NR/commits/master)
[![forks](https://img.shields.io/github/forks/UBOS-Asset-Store/Generative-AI-Bot-NR?style=social)](https://github.com/UBOS-Asset-Store/Generative-AI-Bot-NR/network/members)
[![stars](https://img.shields.io/github/stars/UBOS-tech/AI-Bot-Custom-GPT?style=social)](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/stargazers)
[![open issues](https://img.shields.io/github/issues/UBOS-tech/AI-Bot-Custom-GPT?color=blue)](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/issues)
[![license](https://img.shields.io/badge/license-CC0--1.0-blue)](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/blob/main/LICENSE.txt)

#### [View Demo](https://platform.ubos.tech/?aiBotV3=true) · [Report Bug](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/issues) · [Request Feature](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/issues)

[![Deploy on UBOS](https://ubos.tech/wp-content/uploads/2024/07/deploy_ubos.svg)](https://platform.ubos.tech/?templateId=65397499fe34080011cedbb5)

</div>

## 📔 Table of Contents

- [:star2: About the Project](#star2-about-the-project)
  - [:space_invader: Built With](#space_invader-built-with)
  - [:package: Dependencies](#package-dependencies)
  - [:dart: Features](#dart-features)
  - [:key: Environment Variables](#key-environment-variables)
- [:toolbox: Getting Started](#toolbox-getting-started)
  - [:bangbang: Prerequisites](#bangbang-prerequisites)
  - [:gear: Installation](#gear-installation)
- [:eyes: Usage](#eyes-usage)
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

- [AppSmith](https://github.com/UBOS-Asset-Store/Generative-AI-Bot-UI) 
- [Node-RED](https://github.com/UBOS-Asset-Store/Generative-AI-Bot-NR)
- [MongoDB](https://www.mongodb.com/)
- [ChromaDB](https://www.trychroma.com/)
- [Pinecone](https://www.pinecone.io/)

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

### :dart: Features

- `Multiple LLM Models: GPT-4o, GPT-4o Mini, Claude 3.5, Llama 3.1`
- `Multi-Language Support`
- `Unlimited Knowledge Bases`
- `AI Chatbot Personality Configuration`
- `Unlimited Chatbots`
- `Use Your Own OpenAI API Key`
- `Seamless Integration`

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


## :eyes: Usage

### ADA-VectorDB-ChatGPT

![image](https://github.com/user-attachments/assets/29199ec9-a548-43c1-9fff-8dc51b942c65)

**Key Components**

1. **Input Data Unification**: Consolidates various configuration parameters and user input into a standardized format.
2. **Embedding Generation**: Utilizes OpenAI's text-embedding-ada-002 model to create embeddings for user queries.
3. **Vector Database Integration**: Supports both Pinecone and Chroma for semantic search functionality.
4. **GPT Model Integration**: Uses OpenAI's chat completion API to generate responses based on retrieved context and user queries.
5. **History Management**: Saves conversation history for potential future use or analysis.

**Flow Structure**

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

**Key Functions**

- `Input Data Unification`: Standardizes input data format
- `create vector`: Prepares the context for GPT based on vector database results
- `send to user from chat`: Processes GPT response and prepares it for the user
- `save history`: Stores conversation details for future reference

**Integrations**

- OpenAI API: For embedding generation and GPT-based response generation
- Pinecone: Vector database for semantic search
- Chroma: Alternative vector database option
- Telegram Bot API: For sending typing indicators and messages (implied from the code)

**Configuration**

The flow requires several configuration parameters, including:

- OpenAI API key
- Vector database credentials (Pinecone or Chroma)
- Bot settings (name, prepared messages, AI settings)
- Telegram bot token (for sending messages and typing indicators)

**Error Handling**

The flow includes basic error handling, particularly for API failures and unexpected responses. It uses prepared error messages when issues occur.

**Debugging**

Multiple debug nodes are included throughout the flow for monitoring and troubleshooting purposes.

### **RAG Architecture**

Our AI Bot utilizes a Retrieval-Augmented Generation (RAG) architecture to provide accurate and context-aware responses. 

![image](https://github.com/user-attachments/assets/f83c4ee5-0e94-4330-9795-fe9c6e8f6c41)

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

This source code is licensed under the MIT license.  See [LICENSE.txt](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/blob/main/LICENSE.txt) for more information

## :handshake: Contact

UBOS Team - [@ubos_tech](https://twitter.com/ubos_tech) - [support@ubos.tech](mailto:support@ubos.tech)

Project Link: [AI-Bot-Custom-GPT](https://github.com/UBOS-tech/AI-Bot-Custom-GPT)


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

