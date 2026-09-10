<table>
<tr>
<td width="100%" valign="middle">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=1000&size=26&pause=1000&color=0E75B6&center=true&vCenter=true&width=1000&lines=Pawan+Kumar+Sani;AI+Engineer;RAG+Systems+%7C+Agentic+Workflows+%7C+LLM+Serving" alt="Typing SVG" />

<p>
  <em>Building retrieval-augmented and agentic AI systems with LangChain &amp; LangGraph</em>
</p>

<p>
  <a href="https://linkedin.com/in/pawan-sani-224a2242b">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://x.com/PawanSani11">
    <img src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white" alt="X" />
  </a>
  <a href="mailto:pawan.sani321@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <br>
  <img src="https://img.shields.io/github/followers/PawanKumarSani?label=Followers&style=flat-square" alt="GitHub followers" />
  <img src="https://komarev.com/ghpvc/?username=PawanKumarSani&label=Profile+Views&color=0e75b6&style=flat-square" alt="Profile views" />
</p>

</td>
<td width="30%" align="center">
  <img src="https://i.gifer.com/Paz.gif" width="200" alt="Fun GIF" />
</td>
</tr>
</table>

<br>

## About

I design and build end-to-end AI systems — retrieval-augmented generation pipelines, multi-agent orchestration, and model serving — with a focus on making them production-ready rather than proof-of-concept.

- 🔭 Currently building RAG pipelines and multi-agent workflows with LangChain and LangGraph
- 🌱 Exploring LangGraph multi-agent patterns, model quantization, and inference optimization
- 🧠 Comfortable across the retrieval stack: chunking strategies, embedding models, vector databases (FAISS, ChromaDB), and citation-grounded generation
- 💬 Open to conversations on Python, RAG, LangChain, LangGraph, PyTorch, or AI agents
- 📫 **pawan.sani321@gmail.com**

<br>

## Tech Stack

<div align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />

<br>

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" />
<img src="https://img.shields.io/badge/FAISS-005571?style=flat-square" />
<img src="https://img.shields.io/badge/ChromaDB-6A4EFC?style=flat-square" />
<img src="https://img.shields.io/badge/Groq-F55036?style=flat-square" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />

<br>

<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />

</div>

<br>

## Featured Projects

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>Multi-Agent Research Assistant</h3>
      <p>A LangGraph system where a deterministic supervisor routes between four specialized agents — researcher, analyst, writer, and reviewer — to research a topic end-to-end and produce a report. The writer/reviewer pair loops until the draft is approved or a revision cap is hit, with real tool integrations (web, arXiv, Wikipedia) and checkpointed state for pause/resume.</p>
      <p>
        <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" />
        <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square" />
        <img src="https://img.shields.io/badge/Groq-F55036?style=flat-square" />
      </p>
      <a href="https://github.com/Pawankumarsani/multi_agent_research_assistant">View Repository →</a>
    </td>
    <td width="33%" valign="top">
      <h3>Multimodal RAG Pipeline</h3>
      <p>A RAG pipeline that processes PDFs containing both text and images, using CLIP embeddings for cross-modal retrieval, FAISS for vector search, and a Groq-hosted LLM for generation. Structured as a clean, flat pipeline: <code>load_data → chunking → vectordb → retrieval → pipeline</code>.</p>
      <p>
        <img src="https://img.shields.io/badge/CLIP-000000?style=flat-square" />
        <img src="https://img.shields.io/badge/FAISS-005571?style=flat-square" />
        <img src="https://img.shields.io/badge/Groq-F55036?style=flat-square" />
      </p>
      <a href="https://github.com/Pawankumarsani/multi_model_rag">View Repository →</a>
    </td>
    <td width="33%" valign="top">
      <h3>Agentic RAG</h3>
      <p>An agent-driven RAG system that decides whether retrieval is needed, retrieves from LangGraph/LangChain docs via FAISS, checks retrieved documents for relevance, rewrites the query when they fall short, and generates a grounded answer through a Streamlit chat interface.</p>
      <p>
        <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" />
        <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square" />
        <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
      </p>
      <a href="https://github.com/Pawankumarsani/Agentic_RAG">View Repository →</a>
    </td>
  </tr>
</table>

> Update the Multimodal RAG link once the repository is public under its final name.

<br>

## GitHub Stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=PawanKumarSani&show_icons=true&theme=vue&hide_border=true&bg_color=00000000" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PawanKumarSani&layout=compact&theme=vue&hide_border=true&bg_color=00000000" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=PawanKumarSani&theme=vue&hide_border=true&background=00000000" />
</div>

<br>

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=gruvbox" />
</div>

