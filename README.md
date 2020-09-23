# Research Transparency & Reproducibility Training (RT2)
Materials for workshop on research transparency, Remote 2020

UC Berkeley ([Berkeley Initative for Transparency in the Social Sciences](http://www.bitss.org))


## Installation Instructions
The workshop will introduce you to a tool that can help you make your workflow more reproducible: version control (Git/GitHub). You are required to install the following software programs either on your personal laptop before coming to the workshop for the hands-on exercises. (please remember to bring the laptop too!)

### 1. Version Control with Git and the Github Desktop app

Version control is a powerful way to carefully track revisions to your documents as well as to manage collaboration. Git and Github Desktop are packaged together [here](https://desktop.github.com/). Git is the command line tool, and Github Desktop is a GUI version of the same tool.

There are actually [a whole bunch of GUI apps](https://git-scm.com/downloads/guis) that can act as front ends, so you might find later that you prefer another, but we'll stick with Github Desktop for the demo.


### 2. A good text editor

Writing good code is facilitated by a good text editor. You can get away without one because you almost certainly already have a program on your computer that can save simple ASCII text files (Notepad for Windows, or TextEdit for Mac--but change the default from Rich Text to Plain Text) but modern text editors do syntax highlighting, auto-complete, and a bunch of other cool stuff for you. I suggest [Atom](http://atom.io). You can extend its functionality by going to settings and adding packages (one to render Markdown as PDF might be especially helpful.)  


### 3. Install R and RStudio  
- [R](https://cloud.r-project.org/)  
- [RStudio](https://www.rstudio.com/products/rstudio/download/#download)

If you have downloaded R or RStudio, make sure that your version is up to date.

Open RStudio and click on the following `File-> New File -> RMarkdown...`, when prompted to install additional packages, click **yes**.  

### 4. Install LaTeX
If you could not install LaTeX previously, run the following 2 lines of code in the RStudio console:  

`install.packages(c("tinytex", "rmarkdown"))`  
`tinytex::install_tinytex()`


### 5. Materials
  - Folder `01-git-gui` contains the slides for the git/github tutorial  
  - Folder `02-dyndocs` contains the slides for the dynamic documents tutorial with R  
  - File `handout.pdf` contains some short descriptions of the terminology used in git/github
