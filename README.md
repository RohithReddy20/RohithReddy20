# Chimpiri Rohith

I build end-to-end systems that integrate LLMs into real-world workflows. I prefer systems that are observable, predictable, and don't fall apart under load. Currently building at NEWGEN.

[Portfolio]([https://rohith-reddy-20.vercel.app/]) • [LinkedIn](https://linkedin.com/in/chimpiri-rohith) • [Email](mailto:rohith18151821@gmail.com)

---

## Technical Stack

* **Languages:** TypeScript, Python, SQL
* **Frontend:** React, Next.js, HTML/CSS
* **Backend:** Node.js, FastAPI
* **Data:** PostgreSQL, Pinecone
* **AI / LLMs:** LangChain, LangGraph, OpenAI, RAG
* **Integrations:** Twilio, Firebase
* **Infrastructure:** Turborepo, Docker, Git, Google Cloud

---

## Featured Work

### [Supply Genie]([ADD GITHUB LINK HERE])
* **The Problem:** Resolving a delayed shipment involves messy manual coordination—checking an API, making a phone call, and updating Slack.
* **The System:** A FastAPI backend that handles supply chain exceptions by coordinating actions across external APIs, voice calls, and chat using a state-driven approach.
* **The Constraint:** Keeping system state consistent during live voice interactions while handling low-latency Twilio streams and unpredictable external API failures.
* **The Outcome:** Automates routine delay handling across APIs, voice, and chat, reducing manual coordination to only edge-case exceptions.

### Vestra Assets – Financial Processing SaaS
* **The Problem:** Extracting line items from varied bank statements and tax returns required heavy manual review because OCR is imperfect.
* **The System:** A split-pane Next.js UI pairing the original PDF with extracted data forms. A Flask backend calculates a synthetic confidence score for extractions.
* **The Constraint:** Rendering forms with 1,000+ extracted fields simultaneously crashed the browser. Fixed by implementing UI virtualization to lock the page at 60fps.
* **The Outcome:** Processing thousands of documents daily, the system entirely skips manual review for extractions scoring above 98%, routing only edge cases to human operators.

### Gen AI Platform
* **The Problem:** The Reserve Bank of India needed to search and query across a 10,000+ page secure document corpus without data ever leaving their infrastructure.
* **The System:** Led the end-to-end design and implementation of a local React and tRPC chat interface connected to a Node.js backend. The server handles document chunking, custom embeddings, and streams tokens to the client over Server-Sent Events.
* **The Constraint:** Maintaining multi-turn conversation state across massive contexts while keeping the ingestion pipeline decoupled so users could hot-swap embedding models without downtime.
* **The Outcome:** Delivered the platform in 6 weeks, securing a critical contract and enabling fast, reliable access to previously fragmented policy data for internal teams.

---

## Professional Experience

**Senior Software Engineer — NEWGEN** (Oct 2025 – Present)
* Extracted UI pieces into a decoupled React component library to standardize frontend patterns across the platform.
* Rewrote the engineering onboarding documentation and local setup scripts, cutting the time to first commit for new hires from 6 weeks to 3 weeks.

**Software Engineer** (Jan 2023 – Oct 2025)
* Built a drag-and-drop UI for composing ML pipelines using ReactFlow. Integrated TanStack Query to poll node execution status and stream live logs.
* Reduced latency on heavy API endpoints by 20% by restructuring underlying Postgres queries with more efficient aggregations and adding targeted indexes.

**Software Engineering Intern — AISENCE TECHNOLOGIES** (Aug 2022 – Dec 2022)
* Built the real-time group chat feature for a commercial real estate platform using WebSockets and Firebase.

---

## Education

**National Institute of Technology Manipur**  
B.Tech in Electronics and Communication Engineering (CGPA: 8.43) • Graduated June 2023

---

## Activity 

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=RohithReddy20&show_icons=true&hide_border=true&bg_color=0d1117&text_color=c9d1d9&icon_color=58a6ff&title_color=58a6ff)](https://github.com/RohithReddy20)
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=RohithReddy20&layout=compact&hide_border=true&bg_color=0d1117&text_color=c9d1d9&title_color=58a6ff)](https://github.com/RohithReddy20)
