# 🥗 AI-Powered Nutrition Agent

> **AICTE Internship Project | Edunet Foundation × IBM SkillsBuild**  
> Domain: Healthcare | Technology: IBM watsonx.ai + LangFlow + IBM Granite Models

---

## 👤 Student Details

| Field | Details |
|---|---|
| **Name** | Aman Raj |
| **Email** | aramanrajaramanraj@gmail.com |
| **Mobile** | 9334955453 |
| **College** | Ramgarh Engineering College, Jharkhand |
| **Program** | B.Tech Computer Science (Pre-Final Year) |

---

## 📌 Project Overview

An intelligent, multi-agent **AI Nutrition Assistant** built on **IBM watsonx.ai** using the **IBM Granite 3.2 8B Instruct** model and orchestrated via **LangFlow**. The agent delivers personalized dietary guidance, meal planning, BMI analysis, and family-specific nutrition recommendations — with deep support for **Indian food culture and cuisine**.

---

## 🎯 Problem Statement

Millions of Indians struggle with diet-related health issues — diabetes, obesity, malnutrition — yet lack access to affordable, personalized nutrition guidance. Generic diet apps fail to account for cultural food preferences, regional diets, religious restrictions, and family-level diversity. The goal is to build an AI agent that bridges this gap through intelligent, real-time, hyper-personalized nutrition advice.

---

## 💡 Proposed Solution

A **multi-agent AI system** built on LangFlow that uses IBM Granite for reasoning and IBM watsonx.ai for deployment and governance:

| Agent | Role |
|---|---|
| 🔍 **Nutrition Knowledge Agent** | Retrieves nutritional data via RAG from USDA/WHO datasets |
| 🍽️ **Diet Recommendation Agent** | Generates personalized meal plans based on health profile |
| 🏥 **Health Advisory Agent** | Provides disease-specific diet guidance (diabetes, thyroid, PCOS) |
| 📋 **Food Log & Feedback Agent** | Analyzes logged meals and provides instant nutritional feedback |

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| **LangFlow** | Visual multi-agent workflow orchestration |
| **IBM watsonx.ai** | Model deployment, embeddings, AI governance |
| **IBM Granite 3.2 8B Instruct** | Core LLM for reasoning, personalization, summarization |
| **RAG (Retrieval-Augmented Generation)** | Fetches real-time nutritional data from trusted sources |
| **FAISS / Chroma Vector DB** | Stores and retrieves nutritional knowledge embeddings |
| **IBM Cloud** | Scalable, secure deployment infrastructure |

---

## ⚙️ LangFlow Components Used

1. **Chat Input** — User queries about nutrition, diet plans, BMI, meal suggestions
2. **IBM watsonx AI Agent** — Core agent powered by Granite 3.2 8B Instruct
3. **System Prompt** — Contains `AGENT_INSTRUCTIONS` (tone, Indian food preferences, safety rules)
4. **File Component** — Loads nutrition knowledge base (USDA/WHO/Indian food composition data)
5. **Text Input** — Family profile data for multi-member diet recommendations
6. **Chat Output** — Displays AI-generated nutrition advice and meal plans

---

## 🗂️ Repository Contents

```
nutrition-agent/
├── app.json                          # LangFlow exported flow (import this!)
├── NutritionAgent_ProblemStatement.pdf  # Problem statement document
├── NutritionAgent_Presentation.pptx    # Project submission presentation
└── README.md                         # This file
```

---

## 🚀 How to Run

### Step 1: Import the LangFlow Flow
1. Go to [LangFlow](https://langflow.org) or your IBM LangFlow instance
2. Click **"Import"** → select `app.json`
3. The full agent flow loads automatically

### Step 2: Configure IBM watsonx.ai Credentials
In the **IBM watsonx AI (Granite)** node:
- Enter your **IBM Cloud API Key**
- Enter your **IBM Cloud Project ID**
- Watson X URL: `https://us-south.ml.cloud.ibm.com`
- Model: `ibm/granite-3-2-8b-instruct`

### Step 3: (Optional) Upload Nutrition Knowledge Base
In the **Nutrition Knowledge Base** node, upload:
- USDA food composition CSV
- WHO dietary guidelines PDF
- Indian food nutrition tables

### Step 4: Run the Agent
- Click **▶ Play** in LangFlow
- Ask the agent: *"Create a 7-day diabetic-friendly Indian diet plan for a 50-year-old man weighing 85kg"*

---

## 🌟 Key Features

- ✅ **Personalized Indian Diet Plans** (vegetarian, vegan, Jain, Halal-friendly)
- ✅ **BMI Calculator** with health category interpretation
- ✅ **Calorie Analysis** for 500+ Indian and international foods
- ✅ **Family Profile Management** (multi-member diet recommendations)
- ✅ **Disease-Specific Diets** (diabetes, thyroid, PCOS, heart health)
- ✅ **RAG-Based Accuracy** (real nutritional data, not hallucinations)
- ✅ **Customizable AGENT_INSTRUCTIONS** in the System Prompt node

---

## 📊 Evaluation Criteria Coverage

| Criteria | How This Project Addresses It |
|---|---|
| **IBM Cloud Platform Usage** | Deployed on IBM watsonx.ai with Granite models; IBM Cloud for infra |
| **Scalability & Innovativeness** | Multi-agent RAG architecture; Indian food specialization is novel |
| **Contribution to Society** | Addresses nutrition inequality in India; accessible to all demographics |
| **Deployment Readiness** | Import `app.json` → configure credentials → run in < 5 minutes |
| **Commercial Viability** | Applicable to hospitals, health apps, insurance companies, schools |
| **Future Scope** | Wearable integration, voice assistant, multilingual support |

---

## 🔮 Future Scope

1. **Wearable Integration** — Sync with fitness trackers for real-time calorie tracking
2. **Voice Assistant** — Multilingual voice input (Hindi, Tamil, Telugu)
3. **Image-Based Meal Logging** — Snap a photo of your thali, get instant nutrition analysis
4. **Doctor Integration** — Share diet reports directly with healthcare providers
5. **Regional Language Support** — Full support for 10+ Indian languages

---

## 📜 License

This project is submitted as part of the AICTE Internship Program in partnership with Edunet Foundation and IBM SkillsBuild.

---

*Built with ❤️ using IBM Granite + LangFlow | Aman Raj | 2025*
