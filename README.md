# Requirements

You need Docker and Python installed on your machine.
You also need to have Testcontainers Cloud installed and running and connected to a GPU-enabled zone.

# Setup

Create a virtual environment and install the requirements:

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
# Running the examples

Start the Juputer Lab server:

```bash
jupyter lab
```

Open the notebook `gpu.ipynb` and run the cells.
You will see an Ollama Docker container being started, including GPU access.
It will be wired up using LangChain and you can interactively explore the framework and model.
