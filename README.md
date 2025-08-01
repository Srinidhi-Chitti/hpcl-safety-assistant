# HPCL Safety Assistant

> ✨ AI-Powered Emergency Response & Safety Management for HPCL Refineries

![Tech Stack](https://img.shields.io/badge/TechStack-React%20%7C%20Flask%20%7C%20FAISS%20%7C%20Gemini-blue?style=for-the-badge)

## 🌟 Overview

HPCL Safety Assistant is an intelligent emergency response and refinery safety platform that combines AI, routing, document search, and real-time dashboards to digitize and enhance industrial safety.

---

## ⚙️ System Architecture

* **Frontend**: React + TypeScript + Vite + Leaflet.js
* **Backend**: Flask + FAISS + PyPDF2 + NLTK + Sentence Transformers
* **AI**: Gemini API (Google Generative AI)
* **Deployment**:

  * Frontend: Vercel
  * Backend: Nutanix Linux Server with Gunicorn + NGINX

---

## 🧠 Features

### ✨ AI Chatbot

* Ask safety-related queries from uploaded PDFs
* Powered by Gemini + FAISS for context-aware answers

### 📍 Emergency Evacuation Routing

* Interactive refinery map (Leaflet.js)
* A\*/Dijkstra algorithms for route planning
* Dynamic incident overlays

### 📊 Safety Dashboard

* Live incident heatmaps and KPIs
* Summary cards for major alerts and risks

### 📄 Policy & Manual Repository

* Search and filter by document type
* Expandable summaries with context links

### 📍 Incident Reporting

* Submit via web portal
* Stored in structured NoSQL/JSON format
* View via admin dashboard

---

## 🛠️ Tech Stack

| Layer    | Technology                                        |
| -------- | ------------------------------------------------- |
| Frontend | React, Vite, TypeScript, TailwindCSS, Leaflet.js  |
| Backend  | Flask, FAISS, PyPDF2, Sentence Transformers, NLTK |
| AI Layer | Google Gemini API                                 |
| Hosting  | Nutanix (Linux + Gunicorn + NGINX), Vercel        |

---

## 🧰 Nutanix Infrastructure

* Nutanix AOS with AHV hypervisor
* RAID 1/5/6 configurations
* Clustering, failover-enabled
* Role-based access control
* Dual PSU/NIC setup

---

## 🌐 Example Use Cases

### 🔎 AI Chat

```
Q: What PPE is needed in the tank storage area?
A: FR clothing, goggles, anti-static boots required.
```

### 🛋 Routing

```
Incident: Gas leak near Tanker Bay
Suggested Route: Crude Area → Safe Assembly Point B
```

---

## ✅ Impact

* Reduces incident response times
* Centralizes all safety resources
* Works in low-network industrial settings
* Increases safety awareness and compliance

---

## 🚀 Getting Started

```bash
# Clone frontend
cd frontend && npm install && npm run dev

# Clone backend
cd backend && pip install -r requirements.txt
python app.py
```

---

## 💬 Contributions

Open to improvements, plugins for different refinery layouts, and multilingual chatbot support.

---

## 📍 License

MIT License — feel free to fork and modify for non-commercial industrial use.

---

## 🎉 Built With ❤️ For HPCL Summer Internship 2025
