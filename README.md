TinyLlama link: https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0 --Using GPU  ~1GB 

[Not recommended because it doesn't unload ram usage] -- KumruAI link: https://huggingface.co/vngrs-ai/Kumru-2B --Using CPU 5GB --Not recommended because it doesn't unload ram usage


Firstly, you have to install anaconda in your device,
Secondly, create an environment in anaconda -anaconda navigator is easly, but in prompt "conda create -n envName python:3.11" //python3.11 version is working with this, but it is changeable for others
Thirdly, install cuda tools using anaconda prompt but
  1.Open anaconda prompt and access the environment "conda activate envName"
  2.You have to use "conda install" command for installing everything, you have to install use that: "conda install transformers pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia"
Fourthly, if you install all of the packages you can use them easily but if you want to use them in jupyter, you have to link them.
You should ensure you are in environment that you use in the prompt
In anaconda prompt enter this command: python -m ipykernel --user --name envName --display-name "whatEverYouWANT"
You linked with anaconda environment with jupyter
Lastly, in the .ipynb python files of this repository, open the python files in jupyter and execute the file.
