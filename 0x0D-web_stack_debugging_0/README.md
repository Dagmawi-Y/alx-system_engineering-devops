# 0x0D. Web stack debugging #0

## Description
The Webstack debugging series will train you in the art of debugging. Computers and software rarely work the way we want (that’s the “fun” part of the job!).

Being able to debug a webstack is essential for a Full-Stack Software Engineer, and it takes practice to master it.

In this debugging series, broken/bugged webstacks will be given to you, the final goal is to come up with a Bash script that once executed, will bring the webstack to a working state. But before writing this Bash script, you should figure out what is going on and fix it manually.

## Project Requirements
- Allowed editors: vi, vim, emacs
- All your files will be interpreted on Ubuntu 14.04 LTS
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- Your Bash scripts must pass Shellcheck without any error
- Your Bash scripts must run without error
- The first line of all your Bash scripts should be exactly `#!/usr/bin/env bash`
- The second line of all your Bash scripts should be a comment explaining what the script is doing

## Concepts
For this project, we expect you to look at these concepts:
- Network basics
- Docker
- Web stack debugging

## Resources
- [man or help: curl](https://curl.se/docs/manpage.html)
- [Docker](https://www.docker.com/)

## Tasks

### 0. Give me a page!
Be sure to read the Docker concept page.

In this first debugging project, you will need to get Apache to run on the container and to return a page containing `Hello Holberton` when querying the root of it.