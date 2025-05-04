# AI-Powered-ATS-Friendly-Resume-Creator
Description:

AI Resume Optimizer is a local, AI-powered tool designed to help job seekers improve their chances of passing Applicant Tracking Systems (ATS). It automatically scans resumes for formatting issues, aligns content with job-specific keywords, and minimizes manual editing errors. By enhancing ATS compatibility and keyword relevance, this tool streamlines resume customization and increases the likelihood of getting noticed by recruiters.

Key Features:

ATS-friendly formatting corrections

Keyword suggestions based on job descriptions

Local processing for privacy and security

Reduced manual editing time

Improved resume relevance and impact

Research Questions 

Can local multi-agent LLMs outperform traditional/manual approaches?​

How effectively can agents extract skills from job descriptions and match them with resumes?​

Which agent roles have the most impact on improving ATS scores?​

What are the technical and operational challenges of using local open-source LLMs?​

Proposed Solution

We propose a local multi-agent AI system using open-source LLMs via Ollama and CrewAI.​

Each agent has a specific task: parsing, analyzing, optimizing, rewriting, reviewing, and reporting.​

 System Architecture Overview

 The system includes:​

A Streamlit-based UI​

An orchestrator service manages the flow​

Specialized agents for resume parsing, analysis, and optimization​

A knowledge base and vector store for storing ATS best practices​

Ollama LLM service provides local language model support​

Architecture Diagram

![image](https://github.com/user-attachments/assets/b212fc75-16c9-4253-b34f-4f7a2a27d3a3)

Agents and Their Roles​

Resume Parser: Extracts structured data​

Resume Analyzer: Identifies gaps and missing keywords​

ATS Optimizer: Suggests keyword insertions​

Resume Writer: Rewrites sections to improve clarity and ATS fit​

Critic: Reviews formatting and readability​

Report Generator: Provides detailed feedback and summary​

Technologies Used

CrewAI: Manages agent orchestration​

Ollama: Local deployment of LLaMA 3 and DeepSeek R1​

Streamlit: Frontend UI​

Python: System backend and service logic​

Vector DB: Qdrant or ChromaDB for similarity search and context retrieval

Pipeline and Workflow

![image](https://github.com/user-attachments/assets/e557c8b2-bb14-41a9-ab92-d703e6547ff1)

Evaluation Metrics

![image](https://github.com/user-attachments/assets/d9e56adf-a795-47cd-8d65-e1776f8d830f)

Results​

![image](https://github.com/user-attachments/assets/e786b019-65a7-4363-9eec-57ab0c27926c)

Challenges and Limitations

![image](https://github.com/user-attachments/assets/c7f2d407-80c6-42b3-90e8-c386d3380893)

Future Work

![image](https://github.com/user-attachments/assets/3a91b5fe-3640-4449-968e-28189e33ed31)

Conclusion

A local, multi-agent LLM-based system can significantly improve resume quality and ATS compatibility.​We leverage open-source models and agent collaboration to provide a low-cost, intelligent tool for job seekers.​This aligns with the intention to democratize AI-based career tools.​








The system ensures resumes are keyword-rich, well-structured, and ATS-compliant.
 
