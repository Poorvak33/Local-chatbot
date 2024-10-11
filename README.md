# Local-chatbot
Locally hosted chatbot with LLAMA 3.2 and huggingface gradio
1)Created virtual env using conda
2)set up depencies (transformers, torch, gradio, and dotenv)
3)utilized huggingface library
4)Created custom chat template for tokenizer
5)used eos_token_id for the end of the generation 
6)Had to utilize quantization method using butsandbytes to run it efficiently on 8gb Mac M1 CPU 
7)Had to run model on CPU to avoid MPS memory issue
8)Executed the code on local URL 
