# Welcome to Dustin Toff's Resume [![Build Status](https://github.com/quittle/resume/actions/workflows/action.yml/badge.svg)](https://github.com/quittle/resume/actions/workflows/action.yml)

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

# Install AWS CLI - https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
(
    cd ~/Downloads
    curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
    unzip awscliv2.zip
    sudo ./aws/install
)

# Open a new terminal so pdfx is available

# Build the resume
./build

# Perform additional checks and linting
./check
```
