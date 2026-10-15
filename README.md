## Welcome to GitHub Games

A project based learning activity for people who are getting started with Git and GitHub.

You can play the game at: https://githubschool.github.io/github-games/

>> _*SUPPORTED BROWSERS*: Chrome, Firefox, Safari, Opera and IE9+_

This fun open source game was cloned from: https://github.com/jakesgordon/javascript-tetris

## Running locally

The local server uses Docker Compose. With Docker Desktop running, execute
`script/server` from Git Bash, or `bash script/server` if the script is not
executable. The script supports both the current `docker compose` command and
the legacy `docker-compose` executable.

To run the smoke test, use `script/test` (or `bash script/test`). It starts the
same server without creating a symbolic link, so it also works on Windows
without enabling symbolic-link privileges.
