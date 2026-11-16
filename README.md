# Arinze Elenasulu

AI engineer in London. I build agent systems and LLM products, and the Python backends they run on.

I like building software close to real operations, where the system has to match how people actually work.

## What I've built

**Pharmacy operations system, Vigilis Pharmacy** (2024 to 2026). I built the whole system the pharmacy uses, as its only developer, and they still use it.
Before it, staff wrote invoices by hand and walked them to the cashier.
Now an invoice is raised at the counter, paid, confirmed and taken off stock in one step.
Staff ask the embedded agent in plain words for the day's sales or a price change, instead of searching records or editing prices by hand.
React, FastAPI and PostgreSQL, with role-based access, pytest and cloud deployment.

**[Weaver](https://github.com/haxsysgit/Weaver)**. An LLM product that answers questions over a 3,148-chapter novel and cites the chapters it used, running on AWS EC2.
I built a 40-question golden set and scored six retrieval arms against it.
The best reached only 0.35 hit@5, so I moved the design to an agent that chooses between six reading tools and has to trace every claim to the text.
Hybrid search in Qdrant, FastAPI with streamed responses, 500+ tests and CI/CD from GitHub Actions to EC2.

**[HaxJobs](https://github.com/haxsysgit/Haxjobs)**. A job-search automation harness that finds roles, scores the fit and builds the application packs, with a monitoring interface.
It reads the Lever, Ashby and Greenhouse job boards directly and runs on a schedule.

**[Haxaml](https://github.com/haxsysgit/haxaml)**. A governance runtime for AI coding workflows, published on PyPI.
It puts rules and verification gates around a coding agent through an MCP server, a CLI and a local dashboard.
It reads the project from [FRAME](https://github.com/haxsysgit/FRAME), a structured context format for AI-assisted projects (Facts, Rules, Acts, Map, Expect), and [FrameSDK](https://github.com/haxsysgit/FrameSDK) loads those files into typed Python objects (it's on PyPI as framesdkpy).

## Stack

Python, FastAPI, PostgreSQL, SQLAlchemy, React and TypeScript.
Agents, tool calling, MCP, RAG with Qdrant, and LLM evaluation.
pytest, Docker, GitHub Actions and AWS.

## Contact

[LinkedIn](https://www.linkedin.com/in/arinze-elenasulu) · elenasuluarinze@gmail.com · London
