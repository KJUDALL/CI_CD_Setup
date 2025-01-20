# GitHub Actions CI/CD Setup

## Description

In such a fast paced and every-changing world, it's important to utilize automation tools whenever possible. Not only do these workflows improve functionality but they also provide room for scalability and overall app cohesion. "Think smarter, not harder" as a wise person once said. GitHub Actions is a perfect example of utiltizing your resources to create an Agile Development workflow; one that is continuous and responsive; in other words, CI/CD pipeline creation.

This project will hone in on the capabilites of GitHub Actions (GA) in automating a workflow, post-PR. The idea is that once a pull request is made to the develop branch, the component tests will be triggered and ran in Cypress. From there, GA will also help create a pipeline to deploy the application to Render anytime code is merged from the develop branch to the main branch. This two-step process is meant to free up an engineer's time, allowing more opportunities to create and develop seamless code, rather than wasting time worrying about deployment and testing processes in the interim; to speed up the deployment process and allow each individual, coder and client-alike, the ability to focus on their strengths and reduce overall context-switching.

## Table of Contents

- [Description](#description)
- [Deployment Link](#deployment)
- [Installation](#installation)
- [License](#license)
- [Questions](#questions)

## Deployment Link

This app is being deployed publicly via Render. If you would like to simply view the functionality of the app without building it locally, you can do so at this link:

## Installation

Users can clone this code repo using an IDE of choice. They must ensure bcrypt, dotenv, express, jsonwebtoken, pg, sequelize and npm are all installed. Because this code base uses TypeScript, be mindful of npm scripts used to run and build the app in the package.json file. Npm install is needed, but it should be noted that npm run render-build will have additional functionality, aside from simply performing an npm install. Upon doing so, the user should be redirected to a live localhost deployment. This app will also be deployed via Render.

It should be noted that I was given starter code by means of the school. From there, I completed the necessary refactors to ensure seamless config with GitHub Actions to run the provided Cypress tests.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

    This project is licensed under the MIT license. For more info, see [this link](https://opensource.org/licenses/MIT).

## Questions

If any questions come up in the future, you can contact me directly at myemail@gmail.com. If you would like to view this repo, or check out any of my other work, visit my GitHub at [kjudall](https://github.com/kjudall/).
