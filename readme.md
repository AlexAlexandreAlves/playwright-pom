# Project Resume

In this project, I'll show you how we can use an architecture with Page Object Model and playwright to simplify to run your ui tests!

## Table of Contents

- [Project Resume](#project-resume)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [How to contribute](#how-to-contribute)
  - [Contribution guidelines](#contribution-guidelines)
  - [Contact](#contact)


## Installation

Run to install and use the project:

`npm install`

If you wanna install a new project you can run the command and answer the questions:

`npm init playwright@latest`

## Usage

After you install the depencencies you can use the commands to run the tests:

To run all tests in headless

`npx playwright test`

To run on web page

`npx playwright test --ui`

To run setting a kind of webdriver

`npx playwright test --project=chromium`
    
To run only a selected test

`npx playwright test example`

To run the tests in debug mode

`npx playwright test --debug`

To use the auto generator tests or to use the element selector run

`npx playwright codegen`


## How to contribute
1. Fork the project
2. Create a branch for your contribution: git checkout -b feature/your-feature
3. Make your changes and commit: git commit -m 'Add amazing feature'
4. Push to your fork: git push origin feature/your-feature
5. Open a Pull Request to the main branch of the project

## Contribution guidelines

   - Add new tests
   - Follow the existing code style

## Contact

If you're interested in finding out more, don't hesitate to contact me via linkedin!

www.linkedin.com/in/alexalexandrealves 