# 🚀 SerpAI — Next-Gen AI SEO Analysis & Keyword Tracker

<div align="center">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=Vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Google_Gemini-8E75C2?style=for-the-badge&logo=google-gemini&logoColor=white" alt="Gemini API" />
</div>

---

**SerpAI** is an extraordinary, enterprise-grade AI-powered SEO analysis and keyword tracking ecosystem. Built with a robust full-stack architecture (React, Node.js, Express, and MongoDB), SerpAI harnesses the cognitive power of advanced LLMs (Google Gemini API) and high-speed headless browser scraping to simulate genuine user experiences, deliver deep SEO audits, track organic keyword positions daily, and generate instantly actionable ranking roadmaps.

This isn't just an audit tool; it's a **predictive growth engine** designed to scale with your digital presence.

---

## 📸 App Interface & Visual Walkthrough

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <b>1. Welcome & Landing Portal</b><br/>
      <img src="https://github.com/deepakstwt/SerpAI/raw/main/client/public/screenshot-1.jpeg" width="100%" alt="SerpAI Landing Page" />
      <p>Clean, high-converting homepage demonstrating core capabilities.</p>
    </td>
    <td width="50%" align="center">
      <b>2. Secure Access Gateway</b><br/>
      <img src="https://github.com/deepakstwt/SerpAI/raw/main/client/public/screenshot-2.jpeg" width="100%" alt="SerpAI Secure Auth" />
      <p>Smooth, secure JWT-based user authentication screen.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <b>3. Dynamic Analytical Dashboard</b><br/>
      <img src="https://github.com/deepakstwt/SerpAI/raw/main/client/public/screenshot-3.jpeg" width="100%" alt="SerpAI Dashboard" />
      <p>Aggregated overview of scanned websites, dynamic scores, and tracking alerts.</p>
    </td>
    <td width="50%" align="center">
      <b>4. Deep SEO Domain Auditor</b><br/>
      <img src="https://github.com/deepakstwt/SerpAI/raw/main/client/public/screenshot-4.jpeg" width="100%" alt="SerpAI Domain Auditor" />
      <p>Trigger instant audits by typing the domain and analyzing live metadata.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <b>5. Auditing Score Gauges</b><br/>
      <img src="https://github.com/deepakstwt/SerpAI/raw/main/client/public/screenshot-5.jpeg" width="100%" alt="SerpAI Score Gauges" />
      <p>Interactive score meters tracking performance, SEO, best practices, and mobile UX.</p>
    </td>
    <td width="50%" align="center">
      <b>6. AI Actionable Diagnostics</b><br/>
      <img src="https://github.com/deepakstwt/SerpAI/raw/main/client/public/screenshot-6.jpeg" width="100%" alt="SerpAI AI Diagnostics" />
      <p>Google Gemini categorizes site issues (Critical to Low) with clear inline fixes.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <b>7. Keyword Rank Monitor</b><br/>
      <img src="https://github.com/deepakstwt/SerpAI/raw/main/client/public/screenshot-7.jpeg" width="100%" alt="SerpAI Keyword Monitor" />
      <p>Active dashboard tracking position movements for targeted search keywords.</p>
    </td>
    <td width="50%" align="center">
      <b>8. Historic Performance Analytics</b><br/>
      <img src="https://github.com/deepakstwt/SerpAI/raw/main/client/public/screenshot-8.jpeg" width="100%" alt="SerpAI Rank History" />
      <p>Historical chart illustrating ranking growth and volatility trends over time.</p>
    </td>
  </tr>
</table>

---

## ✨ Key Features & Architectural Highlights

### 🔍 Autonomous Scraper & Performance Analyzer
*   **Deep Crawler:** Emulates genuine browser sessions to bypass bot-detection, extracting raw HTML, metadata, headings hierarchy, and internal/external link networks.
*   **Web Vitals & Performance Scores:** Instantly computes structural load benchmarks, mobile accessibility, and best practices.

### 🧠 Google Gemini-Driven SEO Auditing
*   **Semantic Analysis:** Evaluates content depth, keyword stuffing, keyword intent mapping, and structural accessibility.
*   **AI Diagnostics:** Automatically creates detailed issue reports (Critical, High, Medium, Low) paired with precise inline instructions to improve rank.

### 📈 Precision Keyword Rank History Tracker
*   **Live Position Crawling:** Actively checks and registers Google SERPs rankings for specified target domains and targeted keywords.
*   **Historic Progress Visualization:** Visualizes historical ranking trajectories using clean, interactive analytics charts.

