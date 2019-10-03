# Welcome to Dustin Toff's Resume [![Build Status](https://travis-ci.com/quittle/resume.svg?branch=master)](https://travis-ci.com/quittle/resume)

[Click here](https://github.com/quittle/resume/releases/latest/download/Dustin.Toff.Resume.pdf) for the latest copy of my resume!

### Developing

This resume is written in LaTeX and builds with xelatex.

```bash
# Install required system packages
sudo apt-get install -y \
    chktex \
    hunspell \
    lmodern \
    texlive-font-utils \
    texlive-fonts-recommended \
    texlive-latex-base \
    texlive-latex-extra \
    texlive-xetex \
    xzdec

pip install pdfx

# Build the resume
./build

# Perform additional checks and linting
./check
```
