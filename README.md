AI
==
### Lab exercises for Artificial Intelligence course

*Suggested software: Spyder*

After struggling a bit with Spyder during the first lab i decided to go with Jupyter notebook. It may not show everything like Spyder does, but it's less abstracted from the code and requirements and at least I know what I'm doing. I was using PyCharm before and thought about using it for this, but I remembered the same issue - clicking on things to try to fix things I didin't know anything about, without any understanding of the issue or the solution. Not the way to learn.

## Prepare
### Install python, pip and tools for PDF creation required by Jupyter lab
```bash
sudo apt-get install python3 python3-pip pandoc texlive-xetex
```

#### Install Jupyter lab and required libs *as user*
```bash
pip3 install --user jupyterlab numpy pandas matplotlib sklearn statsmodels keras tensorflow
```

#### Add ~/.local/bin to PATH 
See .profile file, copy the part to .bashrc

## Run Jupyter lab
```bash
cd ~/path/to/ai_dir
jupyter lab
```
or even better
```bash
screen -d -m -S jupyter jupyter lab
```

