# NL2SQL

In this project, I ran a large language model locally (Llama3) for a NL2SQL task (On CPU)

1. Clone the repository:
```bash
git clone git@github.com:Ewins518/nl2sql-ollama-llama3.git
```

2. Navigate in the directory
```bash
cd nl2sql-ollama-llama3
```

3. Run docker
```bash
docker compose up -d
```

4. Run the model locally (llama3):

```bash
docker exec -it ollama ollama run llama3
```

You can now chat with the model on the terminal

5. Execute python file on your host terminal
```bash
python req_ollama.py
```

If you have GPU, go to the official  [ollama docker image](https://hub.docker.com/r/ollama/ollama) for configuration.

Enjoy!
