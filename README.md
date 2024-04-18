# Prompt Engineering

## Prerequisites

### Environment
- VSCode IDE
- Python 3.11.8
- pip 24.0
- Jupyter Notebook 
- OpenAI API Key

### OpenAI Credentials
Set environment variables into `.env` file.
Set the API key as an environment variable named OPENAI_API_KEY. 
Set the Base Url as an environment variable named OPENAI_API_BASE.

E.g:
```bash
OPENAI_API_KEY=sk-1234567890abcdef1234567890abcdef
OPENAI_API_BASE=https://api.openai.com/
```

## Build And Run

### Set Virtual Envs
```bash
## create venv
$ python3 -m venv ~/.venvs/aienv

## activate venv
$ source ~/.venvs/aienv/bin/activate

## deactivate venv
$ deactivate
```

### Jupyter Notebook
install jupyter by pip or VSCode Extensions.

```bash
## install jupyterlab
$ pip install jupyterlab
$ pip install notebook

$ jupyter --version
Selected Jupyter core packages...
IPython          : 8.22.2
ipykernel        : 6.29.3
ipywidgets       : 8.1.2
jupyter_client   : 8.6.0
jupyter_core     : 5.7.1
jupyter_server   : 2.13.0
jupyterlab       : 4.1.3
nbclient         : 0.9.0
nbconvert        : 7.16.2
nbformat         : 5.9.2
notebook         : 7.1.1
qtconsole        : 5.5.1
traitlets        : 5.14.1
```

### Execute Jupyter NoteBook
Use shortcut `Contrl + Enter` Or `Run ALL` Button In IDE.

## References
https://github.com/dair-ai/Prompt-Engineering-Guide
https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/
https://learn.deeplearning.ai/courses/chatgpt-prompt-eng/lesson/1/introduction