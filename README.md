# Generative-ai-with-LLM

## Week 1: Introduction to LLMs and the generative AI project lifecycle

### Generative AI & LLMs

Fundation model or base model which ar pretrain model for example
 - BERT
 - GPT
 - LLaMa
 - FLAN-T5
 - BLOOM 
 - PaLM

 More parameters needs more memory and are capable of doing more complex task


 __Prompts and completions__: The text we pass to the model to perform a task is called prompt

__LLM use-cases and tasks__:
 
 - write an essey
 - translation
 - Code
 - Small focus task, Information retrieval like Nammed Recognition
 - Augmented LLM with external data sources
 

Text genertation before teransformers:
RNN - recurrent neural network 

Transformater Architecture:

Ref: https://arxiv.org/abs/1706.03762



In context learning:
zero-shot, one-shot, few-shot. 


Generative Configuration:
Max token: 
top-k sampling
top-p 
temperature

__Generative AI project Lifecycle__

```mermaid

flowchat LR;

    Scope--> select --> adapt and align model --> Application integration

```

```mermaid

graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```