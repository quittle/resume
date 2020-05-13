# Welcome to Dustin Toff's Resume [![Build Status](https://travis-ci.com/quittle/resume.svg?branch=master)](https://travis-ci.com/quittle/resume)

[<img alt="PDF" src="/pdf-icon.svg" height="12px"/> Click here](https://resume.dustintoff.com) for the latest copy of my resume!

### Developing

This resume is written in LaTeX and builds with xelatex.

```bash
# Install required system packages
sudo apt-get install -y \
    aspell-en \
    chktex \
    hunspell \
    lmodern \
    poppler-utils \
    texlive-font-utils \
    texlive-fonts-recommended \
    texlive-latex-base \
    texlive-latex-extra \
    texlive-xetex \
    xzdec \
    python3-pip

pip3 install pdfx

# Open a new terminal so pdfx is available

# Build the resume
./build

# Perform additional checks and linting
./check
```
