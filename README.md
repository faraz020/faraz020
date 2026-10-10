# Faraz Ahmad Siddiqui

### AI Automation Developer · Python · n8n · RAG

I build AI workflows that connect business tools, process information, and automate repetitive work. My focus is practical integrations: turning an idea into a workflow with clear inputs, useful outputs, and documented setup.

[View my featured projects](#featured-projects) · [Connect on LinkedIn](https://www.linkedin.com/in/faraz-siddiqui/)

## What I can help you build

| Service | Example scope |
| --- | --- |
| **Workflow automation** | n8n and Make.com workflows connecting APIs, webhooks, Airtable, and Google Workspace |
| **AI agents and knowledge search** | Document processing, embeddings, vector search, and retrieval-augmented generation |
| **Voice and content workflows** | Lead qualification and appointment workflows with Vapi; Python pipelines for narrated, captioned video |

## Featured projects

### [AI Content Automation Pipeline](https://github.com/faraz020/End-to-End-AI-Content-Automation-with-n8n-Python)

A modular Python pipeline that turns an AI-generated fictional story into a captioned vertical video.

**Flow:** Groq story generation → Pillow headline card → edge-tts narration → faster-whisper word captions → FFmpeg video assembly.

- Structured JSON generation with premise-history and validation checks.
- Narration and captions aligned to the same audio, including a headline/story pause.
- Vertical video composition with background footage and optional music.
- Environment-based credentials, setup documentation, and sample media.

**Stack:** Python, Groq, Pillow, edge-tts, faster-whisper, FFmpeg. Designed for self-hosted n8n orchestration; the workflow export is being prepared for publication.

### [AI Job Matching & Resume Automation](https://github.com/faraz020/AI-Job-Matching-and-Resume-Automation)

Three n8n workflows that turn job listings into a ranked shortlist and tailored Google Docs resumes.

**Flow:** Remote OK + Adzuna job discovery → Supabase vector search → NVIDIA job-fit evaluation → Google Sheets shortlist → Google Docs resume tailoring.

- Normalize and deduplicate job listings before embedding them.
- Match candidate-profile information to jobs and generate fit scores, explanations, and red flags.
- Tailor resume content using the master profile and fill a Google Docs template.
- Sanitized workflow exports with credential mapping, setup instructions, and fictional examples.

**Stack:** n8n, NVIDIA NIM, Supabase pgvector, Adzuna, Google Drive, Sheets, and Docs. Generates resumes for review; application submission remains manual.

## Other project experience

- **AI voice appointment automation:** built lead-qualification and scheduling workflows using Vapi, Make.com, n8n, and Airtable.

## Tools I work with

**Automation & APIs:** n8n · Make.com · REST APIs · Webhooks · Vapi · Airtable · Google Workspace APIs  
**AI & retrieval:** LangChain · LangGraph · Groq · NVIDIA NIM · Supabase pgvector · Pinecone  
**Development & media:** Python · SQL · Docker · Git · FFmpeg · Pillow · faster-whisper

## Background

Computer Science undergraduate at FAST-NUCES. During my AI automation internship at FlyRankAI, I worked on document processing, vector search, and retrieval workflows for context-aware AI agents.

## Discuss a project

Send me a message on [LinkedIn](https://www.linkedin.com/in/faraz-siddiqui/) with the process you want to automate, the tools you use, and the result you need. We can define a focused scope and the integrations it requires.