### 🕒 Automated Background Cron Scheduler
*   **Daily Sync Engine:** Runs automated background processes daily to track rank shifts, alert you to competitive volatility, and log long-term organic growth.

---

## 🛠️ Tech Stack & Systems

| Layer | Technology | Purpose |
| :--- | :--- | :--- |
| **Frontend** | React 19, Vite, Tailwind CSS 4, React Router 7 | Immersive, fluid, glassmorphic client interface. |
| **Backend** | Node.js, Express | Secure, asynchronous RESTful API Gateway. |
| **Database** | MongoDB, Mongoose | Schema-driven document storage for historical rankings and audits. |
| **AI Engine** | Google Gemini API (via `@google/generative-ai`) | Advanced semantic content gap analysis & diagnostic reports. |
| **Scraper** | Axios & Cheerio Engine | Reliable, lightweight DOM parsing and element extraction. |
| **Automation** | Node-Cron | Periodic background data pipelines and automated rank-checks. |

---

## 📂 Project Architecture

```
SerpAI/
├── client/          # Vite + React Frontend Application
│   ├── src/
│   │   ├── components/  # Reusable UI Elements (Charts, Gauges, protected routes)
│   │   ├── context/     # Global state engines (Auth, Theme)
│   │   ├── pages/       # Dashboard, Keyword Tracker, Auditor, Reports
│   │   └── App.tsx      # Core router and layout tree
│   └── public/          # Static browser assets
├── server/          # Express.js REST API
│   ├── config/          # Database connection pool configurations
│   ├── controllers/     # API handler logic
│   ├── routes/          # Express route definitions
│   ├── models/          # Mongoose Schemas (User, Analysis, KeywordTracking)
│   ├── services/        # AI engines, scraper logic, Google ranking services
│   ├── cron/            # Scheduled background processes
│   └── server.js        # Main system entry point
```

---

## 🚀 Live Setup & Quick Start

### 📋 Prerequisites
Make sure you have the following installed locally:
*   [Node.js](https://nodejs.org/) (v18.x or higher)
*   [MongoDB](https://www.mongodb.com/) (local community instance or Atlas cloud cluster)
*   Google Gemini API Key

---

### ⚙️ Step-by-Step Installation

#### 1. Clone & Enter the Project
```bash
git clone https://github.com/deepakstwt/SerpAI.git
cd SerpAI
```

#### 2. Server Configuration
Navigate to the `server/` directory and configure the environment variables:
```bash
cd server
npm install
```
Create a `.env` file in the `server` folder with the following credentials:
```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/serpai  # or your Atlas URI
JWT_SECRET=your_super_secure_jwt_secret
GEMINI_API_KEY=your_google_gemini_api_key
CLIENT_URL=http://localhost:5173
```

Start the API server in development mode:
```bash
npm run dev # or node server.js
```

#### 3. Client Configuration
Open a new terminal session, navigate to the `client/` directory, and setup the UI:
```bash
cd client
npm install
```
Create a `.env` file in the `client` folder:
```env
VITE_API_URL=http://localhost:5000
```

Start the Vite development web server:
```bash
npm run dev
```
Open your browser to `http://localhost:5173` to explore SerpAI!

---

## 🔮 Roadmap: Future Horizons & Innovation Scope

SerpAI is built to continuously adapt and lead. The next stages of development include pioneering features to keep your website at the forefront of search engines:

*   **🕵️‍♂️ Auto-AI Competitor Hijack Agent:** Autonomous agents that monitor high-ranking competitor landing pages, analyze semantic keywords, and instantly generate strategic content plans.
*   **🛠️ Autonomous GSC Auto-Optimizer:** Seamlessly integrates with the Google Search Console API to identify queries with high impressions but low click-through rates, and automatically suggests/updates website meta headers.
*   **📈 Predictive Volatility Forecasting:** Machine learning models that analyze keyword ranking fluctuations over time to forecast potential algorithmic search shifts before they impact your site.
*   **🌐 Multi-Engine SERP Sync:** Expanding the deep crawl architecture to support multi-platform rank checks across Bing, DuckDuckGo, and Baidu.

---

## 🤝 Contributing

We welcome active contributions to keep SerpAI state-of-the-art! For workflow guidelines, pull requests, and standard procedures, check out our [Contributing Guidelines](client/CONTRIBUTING.md).

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](client/LICENSE.md) file for details.
