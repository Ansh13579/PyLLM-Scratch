# simple-llm-pytorch  
a lightweight implementation of a large language model (llm) using pytorch, based on the llama architecture. perfect for learning and experimenting with llms without the heavy lifting!

## about the project  
this project is a simplified version of a large language model (llm) built from scratch using pytorch. it uses the meta-llama/llama-3.2-1b model as a base, extracts its weights, and reimplements the transformer architecture with custom layers, attention, and beam search generation. i made this to understand llms better and play around with text generation.

### features  
- custom transformer architecture with multi-head attention and swiglu activation.  
- beam search for text generation with top-k, top-p, and repetition penalty.  
- memory-efficient design with garbage collection and cuda memory clearing.  
- easy to modify and experiment with for learning purposes.

## getting started  

### prerequisites  
- python 3.8+  
- pytorch (with cuda support if you have a gpu)  
- transformers library by huggingface  
- a huggingface account with access to meta-llama/llama-3.2-1b (you need to request access on huggingface)

### installation  
1. clone the repo:  
   ```bash
   git clone https://github.com/ansh13579/simple-llm-pytorch.git
   cd simple-llm-pytorch
