# 📂 My Projects

## 👨‍💻 About Me

I'm **Rajakone Christan**, currently pursuing my undergraduate studies at **Uva Wellasa University**.
I have a **keen interest in AI, infrastructure engineering, serverless architectures, and agentic systems**, and am actively building my career in these fields.

🎓 **Cumulative GPA**: `3.72`

---

## 💼 Professional Projects

---

### 🧩 [Sparengine](https://sparengine.com/) (Lead Engineer – Product Development) | [Ascentis Technologies](https://www.ascentistechnologies.com/)

**Description:**
**Sparengine** is an intelligent aviation document analysis system that transforms thousands of pages of unstructured aircraft asset records (maintenance logs, certificates, inspection reports) into structured, queryable intelligence. The system ingests large aviation asset dossiers, extracts structured data, generates multi-level embeddings, identifies asset identity, maintenance events, regulatory compliance indicators, and enables intelligent asset-level analysis using agentic workflows.

A production-grade startup product where I **architected and engineered the entire system from scratch**, and now **lead and oversee 3 engineers**.

#### ⚙️ Stack & Tools

- **Frontend:** Next.js, Tailwind
- **Backend:** Node.js, Express, Supabase, LangGraph, LangChain, Gemini, AWS SDK
- **Infrastructure:** AWS (Lambda, CloudWatch, IAM, Step Functions, EC2, ECS, S3), Docker
- **Networking:** Cloudflare Tunneling

#### 👨‍💻 Contributions

- End-to-end architecture and core engineering
- DevOps + deployment automation
- Scalability and security
- Technical leadership, code reviews, mentoring
- **Currently working on:** Using **LangGraph** to implement **multi-agent systems** that work together as a team to deeply analyze and research documents, providing robust information and insights on aviation asset dossiers

---

### 📞 [DGloss – AI-Powered Call Center Platform](https://softsora.com) (Softsora)

**Description:**
Contributed to the development of an AI-powered call center platform that automates outbound calls to customers, conducts natural language conversations, and seamlessly transfers to human agents when required.

#### ⚙️ Stack & Tools

- **Frontend:** Next.js, Ant Design, Zustand
- **Backend:** Express.js, Sequelize ORM
- **Infrastructure:** AWS Connect, Asterisk PBX, PostgreSQL, Docker
- **Architecture:** NX monorepo workspace
- **DevOps:** Azure Boards, Git/GitHub, ESLint, Husky, Conventional Commits

#### 👨‍💻 Contributions

- Designed and implemented user interfaces for operators and administrators, including real-time management of operator availability status (seated/available or away)
- Developed core backend APIs and business logic for call counting, per-agent/per-campaign call limit enforcement, and related validation checks
- Built responsive, paginated data tables in the frontend with corresponding backend API support for server-side pagination and filtering
- Created comprehensive infrastructure and system architecture diagrams using Draw.io
- Applied clean layered architecture (Models → DAOs → Services → Controllers → Routes)
- Incorporated Japanese design principles focused on simplicity, clarity, minimalism, and intuitive user flows
- Collaborated closely with tech leads, senior developers, and cross-functional team members through code reviews and pair programming sessions

#### ✅ Highlights

- Gained hands-on exposure working with AWS Connect for contact center orchestration and Asterisk PBX for telephony
- Followed DevOps best practices including sprint planning, task tracking, and code quality enforcement
- Improved technical skills, problem-solving abilities, and code craftsmanship through detailed code reviews

---

### 🎫 Insurance Company Event Management Platform (Softsora)

**Description:**
Contributed to the development of a web platform for a Japanese insurance company, enabling the hosting of company events where attendees could register, pay participation fees online, and receive personalized QR code access cards.

#### ⚙️ Stack & Tools

- **Full-Stack:** Frontend design & implementation, Backend logic
- **Payment:** Stripe payment gateway
- **Infrastructure:** Docker (containerized deployment with database services)
- **Features:** QR code generation and scanning for secure event check-in

#### 👨‍💻 Contributions

- Implemented QR code generation for access cards and integrated QR code scanning functionality for secure event check-in
- Integrated Stripe payment gateway to handle secure online fee payments and transaction processing
- Applied Japanese design principles — emphasizing minimalism, clarity, harmony, and intuitive user experience — throughout the interface and user flows
- Worked under the direct supervision of the CEO, receiving guidance on project direction, priorities, and quality standards
- Practiced pair programming sessions with a fellow intern to collaboratively solve implementation challenges, review code, and accelerate feature delivery

#### ✅ Highlights

- Gained hands-on experience with full-stack development and containerized deployment
- Delivered secure event registration and payment processing system
- Enhanced collaboration and technical skills through pair programming

---

### 📸 [Photos Ventoux](https://photos-ventouxsummit.fr) (Digital Photo Commerce Platform) | [Ascentis Technologies](https://www.ascentistechnologies.com/)

