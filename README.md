# setup-manuscript

![Version](https://img.shields.io/static/v1?label=setup-manuscript&message=0.1&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


Script for creating common subfolders in a folder for a manuscript on my local computer. The script also writes a AAAreadme.md file with a description of the role of each subfolder.

I was tired of having heterogeneous subfolder structures for different research papers, so I wrote this script. I am sharing this script on GitHub because it might inspire others to follow a similar approach and because I needed to get it under version control.

My workflow involves writing the manuscript in LaTeX on Overleaf. I have additional subfolders on Overleaf. The project on Overleaf is under version control in the `ov' subfolder.

I store this script in a folder called 000manuscripts in my home directory.
I have mapped this script to an alias stored in my `.bashrc` or `.zshrc` file: 
```bash
setupManuscript='cp ~/000manuscripts/setupManuscript.sh . && ./setupManuscript.sh && echo "Now write the paper!"'
```
After sourcing the `.zshrc` file to load the alias, I create a new manuscript folder in my home folder, move to it, and enter `setupManuscript` in the terminal.
In a few seconds and with very little mental bandwidth, I can create the manuscript folder structure that I need for a research paper.


- [The writer's law](https://github.com/MooersLab/thewriterslaw)
