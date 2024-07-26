<div align="center">

<img src="https://github.com/user-attachments/assets/05e922cb-dfd8-42d7-bbd8-d9f31607974a" alt="logo" width="200" height="auto" />

# AI Chatbot Starter Kit

An  README for template AI Chatbot Starter Kit
<img src="https://github.com/user-attachments/assets/05e922cb-dfd8-42d7-bbd8-d9f31607974a" alt="logo" width="200" height="auto" />
[![contributors](https://github.com/user-attachments/assets/cd27ba60-1041-4277-9f79-622653a93445)](https://github.com/UBOS-tech/AI-Bot-Custom-GPT/graphs/contributors)
[![last update](https://img.shields.io/github/last-commit/Louis3797/awesome-readme-template)](https://github.com/Louis3797/awesome-readme-template/blob/main)
[![forks](https://img.shields.io/github/forks/Louis3797/awesome-readme-template)](https://github.com/Louis3797/awesome-readme-template/network/members)
[![stars](https://img.shields.io/github/stars/Louis3797/awesome-readme-template)](https://github.com/Louis3797/awesome-readme-template/stargazers)
[![open issues](https://img.shields.io/github/issues/Louis3797/awesome-readme-template)](https://github.com/Louis3797/awesome-readme-template/issues/)
[![license](https://img.shields.io/github/license/Louis3797/awesome-readme-template.svg)](https://github.com/Louis3797/awesome-readme-template/blob/master/LICENSE)

#### [View Demo](https://github.com/Louis3797/awesome-readme-template/) · [Documentation](https://github.com/Louis3797/awesome-readme-template) · [Report Bug](https://github.com/Louis3797/awesome-readme-template/issues/) · [Request Feature](https://github.com/Louis3797/awesome-readme-template/issues/)

</div>

AI Bot – Custom GPT
==============
<p align="center">
  <img width="50%" align="center" alt="Ubos - End-to-End Software Development Platform" src="https://ubos.tech/wp-content/uploads/2023/03/cropped-Group-21015-1.png">
</p>

<h3 align="center">
  <b><a href="https://documentation.ubos.tech/docs/intro">Get Started</a></b>
  •
  <a href="https://community.ubos.tech/">Community</a>
  •
  <a href="https://www.youtube.com/@ubos_tech">Youtube</a>
  •
  <a href="https://discord.com/invite/dt59QaptH2">Discord</a>
  •
  <a href="https://github.com/UBOS-tech">GitHub</a>
  </h3>

<div align="center">
  
  [![Use template](https://ubos.tech/wp-content/uploads/2023/06/download-logo.png)](https://ubos.tech/listing/ai-chatbot/)
  [![Use template](https://ubos.tech/wp-content/uploads/2023/06/Group-19.png)](https://youtube.com/playlist?list=PLO6yg7spqnjkkk0wLu6vcNoIItLV0zLSO&si=4TboTI9nAjxrMQsY)
  
</div>

## Build custom GPT Bots

**Train ChatGPT, 1000+ Integrations, Open Source, Extend with JavaScript**

![Integrations](https://ubos.tech/wp-content/uploads/2024/07/AI-Chatbot-Visual.png)

Are you seeking an edge in today’s competitive AI market? Your search ends here. UBOS.tech presents a custom GPT template, enabling businesses and developers to implement Generative AI technology today.

## Dependencies

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


## Key Technologies

### Node-RED
A powerful tool for designing workflows and orchestrating integrations. Node-RED's visual interface allows seamless connection between various services and APIs, facilitating complex automation scenarios.

### Chroma DB
Utilized for scalable and efficient data storage, Chroma DB handles large datasets and supports rapid retrieval, ensuring quick access to information.

### Pinecone
Manages vector databases to handle complex data relationships and queries with high efficiency, essential for advanced search and recommendation functionalities.

### MongoDB
Provides a flexible, scalable database solution for storing and managing chatbot data and configurations, supporting diverse data models and structures.

## Technical Features

### Custom GPT Training
Train and fine-tune your GPT models on your data to create specialized conversational agents. Supports integration with various data sources, including Google Drive, Notion, and AWS S3.

### Multi-Platform Integration
Easily deploy chatbots across messaging platforms like Telegram, WhatsApp, Instagram, and Messenger. Use our chat widget for website integration.

### Advanced Knowledge Management
Build and manage multiple knowledge bases with support for various input methods—file uploads, text entry, web scraping, and FAQs.

### Dynamic Behavior Configuration
Customize bot behavior per knowledge base with tailored responses, personalities, and handling of unusual chat scenarios.

### Multi-language Support
Implement chatbots in 7 different languages to cater to a global audience.

### Admin Panel CRM
Access a comprehensive admin panel to monitor and analyze chatbot interactions, gaining insights into user behavior and engagement.


## Technology Stack

![Technology Stack](https://github.com/user-attachments/assets/25bce59b-df01-4ff4-9178-317f155d47fc)

### Node-RED
UBOS AI Chatbot utilizes Node-RED for orchestrating workflows and integrations. This powerful tool allows you to easily connect different services and APIs with a visual flow-based interface.

### Chroma DB
Leverage Chroma DB for efficient and scalable data storage and retrieval, enabling the chatbot to access and manage large datasets quickly.

### Pinecone
Use Pinecone for vector database management, allowing the chatbot to handle complex data relationships and queries with high performance.

### MongoDB
Implement MongoDB for robust, flexible, and scalable database solutions, providing a strong backbone for storing chatbot data and configurations.

![Technology Stack](https://ubos.tech/wp-content/uploads/2024/07/ubos_example-1.png)

## Node-RED Flow Details

### ADA-VDB-GPT

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

### Key Functions

- `Input Data Unification`: Standardizes input data format
- `create vector`: Prepares the context for GPT based on vector database results
- `send to user from chat`: Processes GPT response and prepares it for the user
- `save history`: Stores conversation details for future reference

### Configuration

The flow requires several configuration parameters, including:

- OpenAI API key
- Vector database credentials (Pinecone or Chroma)
- Bot settings (name, prepared messages, AI settings)
- Telegram bot token (for sending messages and typing indicators)

### Error Handling and Debugging

The flow includes basic error handling for API failures and unexpected responses. Multiple debug nodes are included throughout the flow for monitoring and troubleshooting purposes.

### Notes for Developers

- Ensure all required Node-RED nodes are installed, particularly for Chroma DB integration.
- Properly configure environment variables for sensitive information like API keys.
- The flow uses Node-RED's link nodes, implying that there might be additional connected flows not shown in this snippet.
- The typing indicator functionality suggests this is part of a larger chatbot implementation, possibly for Telegram.

### Future Improvements

- Implement more robust error handling and logging
- Add support for additional vector databases
- Enhance the context creation process for more accurate responses
- Implement rate limiting to prevent API overuse
## Resources

👉 How to train your custom GPT Bot – [ChatGPT Prompt Configuration](https://community.ubos.tech/vika/chatgpt-prompt-configuration-14p2?_gl=1*1doc1f*_ga*MTYyOTM3NTU4OS4xNzAyNTQ4ODg2*_ga_YERL0FNTNF*MTcwMzA4NDA0Ni45LjEuMTcwMzA4NDc0MC4zNi4wLjA.&_ga=2.254612552.1594591842.1703072755-1629375589.1702548886)

👀 [How to train ChatGPT and build knowledge base?](https://www.youtube.com/watch?v=1fspLZMhTxA&ab_channel=UBOS%3Alow-codeplatformtobuildGPTandAIapps)

Imagine being able to launch a fully customized AI chatbot on Telegram, WhatsApp, Instagram, or Facebook within minutes, without writing a single line of code. With our AI Bot Template, that dream becomes a reality.
