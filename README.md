# AI Agent Projects using Google ADK

This repository contains an end-to-end implementation of a **Personal Expense Assistant** AI agent built using the **Google Agent Development Kit (ADK)**.  
The project demonstrates how to design, implement, and deploy a production-quality multimodal AI agent on Google Cloud. It follows best practices for integrating **Vertex AI**, **Firestore**, **Cloud Storage**, and **Gradio** into a unified conversational system.

---

## Personal Expense Assistant using Google ADK

**Description:**  
The Personal Expense Assistant is a multimodal AI agent that helps users manage and analyze their financial receipts. It can process uploaded receipt images, extract structured data such as total amount, merchant, and transaction date, and provide insights through natural language queries. The assistant integrates seamlessly with Google Cloud services for data storage, querying, and visualization.

**Features:**
- Extract expense data from uploaded receipt images using Gemini 2.5 Flash  
- Store structured data in Cloud Firestore  
- Retrieve and filter receipts through natural language search or metadata  
- Provide spending analysis and summaries through conversational interaction  
- Includes a Gradio-based web frontend for user-friendly interaction  
- Fully deployable on Google Cloud Run for scalable access  

**Deployment:**  
The project has been successfully deployed to **Google Cloud Run**.  
Below is a screenshot of the deployed service:
<img width="1259" height="383" alt="image" src="https://github.com/user-attachments/assets/2ad91736-7ace-494d-830c-2c72aa24d14b" />



**Reference Guides:**  
- [Google Codelab: Build a Multimodal Personal Expense Assistant using Google ADK](https://codelabs.developers.google.com/personal-expense-assistant-multimodal-adk)  
- [Medium: Going Multimodal with Agent Development Kit — Personal Expense Assistant with Gemini 2.5 (Part 1)](https://medium.com/google-cloud/going-multimodal-with-agent-development-kit-personal-expense-assistant-with-gemini-2-5-480b031c7d5a)  
- [Medium: Going Multimodal with Agent Development Kit — Personal Expense Assistant with Gemini 2.5 (Part 2)](https://medium.com/google-cloud/going-multimodal-with-agent-development-kit-personal-expense-assistant-with-gemini-2-5-17626aaee9a2)

**Video Walkthrough:**  
[YouTube Video](https://youtu.be/M0CSdEnPBao)

---

This project demonstrates how to:
- Build a multimodal AI agent using Google ADK  
- Integrate Gemini models with Firestore and Cloud Storage  
- Create conversational interfaces using Gradio  
- Deploy intelligent, serverless AI systems on Google Cloud
