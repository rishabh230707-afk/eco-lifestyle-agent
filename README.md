# Eco Lifestyle Agent (RAG-Based) — IBM watsonx Orchestrate

**Student:** Rishabh Bansal
**College:** Maharaja Agrasen Institute of Technology
**Program:** Edunet Foundation × IBM SkillsBuild — AICTE Virtual Internship 2026–27
**Problem Statement:** No. 6 — Eco Lifestyle Agent (RAG Based)

## Overview
A conversational **Eco Lifestyle Agent** built on **IBM watsonx Orchestrate**, grounded
via Retrieval-Augmented Generation (RAG) in trusted sustainability sources. The agent
helps users adopt a greener lifestyle through personalized, practical, everyday guidance
— sustainable living tips, eco-friendly product recommendations, local recycling
guidelines, and government schemes.

## The Challenge
Users often lack quick, trustworthy, and personalized guidance on sustainable living.
Information is scattered across unreliable sources, making it hard to act on small,
high-impact eco-friendly changes. The Eco Lifestyle Agent solves this by retrieving
verified environmental content and answering natural-language questions like
*"How can I reduce plastic use at home?"* instantly.

## Tech Stack
- IBM watsonx Orchestrate (agent build, behavior, knowledge, publishing)
- Foundation model: GPT-OSS 120B / IBM Granite
- Retrieval-Augmented Generation (RAG) over a sustainability knowledge base
- IBM Cloud (Lite/Trial plan)

## Repository Contents
- `app.json` — Orchestrate agent export/config placeholder (replace with your real export)
- `problem_statement.md` — the official problem statement for this project
- `AICTE_Project_Submission_Rishabh_Bansal_Recipe_Agent.pptx` — final project submission deck
  (add this file when you upload to GitHub)

## How the Agent Works
1. User sends a natural-language sustainability question, e.g. "What's the best way to recycle e-waste near me?"
2. watsonx Orchestrate routes the request to the Eco Lifestyle Agent.
3. The agent retrieves relevant content from the sustainability knowledge base (RAG).
4. The foundation model generates a grounded, practical, actionable response.
5. The response is returned to the user in the chat interface.

## Setup
1. Create an IBM Cloud account and provision **watsonx Orchestrate** (Lite/Trial).
2. Create a new agent, select a foundation model (GPT-OSS 120B or IBM Granite).
3. Add behavior instructions and upload sustainability reference documents to the knowledge base.
4. Set a welcome message and suggested prompts (e.g. "Reduce plastic use at home").
5. Test the agent in debug mode, then **Deploy** and **Publish to catalog**.

## License
Educational project — Edunet Foundation / IBM SkillsBuild AICTE Internship 2026–27.
