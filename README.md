# setup_doc
A Bash script to set up a Markdown writing environment with CSS styling and easy PDF conversion. Perfect for creating polished documents with custom looks.

## Features
- Creates project folder with sample Markdown, CSS, and Makefile
- Custom project naming (e.g., `setup_doc mydoc`)
- Generates CSS template with default styles
- PDF conversion with make (using pandoc and Chrome)

## Usage
### Create project in current directory with default name
    `setup_doc`
### Create project in current directory with custom name
    `setup_doc custom_name`
### Generate project pdf
    `cd custom_name
     make`

## Installation (MacOS)
1. Download the file "setup_doc"
2. Create folder "~/bin" if it does not already exist
    `mkdir ~/bin`
3. Navigate to the downloads folder
    `cd ~/Downloads`
4. Move file to folder "~/bin"
    `mv setup_doc ~/bin/`
5. Create file "~/.zshrc" if it does not already exist
    `touch ~/.zshrc`
6. Add setup_doc path to "~/.zshrc"
    `export PATH="$HOME/bin:$PATH"`
7. Save the added command
    `source ~/.zshtc`
