# FLY E-commerce Shopping Chatbot FINAL

Free/local-first FLY shopping chatbot with the same major workspace areas: Dashboard, Shopping Chatbot, Orders, Products, Purchase, Customers, Inventory, Accounts, My Tasks, Reports, Learning, Settings, Grow Your Business and FLY Admin.

## Run in PyCharm
1. Extract ZIP.
2. Open folder in PyCharm.
3. Open Terminal.
4. `python -m venv .venv`
5. `\.venv\Scripts\Activate.ps1`
6. `python -m pip install -r requirements.txt`
7. Optional local AI: install Ollama and run `ollama run llama3.2`.
8. `python run.py`
9. Open `http://127.0.0.1:8000`
10. API docs: `http://127.0.0.1:8000/docs`

The database is SQLite and is created automatically. Demo data is inserted on first run. The chatbot works with a local fallback even when Ollama is unavailable.
