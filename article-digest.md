# Article Digest — Proof Points & Project Narratives

## M2M Tech — Agentic Orchestration Platform (Current)

Developing an agentic orchestration platform that connects to digital twins across different industries. This is the culmination of everything learned at M2M — from the early LoRA experiments through LangChain pipelines to full agent systems. The platform uses FastAPI and MCP integration for seamless inference and endpoint registration, reducing development lead time by 40%. The architecture decisions here reflect lessons from every prior project: reliability over cleverness, production-readiness from day one, and clear interfaces between components.

Key learning: agent orchestration methods are evolving rapidly. The approach isn't to pick one framework and commit — it's to understand the underlying patterns (tool use, planning, memory, handoffs) so the system can adapt as the field moves.

## M2M Tech — Mental Health App (Agent-Based Insurance Extraction)

Designed an agent-based system for a mental health application. The core problem: take a user's insurance information, parse out what mental health benefits they actually have (which is surprisingly complex — different tiers, networks, co-pays, session limits), and recommend how to optimally use those benefits for specific mental health services.

This was the first real agent project. The system needed to handle ambiguous, semi-structured insurance documents and make actionable recommendations. The key insight was that a single LLM call couldn't reliably handle the full pipeline — breaking it into discrete agent steps (extraction → classification → matching → recommendation) made each step auditable and testable.

## M2M Tech — Maritime Crime Detection & Intelligence

The most challenging client project. Built an NLP pipeline for extracting domain-specific entities from 100 maritime crime articles using LangChain with self-critique prompting. The self-critique loop was essential — first-pass extraction missed context-dependent entities that only make sense in maritime domain (vessel types, route patterns, incident classifications).

Separately built a data pipeline classifying 790 prompts to determine which were suitable for web scraping, then evaluated scraping results from Google and Bing using ROUGE and other quality metrics. This was the introduction to systematic prompt evaluation — not just "does it work" but measurable quality scores.

Production handoff was intense: implemented pytest coverage in a single day under deadline pressure, wrote both technical and functional documentation, and reorganized the entire codebase architecture to match the client's requirements. The lesson: production readiness isn't optional, and documentation written under pressure is still better than no documentation.

## M2M Tech — Ocean Wave Energy (NEMOH)

Data processing pipeline for digital twin modeling in ocean wave energy. Worked with NEMOH, an open-source Boundary Element Method software, processing a dataset of 200k+ records. The challenge was domain knowledge — had to quickly learn enough about wave energy physics to make meaningful feature engineering decisions rather than just blindly processing numbers.

This project reinforced a pattern: the ML engineering is rarely the hard part. Understanding the domain well enough to ask the right questions and engineer the right features is what separates useful models from technically correct but useless ones.

## M2M Tech — Stable Diffusion / LoRA (First Project)

First project at M2M: fine-tuning Stable Diffusion models with LoRA to generate line drawing pictures in a specific style for marketing material. The models at the time (early Stable Diffusion era) weren't capable enough to meaningfully achieve the goal — the style transfer wasn't consistent enough for production use.

The project wasn't a success in terms of deliverables, but it was formative: first real exposure to Linux environments, model fine-tuning workflows, and the gap between "technically possible" and "production-viable."

## M2M Tech — Teaching & Curriculum Design

Designed and taught multiple courses to cohorts of 10-25 people (40+ students total) covering Python, Power BI, and the Azure stack. The courses progressed from basic data analytics through machine learning up to digital twins.

This built on 4 years of tutoring experience (40+ students from elementary to university level). The core skill carried forward from tutoring to technical teaching to client communication: listening to understand where someone actually is before explaining, rather than assuming a starting point.

## M2M Tech — Sales & Conference Work (Full-Time Role)

Promotion to full-time ML Engineer added business development responsibilities. Now attend sales calls to explain technical portions of what's pitched to prospective clients. Attended a conference where the engineering team (3 people) handled both technical demos and sales outreach with specific booking targets.

This is a differentiator: most ML engineers don't do client-facing sales. The combination of being able to build the system AND explain it to a non-technical buyer is rare. Time management became critical — balancing active development projects with sales preparation and follow-ups.

## M2M Tech — Content & Marketing (Side Responsibilities)

Writes blog posts and reviews marketing scripts for advertising M2M products. This is a side responsibility on top of core engineering and sales work — not the main role, but further evidence of versatility. The ability to write technical content that's also marketing-effective is another communication differentiator. Useful proof point for roles that value technical writing, developer advocacy, or cross-functional contribution.

## Entrepreneurial Ventures — Food Waste Tracker

Developed an MVP for a smart fridge app designed to reduce household food waste. Put significant effort into ideation, working with an app developer, and attending events to meet people and pitch the concept.

Key learning: initial assumptions about user behavior don't survive contact with reality. Learned how food is actually preserved in businesses vs. households, and discovered that the initial concept didn't match people's actual habits and willingness to change behavior. The pivot insight — "meet people where they are, not where you think they should be" — carries directly into product design and client work.

## Entrepreneurial Ventures — Precision Agriculture

Early-stage exploration of precision agriculture focused on soil health monitoring. Less developed than the food waste project but shows pattern of identifying real-world problems and exploring technical solutions.

## Teaching Thread (Career-Spanning)

A continuous thread from high school tutoring through university to professional teaching:
- **Tutoring (4 years, 40+ students):** Elementary to university. Learned to listen and understand different perspectives to explain tricky concepts.
- **Youreka Canada:** Led high school students through a research project. Reinforced teaching and leadership.
- **NXT-GEN:** Recruited 50+ students, managed marketing team. Stressful moments requiring time management under pressure.
- **M2M Tech courses:** Formalized the teaching into structured curricula for professional audiences.

The throughline: the ability to translate complex technical concepts for different audiences is the same skill whether the audience is a 10-year-old learning math, a high school student doing research, or a prospective client on a sales call.

## Certifications

- **GCP Professional Machine Learning Engineer** (May 2025) — production ML on Google Cloud
- **AWS Certified Machine Learning Engineer – Associate** (Sep 2025) — ML pipelines on AWS
- **Microsoft Azure AI Fundamentals (AI-900)** (Jan 2024) — foundation, built on extensively through M2M projects

Three cloud ML certifications across GCP, AWS, and Azure demonstrates breadth across platforms — not locked into one vendor's ecosystem.
