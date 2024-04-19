### This Repo is not for use sLLM, just Research and Developing sLLM logics

#### all files doesn't include model like safetensor type file or json
#### just only code and jupyter notebook's output results

#### if you try some fine-tuning in sLLM using GPU(Nvidia-A100), you can follow this 3steps.

## Step 1.
---
### load dataset and tokenizer and model
> load dataset need library "datasets"
>> if you install "datasets" yet. you can follow this prompt "pip3 install datasets"

## Step 2.
---
### Arguments 
> you must make 3 arguments.
>> 1. training argument 
>> 2. tokenizer argument
>> 3. evaluate argument 

## Step 3.
---
### Train
> Train function use like this  model_trainer.train()