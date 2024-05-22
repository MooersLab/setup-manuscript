# setup-manuscript

![Version](https://img.shields.io/static/v1?label=setup-manuscript&message=0.1&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


Script for creating common subfolders in a folder for a manuscript on my local computer. The script also writes an A readme.md file with a description of the role of each subfolder.

I was tired of having heterogeneous subfolder structures for different research papers, so I wrote this script. I am sharing this script on GitHub because it might inspire others to follow a similar approach and because I needed to get it under version control.

My workflow involves writing the manuscript in LaTeX on Overleaf. I have additional subfolders on Overleaf. The project on Overleaf is under version control in the `ov' subfolder.

I store this script in a folder called 000manuscripts in my home directory.
I have mapped this script to an alias stored in my `.bashrc` or `.zshrc` file: 
```bash
setupManuscript='cp ~/000manuscripts/setupManuscript.sh . && ./setupManuscript.sh && echo "Now write the paper!"'
```
After sourcing the `.zshrc` file to load the alias, I created a new manuscript folder in my home folder, moved to it, and entered `setupManuscript` in the terminal.
I can create the manuscript folder structure I need for a research paper in a few seconds and with very little mental bandwidth.

## Retrospective in 2024

I found the empty subfolders in a new project folder to add clutter.
A better approach might be to hide these subfolders by preceding their names with a period.
When the folder is needed, the prepended period can be removed.
The revealed subfolder will have a standardized name. 
This revised approach is found in `setupManuscript2.sh`.



## Related links

- [The writer's law](https://github.com/MooersLab/thewriterslaw)


## Update history

|Version      | Changes                                                                                                                                    | Date                 |
|:-----------:|:------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------:|
| Version 0.2 |   Added funding and update table.                                                                                                          | 2024 May 22          |


## Sources of funding

- NIH: R01 CA242845
- NIH: R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel)
- NIH: P20 GM103640 and P30 GM145423 (PI: A. West)
