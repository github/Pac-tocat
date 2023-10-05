# Pac-tocat
[![Code Style](https://img.shields.io/badge/code%20style-airbnb-brightgreen.svg)](https://github.com/airbnb/javascript)

🕹Play Pac-Man starring [Mona](https://github.com/monatheoctocat), the loveable GitHub octocat mascot using Javascript, HTML, and CSS. 

🙌 Forked from [bward2/pacman-js](https://github.com/bward2/pacman-js) 

<a href='https://codespaces.new/github/Pac-tocat?quickstart=1'><img src='https://github.com/codespaces/badge.svg' alt='Open in GitHub Codespaces' style='max-width: 100%;'></a>

When opening the project in a codespace with supported editors, the project will be run by default via the [devcontainer's postAttach commands](https://github.com/github/Pac-tocat/blob/master/.devcontainer/devcontainer.json#L16).

## Local Development Instructions

This project makes use of *__[NodeJS](https://nodejs.org/en/)__*. Download it, then clone this repo and run the following commands:  
1. `npm i` (Installs necessary packages for development)
1. `gulp watch` (Watches changes to JS and SCSS files for continuous compilation)
1. `npx run serve` (Hosts the files locally)

The game can now be accessed at *__http://127.0.0.1:8080/index__*

This project also utilizes *__[Husky](https://github.com/typicode/husky)__* to enforce best coding practices. The current thresholds are 0 linting errors upon commits (following Airbnb's standard), and 100% unit test code coverage upon pushes.

Feel free to submit PRs and/or report any issues you find! 😃
