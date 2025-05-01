# Serverless Web Application Using Generative AI

This project leverages **AWS Amplify** to build a **serverless web application** powered by **Generative AI** using **Amazon Bedrock** and the **Claude 3.5 Sonnet** foundation model.

## 📌 Overview

Users can enter a list of ingredients, and the application will generate delicious recipes based on the input. The application includes:
- A user-friendly **HTML-based interface** for ingredient input
- A **backend** connected to Amazon Bedrock to invoke Claude 3.5 Sonnet for recipe generation

## 🧱 Architecture Diagram

![image](https://github.com/user-attachments/assets/89d00373-d103-4ea5-a366-b6f830d7174e)


## ⚙️ Tech Stack

- **Frontend**: React + TypeScript (via Vite)
- **Backend**: AWS Amplify with GraphQL API and custom authorization
- **AI Model**: Claude 3.5 Sonnet via Amazon Bedrock
- **Hosting**: Amplify Hosting

## 🚀 How It Works

1. User inputs ingredients via the UI
2. Frontend sends request to Amplify GraphQL API
3. Backend invokes Claude 3.5 Sonnet using Bedrock
4. AI model generates a recipe
5. The result is displayed in the frontend

## 🖼️ Outcome

Here are example outcomes of the application:

### 🍲 Example 1
![aws_proj_1](https://github.com/user-attachments/assets/70a23cb6-e115-42a5-88cb-48a6f26b1d8b)


### 🍲 Example 2
![aws_proj_2](https://github.com/user-attachments/assets/12db77ab-90c0-4e9b-a3c2-841d4906b179)

### AWS Amplify Console
![aws_proj_3](https://github.com/user-attachments/assets/c75459a0-fdb5-477f-a1d9-3841143c979e)



## 📝 Setup Instructions

1. Clone the repo and install dependencies:
   ```bash
   git clone https://github.com/your-username/ai-recipe-generator.git
   cd ai-recipe-generator
2. 🧩 Install Dependencies
   ```bash
   npm install
3. ⚙️ Configure AWS Amplify
   ```bash
   npx ampx configure profile
4. 🚧 Start Sandbox Environment
   ```bash
   npx ampx sandbox
5. 🌍 Deploy to AWS
   ```bash
   amplify publish
This command will:
- Deploy all Amplify backend resources (Auth, GraphQL, etc.)
- Host the React frontend using Amplify Hosting

### Locally if you want to run  
💻 Run Frontend Locally
```bash
npm run dev
