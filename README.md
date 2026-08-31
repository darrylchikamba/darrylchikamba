# Darryl Chikamba

### Software & AI Engineer | Johannesburg, South Africa

I build full-stack and AI-enabled systems that turn complex data into useful, explainable decisions.

My work sits at the intersection of **software engineering, applied AI and data** — from financial intelligence and cybersecurity to real-time geospatial applications. I am particularly interested in systems where AI supports a well-engineered product rather than replacing the engineering underneath it.

My approach is simple: build the deterministic foundations first, make intelligent behaviour explainable, design for failure, and treat deployment, security and testing as part of the product.

---

## Featured Engineering Work

### FINSIQX by FINSIQ
**South African Financial Intelligence Platform**

A full-stack financial intelligence platform designed around the realities of personal finance in South Africa.

FINSIQX transforms imported banking data into structured financial intelligence through a South African financial ontology, transaction classification, anomaly detection, recurring-payment analysis, budgeting, goal tracking and personalised financial health insights.

**Engineering highlights**
- Built as a 13-screen MERN application with React, Node.js, Express and MongoDB
- Designed a South African financial ontology covering local financial behaviours and institutions
- Developed a multi-stage transaction classification pipeline using deterministic rules with an AI extension point
- Implemented weighted financial health scoring, anomaly detection and recurring-payment analysis
- Built MALI, an AI-assisted financial insight and natural-language query interface
- Added JWT authentication, ownership controls, rate limiting, NoSQL sanitisation and upload validation
- Deployed across Vercel, Render and MongoDB Atlas with GitHub Actions CI/CD

**Stack:** `JavaScript` `React` `Node.js` `Express` `MongoDB` `Recharts` `JWT` `GitHub Actions`

