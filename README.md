Udacity _UdaPlay_ project: AI game research agent that answers video game questions via RAG over a local games dataset, with Tavily web search fallback, confidence evaluation, and structured reports.

Setup with [uv](https://docs.astral.sh/uv/): `uv venv && source venv/bin/activate && uv pip install -r requirements.txt`

Add your API keys to a `.env` file: `OPENAI_API_KEY=your_key`, `CHROMA_OPENAI_API_KEY=your_key`, `TAVILY_API_KEY=your_key`

Then run Part 1 with `Udaplay_01_starter_project.ipynb` (offline RAG / ChromaDB) and Part 2 with `Udaplay_02_starter_project.ipynb` (agent with retrieve, evaluate, and web search tools).
