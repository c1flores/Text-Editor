# Table of Contents

  - [Overview](#overview)
  - [What is a progressive web application?](#what-is-a-progressive-web-application)
  - [Screen Capture](#screen-capture)
  - [Deployed Application](#deployed-application)
  - [Installation](#installation)
  - [Usage](#usage)
  
## Overview
 This repository is an exhibition of a progressive web application that runs in the browser and works  offline. Users can install the browser-based text editor on their device to create code snippets at a moment's notice. The project makes use of <a href="https://nodejs.org/en/" target="_blank">Node.js</a> to work with a back end, the <a href="https://www.npmjs.com/package/express" target="_blank">Express</a> package to design and configure an API, and a set of <a href="https://webpack.js.org/" target="_blank">Webpack</a> dependencies to effectively transform the browser-based application into a progressive web app. 

## What is a progressive web application?
Progressive Web Applications (PWAs) are apps built with web technologies that we all know and love, like HTML, CSS, and JavaScript while owning the feel and functionality of a native application. PWAs takes advantage of the huge web ecosystem, this is inclusive of plugins, to offer a comparable experience to native apps. 

Characteristics of a progressive web app include:
  - Responsiveness to different screen sizes.
  - Installable on home screen as an alternative to native web apps or official websites.
  - Independent connectivity for offline functionality. 

Many companies have shifted into the product because of its ability to run on an android and iOS without much difference. Some good examples of top companies who have their products as PWAs include: Twitter, Pinterest, Uber, Tiktok, and Spotify.

## Screen Capture
![](https://user-images.githubusercontent.com/81927296/208821242-1cb0c481-b523-4bfa-91af-caba375be601.gif)

## Deployed Application
[Heroku Link](https://jate-text-editrr.herokuapp.com/)

## Installation

  1. Fork and clone repository to local machine.
  2. Run ```npm i``` to install dependencies in local project directory. 
  3. Run ```npm install --save-dev webpack``` to install Webpack. 

  
## Usage

  1. Use application through the deployed link above.
  2. Run ```npm run start:dev``` to initiate webpack build and start server on local port. 
  3. For offline use, user can go to the link and click the "install" button to open the web application on home screen. 
