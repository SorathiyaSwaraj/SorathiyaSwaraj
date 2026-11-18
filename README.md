<h1 align="center">Hi 👋, I'm Swaraj Sorathiya</h1>
<h3 align="center">Software Engineer · GenAI, RAG & AI Agents</h3>

I build LLM systems and measure whether they work.

I'm a Software Engineer at **Vayana Network**, working on a production lending platform (microservices, NATS, complex SQL and stored procedures for financial reports). Outside work, I build Generative AI systems end to end: agents, RAG pipelines and the evaluation harnesses that test them.

🎯 Looking for **AI Engineer** roles building agents, RAG and LLM applications.

### 🚀 Featured projects

**[Document Extraction Agent](https://github.com/SorathiyaSwaraj/doc_extract_agent)**: GenAI entity extraction for GST invoices
- Extracts validated entities (GSTINs, line items, taxes, totals) from GST invoice PDFs using LLM APIs, prompt engineering and schema-constrained structured outputs.
- Evaluation harness on a 300-invoice benchmark: vision-LLM extraction reached **0.87 micro-F1** on degraded scans, against 0.44 for OCR plus a text LLM.
- Rule validation and an LLM self-repair loop flagged **29 of 30** wrong invoices with zero false alarms.
- Ships as a Dockerized FastAPI service, exposed to AI assistants through a least-privilege **MCP** server.
- *Python · Gemini · FastAPI · MCP · Pydantic · RapidOCR · Docker*

**[Schema RAG](https://github.com/SorathiyaSwaraj/RAG-sql-generator)**: natural-language-to-SQL generation with RAG
- Generates SQL queries and stored procedures from plain-English requirements, grounded in large MySQL and Oracle schemas (266 tables, 4,183 columns on MySQL).
- Hybrid BM25 + vector retrieval with rank fusion and foreign-key graph expansion: **0.69 recall@20**, against 0.44 for vector-only and 1.9–2.6× a LangChain baseline.
- Static SQL validation catches hallucinated tables and columns before an LLM repair loop runs. SQL is never auto-executed.
- *Python · Gemini · Ollama · fastembed · sqlglot · LangChain*

### 🧠 What I work with
- **GenAI:** LLM APIs (Gemini, Ollama), AI agents, tool-calling, Model Context Protocol (MCP), prompt engineering (system prompts, few-shot, JSON-schema outputs), vision LLMs, entity extraction
- **RAG:** ingestion, chunking, embeddings, vector and hybrid search, LangChain
- **Evaluation:** precision / recall / F1, recall@k, MRR, agent benchmarking
- **Backend:** Python, FastAPI, Pydantic, REST APIs, Go (Gin), Docker, microservices, NATS
- **Databases:** MySQL, Oracle, MongoDB, SQL & stored procedures

<p align="left">
<a href="https://www.python.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/></a>
<a href="https://fastapi.tiangolo.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="fastapi" width="40" height="40"/></a>
<a href="https://go.dev" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original-wordmark.svg" alt="go" width="40" height="40"/></a>
<a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/></a>
<a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/></a>
<a href="https://www.oracle.com/database/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/></a>
<a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/></a>
<a href="https://nodejs.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/></a>
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/></a>
</p>

### 🎓 Education
B.Tech in Computer Engineering, Dharmsinh Desai University (2022–2026) · LeetCode rating 1443, 150+ DSA problems solved

### 🤝 Connect with me
<p align="left">
<a href="https://linkedin.com/in/swarajsorathiya" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="swarajsorathiya" height="20" width="30" /></a>
<a href="mailto:swarajpatel08@gmail.com"><img align="center" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/google/google-original.svg" alt="email" height="20" width="30" /></a>
<a href="https://www.leetcode.com/sorathiya swaraj" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="sorathiya swaraj" height="20" width="30" /></a>
<a href="https://instagram.com/sorathiya_swaraj" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="sorathiya_swaraj" height="20" width="30" /></a>
</p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=sorathiyaswaraj&show_icons=true&locale=en&layout=compact" alt="sorathiyaswaraj" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=sorathiyaswaraj&show_icons=true&locale=en" alt="sorathiyaswaraj" /></p>