[View Repository](https://github.com/darrylchikamba/finsiqx) · [Live Application](https://finsiqx.vercel.app/)

---

### SENTINEL by FINSIQ
**Enterprise Cyber Intelligence Platform**

A cyber intelligence platform that converts raw security telemetry into structured, evidence-grounded investigations.

SENTINEL combines deterministic threat analysis, anomaly detection, attack-graph intelligence, retrieval-augmented generation and grounded AI reporting to support SOC-style investigation workflows.

**Engineering highlights**
- Built the backend with Python 3.12 and FastAPI
- Developed security-event analysis using pandas and scikit-learn
- Modelled attack relationships and clusters using NetworkX
- Persisted attack-graph topology and built an interactive D3.js visualisation
- Integrated a ChromaDB-backed local RAG knowledge layer
- Designed **BONA**, a provider-abstracted incident intelligence layer supporting Mock, Ollama and Gemini providers
- Added post-generation grounding controls for MITRE ATT&CK techniques, provenance and report structure
- Added South African intelligence signals for POPIA and Cybercrimes Act-related investigation context
- Implemented JWT authentication, IDOR protection, rate limiting, payload caps, strict CORS and security headers
- Containerised the backend and local intelligence stack with Docker
- Built an automated testing and GitHub Actions CI/CD pipeline
- Deployed the frontend to Vercel and API to Render

**Stack:** `Python` `FastAPI` `React` `MongoDB` `scikit-learn` `NetworkX` `D3.js` `ChromaDB` `Docker` `RAG` `GitHub Actions`

[View Repository](https://github.com/darrylchikamba/sentinel) · [Live Application](https://sentinel-rho-ruby.vercel.app/)

---

### PotSpot
**Real-Time Road Hazard Reporting Platform**

A real-time geospatial application for reporting and discovering road hazards such as potholes, flooding, accidents and road closures.

**Engineering highlights**
- Built with the MERN stack and an interactive Leaflet map
- Implemented real-time hazard updates using Socket.IO
- Added browser geolocation and OpenStreetMap reverse geocoding
- Built voting and ownership-based report management
- Added JWT/bcrypt authentication and IDOR protection
- Implemented rate limiting, security headers, NoSQL sanitisation and strict CORS
- Used MongoDB TTL expiry to automatically remove stale reports
- Deployed as a full-stack web application

**Stack:** `JavaScript` `React` `Node.js` `Express` `MongoDB` `Socket.IO` `Leaflet` `JWT`

[View Repository](https://github.com/darrylchikamba/potspot) · [Live Application](https://potspot.vercel.app/)

---

## What I Work With

**Languages**

`Python` `JavaScript` `Java` `C#` `SQL` `HTML` `CSS`

**Frontend**

`React` `Vite` `Axios` `D3.js` `Recharts` `Leaflet`

**Backend & APIs**

`FastAPI` `Node.js` `Express` `REST APIs` `JWT`

**AI & Data**

`scikit-learn` `pandas` `RAG` `Vector Embeddings` `ChromaDB` `LLM Integration` `Prompt Engineering` `Anomaly Detection`

**Databases**

`MongoDB` `MongoDB Atlas` `Mongoose` `SQL`

**Engineering & DevOps**

`Git` `GitHub` `Docker` `Docker Compose` `GitHub Actions` `CI/CD` `pytest` `Render` `Vercel`

---

## How I Think About Engineering

A few principles increasingly shape the systems I build:

**Deterministic before generative**  
AI should operate on reliable foundations. Where a result can be calculated, validated or derived deterministically, I prefer to establish that evidence before involving a generative model.

**Explainability over magic**  
An intelligent system is more useful when a user can understand why it reached a conclusion.

**Grounding over completeness**  
I'd rather return an honest empty result than a convincing fabrication.

**The backend is the source of truth**  
Interfaces should represent real application state and persisted analysis rather than reconstructing convenient approximations.

**Failure is part of the architecture**  
External APIs, AI providers and infrastructure fail. Good systems should degrade gracefully rather than collapse with them.

**Security belongs at the boundaries**  
Authentication, authorisation, input validation, ownership controls, payload limits and model-output validation are engineering concerns — not finishing touches.

---

## Certifications & Continuous Learning

My development has combined hands-on engineering with structured learning across AI, data, software development, cybersecurity and user experience.

- **Microsoft** — Azure AI Fundamentals (AI-900)
- **Google** — AI Essentials
- **Google** — Prompting Essentials
- **Google** — AI Professional
- **Google** — Data Analytics
- **Google** — Advanced Data Analytics
- **Google** — Business Intelligence
- **freeCodeCamp** — Responsive Web Design
- **freeCodeCamp** — JavaScript Algorithms and Data Structures
- **IBM SkillsBuild** — Cybersecurity
- **IBM SkillsBuild** — UX Design
- **Cisco Networking Academy** — IT Customer Support
- **Cisco Networking Academy** — Python Essentials 1 & 2
- **Mayerfield Consulting** — AI Web Design Training

---

## What I'm Building Next

### LITHOS — Decision Intelligence for Mining

My next major engineering project explores **Decision Intelligence** in the mining domain — moving beyond dashboards that describe what has happened towards systems that help operators understand **what decision to make next, and why**.

The project is being designed around three principles:

- **Decision-first architecture** — every analytical or AI capability must support a real operational decision
- **Explainability by design** — predictions and recommendations should expose the evidence and reasoning behind them
- **Cross-module intelligence** — operational, financial and risk signals should become more valuable when analysed together

LITHOS will extend the direction established through FINSIQX and SENTINEL into a more ambitious applied AI and decision-support system.

**Planned focus:** `Decision Intelligence` `Applied ML` `Explainable AI` `Data Engineering` `Full-Stack Engineering`

---

## Background

My foundation in software engineering comes from studying **Information Systems and Computer Science at the University of Cape Town**, alongside continued independent development and professional certification.

Before focusing fully on software and AI engineering, I also worked across web design and digital marketing. That experience still influences how I build: not only thinking about whether a system works technically, but whether people can understand and use it effectively.

---


> **Build the evidence first. Make the intelligence explainable.**
