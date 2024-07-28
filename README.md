# Running Lamma2 on CCPU Machine


# How to run

### Steps
1. clone the repsitory 

```bash
git clone https://github.com/dhananjai14/Lamma2_CPU.git
```

2. Create a virtual environment (As per the ubuntu)

```bash 
python3 -m venv venv
```

3. Activate the environment (As per the ubuntu)

```bash
. venv/bin/activate
```

4. Install the requirements
```bash
pip install -r requirements.txt -q
```

5. Download the Lamma2 quantized model from hugging face

source: https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main

model name:  llama-2-7b-chat.ggmlv3.q4_0.bin

6. Run the main.py file

```bash
python3 main.py
```

7. To change the behaviour LLM change the "CUSTOM_SYSTEM_PROMPT" present in path "src/helper.py" file

Volla!!! 