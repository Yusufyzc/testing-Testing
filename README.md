<div style="font-size:16px">
TinyLlama link: https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0 --Using GPU  ~1GB 

<p>Firstly, you have to install anaconda in your device,
<p>Secondly, create an environment in anaconda -anaconda navigator is easly, but in prompt "conda create -n envName python:3.11" //python3.11 version is working with this, but it is changeable for others
<p>Thirdly, install cuda tools using anaconda prompt but
<p>----  1.Open anaconda prompt and access the environment "conda activate envName"
<p>----  2.You have to use "conda install" command for installing everything, you have to install use that: "conda install transformers pytorch torchvision torchaudio <p>pytorch-cuda=12.1 -c pytorch -c nvidia"
<p>Fourthly, if you install all of the packages you can use them easily but if you want to use them in jupyter, you have to link them.
<p>You should ensure you are in environment that you use in the prompt
<p>In anaconda prompt enter this command: python -m ipykernel --user --name envName --display-name "whatEverYouWANT"
<p>You linked with anaconda environment with jupyter
<p>Lastly, in the .ipynb python files of this repository, open the python files in jupyter and execute the file.
</div>
