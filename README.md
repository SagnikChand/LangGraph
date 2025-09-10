# LangGraph — react_agent

**Short:** Agentic AI prototypes and tooling for LangGraph architectures — Python backends + experiment utilities.

## Contents
- `react_agent.py` — main Python agent backend
- `requirements.txt` — Python dependencies
- `.env.example` — environment variable template
- `notebooks/` — exploratory notebooks (optional)

## Setup (local)
1. Create & activate venv:
   - `python -m venv venv`
   - `source venv/bin/activate` (macOS/Linux) or `.\venv\Scripts\Activate.ps1` (Windows)
2. Install dependencies:
   - `pip install -r requirements.txt`
3. Copy `.env.example` → `.env` and add your API keys.
4. Run the agent backend:
   - `python react_agent.py`
   - or `uvicorn react_agent:app --reload` (if FastAPI)

## Development notes
- Do **not** commit `.env` or `venv/`.
- To update dependencies: `pip freeze > requirements.txt`.
- Use GitHub Secrets for CI / deployment keys.

## Contact
Sagnik Chand — lesagnik@gmail.com
