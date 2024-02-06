# agent-workflow-test-case-project

## Getting Started

### Setting up Environment

- Download ollama from the official website or use `curl https://ollama.ai/install.sh | sh` for linux
- On MacOS, ensure the ollama server is running while on linux, run `ollama serve` on terminal
- run `ollama run openhermes` on your terminal to download the openhermes model
- create a virtual environment using conda; `conda create -n <name_of_choice> python=3.11`
- Install the python packages using `pip install -r requirements.txt`
- run the python script using `streamlit run app.py`

-----
**NOTE** : IT TAKES AT LEAST 30 MINS TO COMPLETE using CPU, But a GPU will significantly reduce the time needed. Tested on google colab