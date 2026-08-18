<div align="center">

# 👋 Hi, I'm Priyanshu Sharma

### Backend Engineering · AI Systems · Data & Geospatial Computing

I build software systems around **backend engineering, AI, databases, real-time data, and geospatial computing**.

I enjoy taking ideas from:

**Problem → Architecture → Backend → Intelligence → Integration → Working Product**

[![GitHub](https://img.shields.io/badge/GitHub-cs1m2414238-181717?style=for-the-badge\&logo=github)](https://github.com/cs1m2414238)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Priyanshu_Sharma-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/priyanshu-sharma-b85b8a335/)

</div>

---

# 🚀 About Me

I'm a Computer Science student interested in building systems that combine:

```text
Backend Engineering
        +
Database Systems
        +
AI & Intelligent Agents
        +
Real-Time Processing
        +
Data & Geospatial Computing
```

My main areas of interest are:

* ☕ **Java & Spring Boot**
* 🧠 **AI agents and intelligent applications**
* 🗄️ **PostgreSQL, SQL & database design**
* ⚡ **Real-time and event-driven systems**
* 🌍 **Geospatial computing & spatial analytics**
* 🏗️ **System design & backend architecture**
* 📊 **Data analytics & visualization**
* ☁️ **Cloud, containers & deployment**

I prefer projects where software has to process **real-world data**, enforce constraints, make useful decisions, and coordinate multiple services.

---

# 🧩 Engineering Focus

## ⚙️ Backend Engineering

I enjoy designing applications with clear separation between APIs, business logic, persistence, and external services.

```text
Client
  ↓
REST API
  ↓
Controller
  ↓
Service Layer
  ↓
Business Logic
  ↓
Repository
  ↓
Database
```

Working with:

* Java
* Spring Boot
* REST APIs
* Authentication & authorization
* Service-layer architecture
* PostgreSQL
* MySQL
* Database migrations
* API integrations
* Real-time communication

---

## 🧠 AI & Agent Systems

I'm interested in applications where AI is integrated into an actual software system instead of existing as an isolated model.

```mermaid
flowchart LR
    A[User / Application] --> B[Backend API]
    B --> C[Context & Data Retrieval]
    C --> D[AI Agent / Decision Engine]
    D --> E{Constraints Valid?}

    E -->|Yes| F[Recommendation / Action]
    E -->|No| G[Replan / Alternative]

    G --> D
    F --> H[Application Services]
    H --> I[(Database)]
    H --> J[Monitoring / UI]
```

Areas I'm exploring:

* AI agent architecture
* LLM integration
* Context-aware decision making
* Tool-using agents
* Retrieval and memory
* Constraint-based planning
* AI-assisted backend workflows
* Evaluation of agent decisions

---

## 🗄️ Data & Database Systems

I enjoy working on the part of software that turns raw information into reliable application state.

Areas I'm developing:

* Relational database design
* PostgreSQL
* MySQL
* SQL querying
* Schema normalization
* Indexing
* Query optimization
* Spatial databases
* PostGIS
* Data pipelines
* Analytics-oriented data models

---

# 🔥 Featured Projects

## ⚡ Vidyut — AI-Powered EV Charging Platform

A full-stack EV charging and journey-planning system that combines **backend services, routing, constraints, charging infrastructure, and AI-assisted decisions**.

### Core Flow

```mermaid
flowchart TD
    A[User Journey Request] --> B[Spring Boot Backend]

    B --> C[Vehicle & Battery Constraints]
    B --> D[Route Engine]
    B --> E[Charging Station Data]

    C --> F[Journey Planner]
    D --> F
    E --> F

    F --> G[AI Decision Layer]
    G --> H[Charging Plan]

    H --> I[User Approval / Autopilot]
    I --> J[Booking / Charging Services]
```

### Features

* Battery-aware journey planning
* Charger discovery
* Connector compatibility
* Cost-aware charging decisions
* Time-based optimization
* Balanced journey optimization
* Minimum battery reserve
* Charging-budget constraints
* Dynamic rerouting
* Charging session management
* Charging-company workflows
* Property-owner / host workflows
* AI-assisted journey planning

### Backend Architecture

```text
Web / Mobile Client
        ↓
Spring Boot REST API
        ↓
Service Layer
        ↓
Journey + Charging Logic
        ↓
Routing / AI Components
        ↓
PostgreSQL
```

### Tech

`Java` `Spring Boot` `PostgreSQL` `React` `React Native` `OSRM` `Docker` `AI Agents`

🔗 [Explore Vidyut](https://github.com/cs1m2414238/vidyutEV-1.0)

---

## 🌍 Geospatial AI for Urban Heat Mitigation

A geospatial AI framework for identifying urban heat hotspots and evaluating possible cooling interventions using satellite, climate, and spatial datasets.

### Data Pipeline

```mermaid
flowchart LR
    A[Landsat 8] --> D[Google Earth Engine]
    B[Sentinel-2] --> D
    C[ERA5] --> D

    D --> E[Preprocessing]
    E --> F[Spatial Feature Engineering]
    F --> G[Machine Learning]
    G --> H[Heat Hotspot Prediction]
    H --> I[Mitigation Analysis]
```

### Areas Covered

* Satellite-data processing
* Urban heat hotspot detection
* Geospatial feature engineering
* Machine-learning prediction
* Cooling-intervention analysis
* Spatial databases
* Backend integration

### Tech

`Python` `Google Earth Engine` `Landsat 8` `Sentinel-2` `ERA5` `XGBoost` `PostGIS` `Spring Boot`

---

## 🪖 Military Logistics & Fleet Readiness Command Center

A data-oriented application focused on **fleet readiness, logistics monitoring, reporting, and operational analytics**.

### Areas Explored

* Fleet-readiness metrics
* Logistics data organization
* Operational dashboards
* Analytics
* Reporting
* Data visualization

🔗 [View Project](https://github.com/cs1m2414238/Military-Logistics-Fleet-Readiness-Command-Center)

---

## 📝 Text-Pro

A Java-based text-processing project focused on efficient document processing, parsing, algorithms, and software design.

### Focus

* Java
* Object-oriented design
* Efficient parsing
* Text processing
* Data structures
* Performance improvement

🔗 [View Text-Pro](https://github.com/cs1m2414238/Text-Pro)

---

# 🏗️ How I Think About Systems

```mermaid
flowchart TD
    A[Client / User] --> B[API Layer]
    B --> C[Business Logic]

    C --> D[(Database)]
    C --> E[AI / Decision Engine]
    C --> F[External Services]

    D --> G[Analytics / Monitoring]
    E --> G
    F --> G
```

I try to keep clear boundaries between:

* API layer
* domain logic
* persistence
* AI components
* external integrations
* analytics
* infrastructure

---

# 🛠️ Tech Stack

## Languages

<p>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
</p>

## Backend

<p>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/REST_APIs-005571?style=for-the-badge"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
</p>

## Databases

<p>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/PostGIS-336791?style=for-the-badge"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
</p>

## Frontend

<p>
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
</p>

## AI & Data

<p>
<img src="https://img.shields.io/badge/AI_Agents-8A2BE2?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Machine_Learning-FF6F00?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Geospatial_AI-6A5ACD?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white"/>
</p>

## Tools & Infrastructure

<p>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white"/>
<img src="https://img.shields.io/badge/OSRM-Routing-46A758?style=for-the-badge"/>
</p>

---

# 🔭 Currently Exploring

```java
while (learning) {

    understandProblem();

    designArchitecture();

    build();

    test();

    measure();

    improve();
}
```

Current focus:

* Advanced Java & Spring Boot
* Backend architecture
* System design
* Distributed systems
* PostgreSQL & database performance
* AI agent orchestration
* LLM-powered applications
* Geospatial machine learning
* Data analytics
* DevOps & deployment

---

# 📊 GitHub Activity

<div align="center">

<img height="175"
src="https://github-readme-stats.vercel.app/api?username=cs1m2414238&show_icons=true&hide_border=true&rank_icon=github&include_all_commits=true"
/>

<img height="175"
src="https://github-readme-stats.vercel.app/api/top-langs/?username=cs1m2414238&layout=compact&hide_border=true&langs_count=8"
/>

</div>

---

# 📈 Contribution Activity

<div align="center">

<img
src="https://github-readme-activity-graph.vercel.app/graph?username=cs1m2414238&hide_border=true&area=true"
/>

</div>

---

# 🎯 What I Want to Build

I'm particularly interested in projects where several engineering areas come together:

```text
Backend Engineering
        +
AI
        +
Databases
        +
Real-Time Data
        +
Analytics
        +
Infrastructure
```

Areas that interest me include:

* AI-powered applications
* Backend platforms
* Decision-support systems
* Geospatial applications
* Data-intensive systems
* Real-time applications
* Developer tools
* Infrastructure-focused software

> **I want to build software that understands real-world information, makes useful decisions, and turns those decisions into reliable applications.**

---

# 💡 Engineering Philosophy

```text
Don't just make it run.
Understand why it works.

Don't just add features.
Design the system.

Don't use technology because it's popular.
Know why it belongs there.

Build → Measure → Learn → Improve.
```

---

# 🤝 Open To

* 💻 Software Engineering Internships
* ☕ Backend Engineering
* 🧠 AI / Agent Systems
* 🔬 Research Internships
* 🌍 Geospatial Computing
* 📊 Data & Analytics
* 🛠️ Open Source
* 🏆 Hackathons

---

<div align="center">

# 🌐 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Priyanshu_Sharma-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/priyanshu-sharma-b85b8a335/)

[![GitHub](https://img.shields.io/badge/GitHub-cs1m2414238-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/cs1m2414238)

---

### `Design thoughtfully. Build deeply. Keep improving.`

⭐ Explore my repositories or reach out if you'd like to collaborate.

</div>
