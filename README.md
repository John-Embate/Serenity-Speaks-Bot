# 🌸 Serenity Speaks Bot 🌸

Welcome to the 🌸 Serenity Speaks Bot 🌸 repository! This project, developed by Apollo Analytics, utilizes state-of-the-art technology to provide a personalized and secure mental wellness companion. Powered by Flowise and Ollama's Llama3 model, this bot offers an interactive and intuitive interface for users seeking mental health support.

## Installation

### Prerequisites
Before installing Flowise, you will need Node.js installed on your machine. You can install Node.js from the [Node.js Download Link](https://nodejs.org/en/download/package-manager).

### Installing Flowise
With Node.js installed, open your terminal or command prompt and run the following commands:

```bash
npm install -g flowise
npx flowise start
```

After running these commands, Flowise should be up and running 🚀. You can access it by navigating to [http://localhost:3000](http://localhost:3000).

## Importing Serenity Speaks Bot Chatflow 📥
To import the Serenity Speaks Bot Chatflow:

1. Go to [http://localhost:3000](http://localhost:3000) 🌐.
2. Navigate to the Chatflows section from the sidebar menu and click "Add New" 🆕.
3. Click the settings icon, then select "Load Chatflow" ⚙️.
4. Navigate to where the `Serenity Speaks Bot - Apollo Analytics.json` chatflow file is located and load it 📂.
5. Save the chatflow by clicking the save button and assigning a filename 💾.

## Setting Up Ollama and Llama3 🛠️
To use Llama3 locally:

1. Download Ollama from [this link](https://ollama.com/download) and run the executable file 📦.
2. Open your terminal and run the following commands to install and serve the Llama3 model:

   ```bash
   ollama run llama3
   ollama serve
  ```
