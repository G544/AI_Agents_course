## AI_Agents_course

This repository contains example code and notebooks for working with small AI agents, search/indexing utilities, and simple agent evaluation tooling used in the course materials. It includes scripts and notebooks for ingesting documentation, building simple search indices, and wiring agents that call search tools and LLM providers.

Contents
- `app.py`, `main.py`, `ingest.py`, `search_agent.py`, `search_tools.py`, `logs.py` — example scripts referenced by the notebooks
- `requirements.txt`, `pyproject.toml` — Python dependency manifests
- `logs/` — folder used for storing interaction logs

Quickstart (local)
1. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set required environment variables (example for OpenAI key):

   ```bash
   export OPENAI_API_KEY="your_api_key_here"
   ```

   Alternatively you can store secrets in a local `.env` file and load them via your preferred method (do not commit `.env` to git).

4. Run a script or notebook. Examples:

   - Run a script:
     ```bash
     python app.py
     ```