**Description:**
Led development of the full-stack photo platform at [photos-ventouxsummit.fr](https://photos-ventouxsummit.fr), using **Next.js on both frontend and backend** to unify codebase and simplify deployments. A full digital commerce system where users select photos, convert them into products, and purchase digital/print versions with **dynamic pricing**.

#### ⚙️ Stack

- **Full-Stack:** Next.js (Frontend & Backend)
- Tailwind CSS
- Supabase (DB/Auth, S3 for thumbnails)
- AWS S3 (HD asset storage)
- Stripe payment integration
- OpenAI API (image processing)
- Earlier phase: custom PrestaShop modules (`galleryquest`, `customphotopricing`)

#### 👨‍💻 Contributions

- **Unified codebase** using Next.js for both frontend and backend, simplifying deployments
- Implemented **multi-step gallery filter and rendering engine**, accelerating page loads by **40%** and improving end-user search precision
- Quantity-based dynamic pricing logic
- Guest checkout design
- Migration from PrestaShop → full Next.js platform
- **High-throughput media pipeline:**
  - Handles photographers uploading tens of gigabytes of ZIP archives
  - Automatically extracts images and generates low-res variants for OpenAI API processing
  - Creates thumbnail versions in Supabase S3 bucket
  - Uploads HD assets to AWS S3
  - Optimized end-to-end throughput to process each image bundle in **under one second**

---

## 🔬 Research Projects

---

### 🧪 [Research Review: AVCCT-HCD (Harmful Content Detection)](https://github.com/christancone/AVCCT-HCD)

**Description:**
Multi-label classification of harmful content in short videos: **Adult, Suicide, Violent, Neutral**, with a safety-first constraint (**Recall ≥90% for Suicide & Violent**).

#### 🔬 Core Innovation

**Two-stage cascaded bi-directional cross-attention** for progressive audio-video fusion + modality-specific refinement before fusion.

#### 🏗️ Architecture

1. Frozen feature extraction: **VideoMAE + AST** (768-d each)
2. Intra-modality refiners (2-layer transformers)
3. Cascaded cross-attention (2 stages)
4. Masked mean pooling + concat (1536-d) + MLP classifier

#### ⚙️ Tech Stack

- PyTorch, PyTorch Lightning, Transformers
- OpenCV, Decord, Librosa, FFmpeg
- sklearn, NumPy, Pandas
- Matplotlib, Seaborn, Plotly, TensorBoard
- Docker, ONNX, TorchScript

#### ✅ Highlights

- 5-fold CV with stratification
- Wilcoxon + Bonferroni tests
- Baseline comparisons + ablations
- Production-ready, modular, reproducible pipeline

---

### 🌐 Valerie Bourceaud Website + Headless CMS | [Ascentis Technologies](https://www.ascentistechnologies.com/)

**Website:** [www.valeriebourceaud.fr](http://www.valeriebourceaud.fr)
**Description:**
A modern website built using Next.js with a custom Notion-based CMS setup.

#### ⚙️ Stack

- Next.js
- Notion as CMS
- Upstash Redis caching
- Tailwind

#### 🔧 Package Used

- Published npm package: [https://www.npmjs.com/package/notion-upstash-cms](https://www.npmjs.com/package/notion-upstash-cms)

---

### ✉️ [Email Signature Generator](https://www.simpleemailsignature.com/) | [Ascentis Technologies](https://www.ascentistechnologies.com/)

**Description:**
Designed and launched the signature builder at [simpleemailsignature.com](https://www.simpleemailsignature.com/), crafting **modular React components** that slashed user setup time by **80%** and standardized branding across email clients.

> **Note:** Because of low traffic, site is currently halted in order to save resources.

#### ⚙️ Technologies Used

Next.js React TypeScript Tailwind CSS Supabase

#### 👨‍💻 Role

- Built **modular React components** & live signature preview.
- Engineered **cloud-powered storage** and **live-sync features** so signature updates propagate instantly to all users' devices.
- Integrated Supabase for **user data storage** and **profile image uploads**.
- Mobile-friendly UI with optimized UX.

#### ✅ Outcome

- **80% reduction** in user setup time through modular component architecture.
- Standardized branding across email clients.
- **Instant synchronization** across all user devices via cloud-powered live-sync.
- Offered a **free**, **user-friendly** tool with no sign-up.
🌐 [Live Demo](https://www.simpleemailsignature.com/)

---

### 🚚 [RouteLead](https://github.com/christancone/routelead) (Logistics Bidding Platform)

**Description:**
A mobile-first marketplace connecting drivers returning empty with customers who need to ship parcels. Drivers can bid and customers can choose offers.

#### ⚙️ Stack

- **Frontend:** React Native
- **Backend:** Spring Boot (Gradle)
- **Auth/Data:** Supabase
- Docker support

📊 [Pitch Deck](https://www.linkedin.com/posts/christancone_routelead-activity-7396482422294556672-O2KT?utm_source=share&utm_medium=member_desktop&rcm=ACoAADMqL84B2CFTpjWbGgL2hwwNJ0TRBOVY8ho) | 🎬 [Demo](https://lnkd.in/gZVBy8Dr)

---

## 📚 Academic and Self Interest Projects

---

### 📈 Stock API (FastAPI Multi-Source Financial Data Platform)

**Description:**
A robust financial API providing real-time stock data from multiple sources including **MarketWatch, Yahoo Finance, and CSE** with a modular domain-driven architecture.

#### ⚙️ Stack

- FastAPI, Python
- Docker / Compose
- Bootstrap UI + charts
- Provider + Factory design patterns
- **Web Scraping:** Selenium, BeautifulSoup (for CSE data)

#### ✅ Features

- NYSE + Colombo Stock Exchange support
- Historical charts + CSV export
- Company announcements & financial reports (CSE)
- Clean modular architecture with strong error handling

#### 🔧 Technical Note

Since CSE (Colombo Stock Exchange) lacks official APIs for programmatic access, I developed an **unofficial web scraping solution** using **Selenium** and **BeautifulSoup** packages. This solution enables automated data retrieval for my personal investment decisions, providing real-time access to CSE market data that would otherwise require manual monitoring.

---

### 📦 [NPM Package: notion-upstash-cms](https://www.npmjs.com/package/notion-upstash-cms)

**Description:**
A reusable package to use **Notion as a CMS** with **Upstash Redis caching** for fast content delivery in Next.js projects.

#### ⚙️ Stack

- Node.js / TypeScript
- Notion API
- Upstash Redis

---

### 🍼 [TinyToes - Childcare Management System](https://github.com/christancone/project1)

**Description:**
A comprehensive web app designed to **revolutionize childcare management**, offering daycare businesses tools to efficiently manage operations and provide parents real-time updates.

#### ⚙️ Technologies Used

React Vite Material UI Tailwind CSS

#### 👨‍💻 Role

- Developed key features: employee management, real-time updates, secure communication.

#### ✅ Outcome

- Improved daycare management with **real-time child status updates**, **efficient billing**, and **secure communication** between parents and caregivers.   

▶️ [Watch Demo](https://www.youtube.com/watch?v=hWbEa2_tLuM)

---

### 💰 [BestBid Auction Site](https://github.com/christancone/AuctionSite)

**Description:**
A real-time **online auction** platform where auction hosts can create listings and users place bids live.

#### ⚙️ Technologies Used

Django React Tailwind CSS PostgreSQL

#### 👨‍💻 Role

- Full-stack development (Frontend & Backend).
- Implemented **real-time bidding**, user authentication, auction management.

#### ✅ Outcome

- Delivered a fully functional, **real-time auction platform** ensuring transparency and fairness.
▶️ [Watch Demo](https://www.youtube.com/watch?v=pCmhMT8fOmU)

---

### 📚 [EpicReads - Bookstore Management System](https://github.com/christancone/EpicReads)

**Description:**
A **comprehensive bookstore system** managing inventory, customer orders, and sales.

#### ⚙️ Technologies Used

Java JSP MySQL HTML5 CSS3 Bootstrap

#### 👨‍💻 Role

- Designed database schema.
- Implemented user authentication, order & inventory management.
- Developed responsive UI with **Bootstrap**.

#### ✅ Outcome

- Streamlined bookstore admin tasks.
- Delivered a **seamless shopping experience** for users.
▶️ [Watch Demo](https://www.youtube.com/watch?v=59v-Nk8jbLw)

---

### 💊 [Renew - Pharmacy Inventory Management System](https://github.com/christancone/Renew)

**Description:**
A web-based app designed for **pharmaceutical inventory management**, with Admin & Pharmacist roles.

#### ⚙️ Technologies Used

HTML5 CSS3 JavaScript PHP MySQL

#### 👨‍💻 Role

- Developed inventory control & low-stock notifications.
- Created Admin & Pharmacist dashboards.

#### ✅ Outcome

- Provided **real-time stock tracking**.
- Enhanced timely restocking of items.
▶️ [Watch Demo](https://www.youtube.com/watch?v=JnBmRnVRdno)

---

### 🌐 [DomainLK - A Minimalistic Redesign](https://github.com/christancone/domainTest)

**Description:**
A minimalistic **SEO-focused redesign** of [domains.lk](https://www.domains.lk/), with mobile-first UI.

#### ⚙️ Technologies Used

React.js Tailwind CSS

#### 👨‍💻 Role

- Rebuilt website from scratch (no 3rd party libraries).
- Focused on **UX** and **accessibility**.

#### ✅ Outcome

- Boosted **SEO** and mobile compatibility.
🌐 [Live Demo](https://domain-test-vii5.vercel.app/)

---

## 📄 [Download My Resume](https://github.com/christancone/myProjects/blob/main/resume.pdf)

---

