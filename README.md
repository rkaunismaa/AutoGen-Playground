# AutoGen-Playground 

This will be my playground for all things using AutoGen.

One of my primary source of code samples will be the [Microsoft AutoGen Examples](https://microsoft.github.io/autogen/docs/Examples/)

One of the principle goals of this playground is to always use a local Large Language Model, and stay away from OpenAI.

conda activate autogen

## Wednesday, January 24, 2024

The first code sample from the above repo was not working. A little digging reveals the code may no longer work with the current release of autogen. 

## Thursday, January 25, 2024

The notebook 'agentchat_RetrieveChat.ipynb' required I install chromadb.

1) mamba install conda-forge::chromadb
2) mamba install pypdf
3) mamba install sentence-transformers
4) mamba install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia


