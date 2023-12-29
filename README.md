# Blog Generation App
This is a Blog Generation App which uses Large Language Models (LLM) specifically Llama-2 model to generate a blog using a prompt.
Streamlit framework is used to build the web app to give prompt with number of words to generate blog.

### Requirements
- `streamlit`
- `langchain`
- `ctransformers`
- `python-box`
- `uvicorn`

### Download the model
Create a folder named ***models*** and download the Llama-2 model from huggin face using the following link.
```txt
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/resolve/main/llama-2-7b-chat.ggmlv3.q8_0.bin?download=true
```

### Install the requirements

```bash
$ pip install -r requirements.txt
```

### Open the Webapp

```bash
$ streamlit run app.py
```

### Screeshot from Blog Generation App

Here is a screenshot from Blog Generation App that generates Blog on ***large language model*** having ***300 number of words***.
![alt text](https://github.com/deep4nshu1228/Blog-Generation-App/blob/main/Prompt%20screenshot.png)
