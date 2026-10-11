# Raghav Bhardwaj

**Full-Stack Engineer | AI/ML | System Design**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/raghav-bhardwaj-471ab2327/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Raghav-305)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:raghav.bhardwaj.305@gmail.com)

---

## About

I'm a 3rd-year Computer Science student at **Dr. Akhilesh Das Gupta Institute of Professional Studies (GGSIPU)**, New Delhi. I build full-stack applications and AI/ML systems, from data pipelines and model training to APIs and production-style frontends.

What I focus on:
- **System design**: clean service boundaries, config-driven architectures, offline-capable deployments
- **Full-stack ownership**: database schema to UI
- **Applied AI/ML**: forecasting, NLP/OCR and computer vision, wrapped in solid software engineering
- **Hackathons**: building working end-to-end prototypes under tight deadlines

---

## 💼 Tech Stack

**Languages**
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

**Frontend**
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Shadcn UI](https://img.shields.io/badge/shadcn%2Fui-000?style=for-the-badge&logo=shadcnui&logoColor=white)

**Backend & Databases**
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)

**AI / ML**
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

**DevOps**
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white)

---

## 🏆 Featured Projects

### 1. **Freight Chartering Intelligence Platform** — AI Decision Support for Maritime Procurement
**Repository:** [github.com/Raghav-305/Freight-sih](https://github.com/Raghav-305/Freight-sih)

A decision-support system for freight chartering that turns cargo, route, vessel and laycan inputs into a Fix / Wait / Partial Cover recommendation, with a human reviewer always in the loop. Designed to run fully offline with local models and a local database.

- **Forecasting**: 7/30/60/90-day freight forecasts with P10–P90 uncertainty bands
- **Optimization**: vessel feasibility checks (draft, LOA, beam, DWT) and contract/COA allocation using a HiGHS linear-programming optimizer
- **Explainability**: SHAP contributions, plus counterfactual analysis showing the smallest change that de-risks a route or flips a decision
- **Risk engine**: market, port, weather, geopolitical, supply and contract risk dimensions
- **Anti-rigging module**: XGBoost + SHAP model for flagging anomalous or colluding tender bids
- **Audit trail**: SHA-256 hash-chained decision log with optional Merkle-root anchoring on the Polygon Amoy testnet, queued locally when offline
- **Architecture**: React + TypeScript + Vite frontend, FastAPI + SQLAlchemy backend, versioned model registry, mock mode for UI development

![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi)
![Python](https://img.shields.io/badge/python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white)

---

### 2. **Forge** — Config-Driven Runtime Engine
**Repository:** [github.com/Raghav-305/forge](https://github.com/Raghav-305/forge)

A runtime engine that renders UIs dynamically from JSON configurations, so new apps can be defined without changing code.

- TanStack Start (React 19 + Vite 7), TypeScript strict mode, Tailwind CSS v4, Shadcn UI
- Component registry pattern with pluggable renderers
- Dynamic form, table and card rendering with error boundaries
- CSV import with smart field mapping

![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=flat-square&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=flat-square&logo=tailwind-css&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=Cloudflare&logoColor=white)

---

### 3. **LexiScan Auto** — Legal Document Processor
**Repository:** [github.com/Raghav-305/lexiscan](https://github.com/Raghav-305/lexiscan)

Automated legal document analysis using a hybrid OCR pipeline and a custom-trained NER model.

- FastAPI backend with a modular service layer
- OCR fallback chain: PyPDF2 → Tesseract → preprocessing
- Custom spaCy NER model plus regex validation for dates, parties, amounts and termination clauses
- React + Vite frontend with interactive highlighting and JSON export
- Dockerized for deployment

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB)
![Python](https://img.shields.io/badge/python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white)

---

### 4. **NagrikAI** — Government Services CRM Platform
**Repository:** [github.com/Raghav-305/NagrikAi](https://github.com/Raghav-305/NagrikAi)

A citizen complaint management platform with AI-assisted triage and analytics for government departments.

- Citizen portal with complaint submission and image uploads
- AI pipeline for automatic classification, sentiment scoring and urgency assessment
- Admin dashboard with KPIs, trends and department performance
- Leaflet map with urgency-coded markers; Chart.js analytics

![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=flat-square&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=flat-square&logo=tailwind-css&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi)

---

### 5. **VeriLens** — Deepfake Detection System
**Repository:** [github.com/Raghav-305/hackmol](https://github.com/Raghav-305/hackmol)

A deepfake detection tool combining perceptual hashing with a TensorFlow classifier.

- Next.js frontend for image analysis
- Perceptual hashing for fast similarity matching
- TensorFlow neural network for deepfake classification
- Batch processing and Firebase deployment

![Next JS](https://img.shields.io/badge/Next-black?style=flat-square&logo=next.js&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=flat-square&logo=TensorFlow&logoColor=white)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=flat-square&logo=firebase)
![Python](https://img.shields.io/badge/python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)

---

## 🎓 Education

**B.Tech in Computer Science and Engineering**  
Dr. Akhilesh Das Gupta Institute of Professional Studies (GGSIPU), New Delhi  
Currently in 3rd Year

---

## 📊 GitHub Statistics

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Raghav-305&theme=dark&hide_border=true&include_all_commits=true&count_private=true&show_icons=true&title_color=FFFFFF&text_color=FFFFFF&bg_color=0D1117)

![GitHub Streak](https://nirzak-streak-stats.vercel.app/?user=Raghav-305&theme=dark&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Raghav-305&theme=dark&hide_border=true&include_all_commits=true&count_private=true&layout=compact)

---

## 🎯 What I'm Looking For

- **Full-stack engineering** internships and roles at product-focused teams
- **AI/ML engineering** internships, especially forecasting, NLP and computer vision
- **System design** problems with real technical depth
- **Open-source** contributions in ML tooling and web frameworks

---

## 📬 Get In Touch

**Email:** [raghav.bhardwaj.305@gmail.com](mailto:raghav.bhardwaj.305@gmail.com)  
**LinkedIn:** [linkedin.com/in/raghav-bhardwaj-471ab2327](https://linkedin.com/in/raghav-bhardwaj-471ab2327/)  
**GitHub:** [github.com/Raghav-305](https://github.com/Raghav-305)

---

*Last updated: October 2026*
