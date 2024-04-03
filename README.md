# AutoGen-Playground 

This will be my playground for all things using AutoGen.

One of my primary source of code samples will be the [Microsoft AutoGen Examples](https://microsoft.github.io/autogen/docs/Examples/)

One of the principle goals of this playground is to always use a local Large Language Model, and stay away from OpenAI.

conda activate autogen

## Wednesday, January 24, 2024

The first code sample from the above repo was not working. A little digging reveals the code may no longer work with the current release of autogen. 

Hmm right away I get the error ... 

cannot import name 'AssistantAgent' from 'autogen'

Gonna uninstall then reinstall ...

* pip uninstall autogenstudio
* pip install autogenstudio

Nope! Still problems ... so ran ...

* pip uninstall autogenstudo
* pip uninstall autogen
* pip uninstall pyautogen 

... Then ran ... 

* pip install pyautogen

... and now that inital error is gone  ... continuing ... 

The original 'agentchat_RetrieveChat.ipynb' I am going to leave untouched, and then download the most current version of this notebook to 'agentchat_RetrieveChat (1).ipynb'

## Thursday, January 25, 2024

The notebook 'agentchat_RetrieveChat.ipynb' required I install chromadb.

1) mamba install conda-forge::chromadb
2) mamba install pypdf
3) mamba install sentence-transformers
4) mamba install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia

## Wednesday, April 3, 2024

Getting back to playing with AutoGen and AutoGen Studio ...


