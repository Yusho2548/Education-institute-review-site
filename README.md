
# Education Intelligence Platform

An education discovery and intelligence platform designed to help students explore, compare and evaluate higher-education institutions using structured data and AI-assisted research.

## Problem Statement

Students often need to consult multiple websites, institutional pages and admission documents to understand available courses, fees, eligibility requirements and admission processes. Information can be inconsistent, difficult to compare or outdated.

This project aims to centralise institution information and provide a conversational interface that helps students find relevant, evidence-backed answers.

## Initial Scope

**Geographical focus:** Chandigarh, Mohali (SAS Nagar) and Panchkula.

Core capabilities:
- Search and filter educational institutions.
- Explore courses, fees, locations and eligibility information.
- Compare institutions using explicit criteria.
- Ask questions through a conversational AI assistant.
- Retrieve relevant information from official admission documents.
- Display sources and data verification dates where available.

## Technology Stack

- Frontend: HTML, CSS and JavaScript
- Existing web backend: PHP
- Database: MySQL
- AI backend: Python and FastAPI
- Local inference: Ollama with a compatible Qwen model
- Document retrieval: ChromaDB and Sentence Transformers (planned)
- Version control: Git and GitHub
- Frontend deployment: Vercel (planned)

## Architecture Principles

1. MySQL is the source of truth for structured institution records.
2. AI-generated factual answers must be grounded in retrieved evidence.
3. Database access must use validated, parameterised queries.
4. The language model must not execute arbitrary SQL.
5. Institution data must be updateable without fine-tuning the model.
6. Components should be testable and replaceable independently.

## Development Roadmap

1. Inspect and document the existing website and database.
2. Establish reliable institution search and comparison.
3. Build a Python AI service with approved database-search tools.
4. Integrate a local language model through Ollama.
5. Add document retrieval and explainable recommendations.
6. Evaluate reliability, secure the application and deploy.

## Project Status

Architecture and repository setup.

## License

To be finalised before public release.
