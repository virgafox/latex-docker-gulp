# latex-docker-gulp
Autocompile LaTex to PDF using gulp and Docker.

## Requirements
- NodeJS
- Docker

## Installation
1. Download this repository and move into the directory;
2. Download the image with `docker pull virgafox/texlive`;
3. Install the dependencies with `npm install` and wait it to finish.

## Usage
1. Start the daemon with `npm run latex` and leave the terminal open;
2. Wait few seconds and check the content of the freshly created `main.pdf` file;
3. Modify the `main.tex` file and save;
4. Wait few seconds and check `main.pdf` again. Ta-Da!
