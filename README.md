# Agentic Legacy Integrator

An AI-powered solution designed to bridge the gap between legacy mainframe systems and modern, ML-ready architectures. This tool extracts business logic from JCL artifacts and transforms them into clean, cloud-native API contracts.

## Project Objective
To automate the translation of complex enterprise logic (like DFSMS storage rules) into modern system specifications using an Agentic Workflow, ensuring both efficiency and data privacy.

## Key Features
- **Smart Parser:** Robust Python-based extraction of legacy logic from raw JCL files.
- **Agentic Pipeline:** A multi-stage workflow (Parsing → Reasoning → Generation → Validation).
- **Local LLM:** Powered by **Mistral-7B (GGUF)** to ensure sensitive banking/insurance data never leaves your infrastructure.
- **Modern Output:** Generates standardized JSON API contracts and migration risk reports.
- **Production Ready:** Using **Docker** and exposed via **FastAPI**.
