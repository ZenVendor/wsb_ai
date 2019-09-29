AI
==
###Lab exercises for Artificial Intelligence course

*Suggested software: Spyder*

##Prepare
### Install pip (if not present) and tools for PDF creation
```bash
sudo apt-get install python3-pip pandoc texlive-xetex
```

### Install Jupyter lab and required libs *as user*
```bash
pip3 install --user jupyterlab numpy pandas matplotlib sklear
```

###Add ~/.local/bin to PATH 
See .profile, copy to .bashrc

## Run Jupyter lab 
```bash
cd ~/path/to/ai_dir
screen -d -m -S jupyter jupyter lab
```


##Submit reports on Moodle in PDF
