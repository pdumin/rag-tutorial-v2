# Local RAG with Ollama models and pdf support

❗️ Forked and modified from: [https://github.com/pixegami/rag-tutorial-v2](https://github.com/pixegami/rag-tutorial-v2)

0. Download and install [ollama](https://github.com/ollama/ollama) and pull models:
   ```
   ollama pull llama3
   ollama pull mxbai-embed-large
   ```

1. Create and activate enviroment:
   ```
   python -m venv .venv
   source .venv/bin/activate
   ```
2. Install dependencies:
   ```
   pip install requirements.txt
   ```
3. Add pdf files to `data` folder
4. Run streamlit app:
   ```
   streamlit run app.py
   ```

   If there is another streamlit installed you can run streamlit from specified enviroment:
   ```
   .venv/bin/python -m streamlit run app.py
   ```
5. Press `Load` button for getting embeddings of pdf-file(s)
6. Ask model about content

