# Oracle APEX E-Commerce with AI Assistant 🛒🤖

## 📌 Project Overview
This repository contains a full-featured Enterprise E-Commerce application built using **Oracle APEX**, seamlessly integrated with a powerful **Generative AI Chatbot** to enhance customer support and user experience. 

The project demonstrates modern Oracle APEX development practices, including AI integration, RESTful services, and professional version control using APEXlang.

## ✨ Key Features
*   **E-Commerce Core:** Complete shopping online features including product catalogs, shopping carts, department lookups, and administrative dashboards.
*   **Smart AI Assistant:** An integrated AI Chatbot built using **Groq API** and the **Llama 3** generative model to provide instant, contextual customer support.
*   **Conversational Memory:** The AI assistant is backed by a custom database schema (`chat_sessions` & `chat_messages`) to retain context during user interactions.
*   **Modern Version Control:** The application is exported using the readable **APEXlang** format (JSON/YAML), allowing precise tracking of page, component, and code changes across versions.

## 🛠️ Technologies & Tools
*   **Framework:** Oracle APEX 26.1
*   **Database:** Oracle Database (PL/SQL, SQL)
*   **AI Integration:** Generative AI Services, Groq API (Llama 3 Model)
*   **Web Services:** REST Data Sources, Web Credentials (HTTP Header Authentication)
*   **DevOps:** Git, GitHub, APEXlang Export

## 🚀 How to Run Locally
1. Clone this repository to your local machine.
2. Open your Oracle APEX Workspace.
3. Import the application using the `shopping-online.zip` or the main `application.apx` file.
4. Go to **Workspace Utilities > Web Credentials** and configure your Groq API Key under `GROQ_CRED_KEY`.
5. Run the application and click on **AI Assistant** in the Navigation Bar to start chatting!

---
*Developed by Ahmed Samir.*
