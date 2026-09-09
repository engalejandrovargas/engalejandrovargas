<div align="center">

# Alejandro Vargas

### Software Engineer · AI/ML and Full-Stack

15+ years building production systems: clinical ML pipelines in Japan, multi-tenant SaaS platforms<br/>architected and shipped end to end, and RAG systems for querying large private document sets.

[![Website](https://img.shields.io/badge/alejandrovargas.co-0D1117?style=flat-square&logo=googlechrome&logoColor=white)](https://alejandrovargas.co)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square)](https://linkedin.com/in/luis-alejandro-vargas-ramos/)
[![Email](https://img.shields.io/badge/hello@alejandrovargas.co-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:hello@alejandrovargas.co)

Spanish (native) · English (C1, IELTS 7) · Japanese (JLPT N3)

</div>

---

## Products

Platforms I architected and shipped end to end, covering data modelling, payments, background processing, and deployment.

### [CalorieTally](https://calorietally.com) · AI nutrition tracking SaaS

Multi-modal meal logging through text, voice, and food photography, an AI nutritionist chat that routes between models based on query complexity, and a complete PayPal subscription lifecycle across three tiers.

`Django 5.2` `PostgreSQL` `Cloudflare R2` `OAuth2` `Computer Vision` `Speech-to-Text`

### [Travelforce](https://travelforce.app) · B2B multi-tenant SaaS for travel agencies

AI-generated itineraries and itemized quotes, with every AI response anchored to external API data and validated against a schema so trip intelligence cannot hallucinate. Row-level tenant isolation across 15+ tables, ten scheduled background jobs, and 215 passing tests covering auth flows, tenant isolation, and quote state transitions.

`React 19` `TypeScript` `Node.js` `Express` `Prisma` `PostgreSQL` `Redis` `BullMQ`

### [OperX](https://operx.pro) · LATAM-first CMMS *(in progress)*

Closes the entire field maintenance loop: work order created, technician dispatched, before photos, fix, after photos, customer signs on screen, time tracked. The mobile app is offline-first with bidirectional PostgreSQL to SQLite sync, so technicians keep working in dead zones and the data reconciles when they resurface.

`Django 6` `DRF` `React Native` `PowerSync` `Celery` `FastAPI` `Deepgram`

### Documenty · Multi-tenant document RAG platform

Retrieval-augmented generation over large private document sets: chunking strategies, embeddings, vector search, and async ingestion pipelines. *Private repository, demo available on request.*

`Django` `Celery` `LangChain` `Vector search` `Embeddings`

---

## Selected engineering work

**[django-tasks-vs-celery](https://github.com/engalejandrovargas/django-tasks-vs-celery)**

A fair benchmark of Django 6's native `django-tasks` (DatabaseBackend) against Celery, with both running as real worker processes over 35,000+ smart meter readings. Ships with a Chart.js comparison dashboard, a REST API documented in Swagger, and a "when to use each" breakdown rather than a verdict, because the honest answer depends on whether you want the operational cost of Redis.

<details>
<summary><b>More studies and experiments</b></summary>

<br/>

**Machine learning and forecasting**
- [Petrol Price Forecasting](https://github.com/engalejandrovargas/Petrol-Price-Forecasting-Using-Arima-and-LSTM-) comparing ARIMA against LSTM
- [Credit Quota Prediction](https://github.com/engalejandrovargas/Prediction-of-Credit-quota-Using-Machine-Learning) from company financial data
- [Body Fat Prediction](https://github.com/engalejandrovargas/BodyFat-Predictions-Using-RandomForest) with Random Forest
- [Absence Analysis](https://github.com/engalejandrovargas/McDonalds-absence-ML-analysis) on workforce data
- [Pizza Price Prediction](https://github.com/engalejandrovargas/Price-prediction-of-pizza-using-autoML) with AutoML
- [Course Recommender](https://github.com/engalejandrovargas/Udemy-course-recommendation-system-using-Cosine-Similarity-Matrix) using a cosine similarity matrix
- [Wastewater Treatment Simulation](https://github.com/engalejandrovargas/Simulating-Random-Events-in-Wastewater-Treatment), stochastic modelling from my chemical engineering years

**Computer vision and audio**
- [Vehicle Detection and Counting](https://github.com/engalejandrovargas/Vehicle_Detect_Count_CV2_flask) with OpenCV and Flask
- [Chinese Character Recognition](https://github.com/engalejandrovargas/MNIST-Chinese-Characters-Flask) served through Flask
- [Deep Learning Applications in Audio](https://github.com/engalejandrovargas/DeepLearning-applications-in-Audio)

**LLMs and NLP**
- [Japanese Book Processing](https://github.com/engalejandrovargas/Japanese-books-using-gemini-api) with the Gemini API
- [Audio Capture, Transcription and Translation](https://github.com/engalejandrovargas/Audio-capture-transcription-using-Flask-and-GPT-Turbo-translation) through Flask and GPT
- [Speech Recognition and Translation](https://github.com/engalejandrovargas/Speech-to-test-and-translation-and-google-speech-recognition)
- [WhatsApp Conversation Analyzer](https://github.com/engalejandrovargas/Whatsapp-text-analyzer)
- [Language Translator](https://github.com/engalejandrovargas/Language-translator-using-IBM-Watson) built on IBM Watson

**Web and tooling**
- [Django Boilerplate](https://github.com/engalejandrovargas/django-boilerplate) for spinning up new projects
- [Flask CI/CD](https://github.com/engalejandrovargas/flask-CD-CI) pipeline setup
- [Text Extraction Service](https://github.com/engalejandrovargas/text-extraction-flask)
- [Spotify Playlist Generator](https://github.com/engalejandrovargas/create-spotify-list)

</details>

---

## Stack

**Backend**

![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-0D1117?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-0D1117?style=flat-square&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-0D1117?style=flat-square&logo=nodedotjs&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-0D1117?style=flat-square&logo=celery&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-0D1117?style=flat-square&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-0D1117?style=flat-square&logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-0D1117?style=flat-square&logo=expo&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-0D1117?style=flat-square&logo=tailwindcss&logoColor=white)

**Machine learning and AI**

![PyTorch](https://img.shields.io/badge/PyTorch-0D1117?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-0D1117?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0D1117?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-0D1117?style=flat-square&logo=huggingface&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-0D1117?style=flat-square&logo=langchain&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-0D1117?style=flat-square&logo=opencv&logoColor=white)

**Data and infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D1117?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-0D1117?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-0D1117?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0D1117?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-0D1117?style=flat-square)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-0D1117?style=flat-square&logo=googlecloud&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0D1117?style=flat-square&logo=railway&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-0D1117?style=flat-square&logo=cloudflare&logoColor=white)

---

## Background

**Now** · Building the products above, and open to senior engineering roles across AI/ML, backend, and full-stack.

**Oak Group, Osaka** · Software and Bioinformatics Engineer, AI/ML. Built Nanopore sequencing pipelines that took genomic analysis from days to hours, trained ResNet classifiers for embryo stage detection with five-fold cross-validation, automated 1,000+ genetic screening reports annually, and deployed local LLM infrastructure with Ollama inside an isolated medical network so clinical staff could use AI without patient data ever leaving the building.

**株式会社ロボケン, Fukuoka** · AI/IT Engineer. Fine-tuned language models, and built a system that generates and distributes AI-written content across ten social platforms from a single interface.

**Freelance, since 2014** · Web development and client delivery, from WordPress and WooCommerce builds through to hosting, DNS, and API integration.

Earlier: chemical engineer and project manager, where I learned to model processes, run Monte Carlo risk analysis, and apply Lean Six Sigma before I applied any of it to software.

---

## Credentials

**Postgraduate in Machine Learning and Artificial Intelligence** · National University of Colombia, 2022<br/>
**BSc Chemical Engineering** · National University of Colombia, 2014

**PSM I** Scrum Master · **PSPO I** Product Owner · **SPS** Scaled Professional Scrum · Scrum.org

Course and certification records: [2024](https://github.com/engalejandrovargas/Certificates-2024) · [2022](https://github.com/engalejandrovargas/Certificates-2022) · [2021](https://github.com/engalejandrovargas/Certificates-2021)

---

<div align="center">

**Open to new opportunities.** The fastest way to reach me is [hello@alejandrovargas.co](mailto:hello@alejandrovargas.co).

</div>
