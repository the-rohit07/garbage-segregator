<p align="center">
  <a href="https://trashier.appspot.com">
    <img width="200" src="images/trashier-logo.png">
  </a>
</p>

<h1 align="center">Trash Classifier</h1>
<div align="center">
A web-app that classifies your trash to its appropriate category and provides you with information on proper waste disposal. Written in NodeJS, HTML, CSS and Javascript. 

[![Testing](https://github.com/markgacoka/TrashClassifier/blob/master/images/badge.svg)](https://github.com/markgacoka/TrashClassifier/issues)
[![Build Passing](https://github.com/markgacoka/TrashClassifier/blob/master/images/build.svg)](https://trashier.appspot.com)
[![NPM downloads](https://github.com/markgacoka/TrashClassifier/blob/master/images/npm.svg)](https://docs.npmjs.com/)

</div>

[![Features](https://github.com/markgacoka/TrashClassifier/blob/master/images/features.png)](http://trashier.appspot.com/)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on localhost. You can also check out the website [here](http://trashier.appspot.com/). If that does not work, you can check the layout without API calls to Houndify API [here](https://treehacks.netlify.com/).

### Prerequisites

What things you need to install the software and how to install them:
* npm
* git
* express-js

### Installing

To install the files to your computer, use git to clone the repository

[![Tutorial Video](https://github.com/markgacoka/TrashClassifier/blob/master/images/git-clone.gif)](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)


#### For Windows
Download [Git for Windows](https://gitforwindows.org/) if you don't have one already.

```
git --version
git config --global user.name "YOUR-NAME"
git config --global user.email "YOUR-EMAIL"
cd Desktop/
git clone https://github.com/markgacoka/TrashClassifier.git
```

#### For Mac
Use the first code to check if you have it installed.

```
git --version
git config --global user.name "YOUR-NAME"
git config --global user.email "YOUR-EMAIL"
brew install git
mkdir TrashClassifier/
git clone https://github.com/markgacoka/TrashClassifier
```

## Running the tests

Once downloaded to your local machine, you can go into the directory and test out the index file on your browser.

```
cd TrashClassifier/
index.html
```

## Deployment

However, the website is hosted by a nodeJS server and to do this you need to install npm.
1. Check if a nodeJS and npm are installed

```
node -v
npm -v
```

2. Install the latest version of npm and install expressJS using npm
```
npm install npm@latest -g
npm init
npm install express --save
node server.js
```

## Demo

[![Classification](https://raw.githubusercontent.com/markgacoka/TrashClassifier/master/images/paper.png)](https://raw.githubusercontent.com/markgacoka/TrashClassifier/master/images/paper.png)


[![Node Server](https://github.com/markgacoka/TrashClassifier/blob/master/images/node-server.gif)](https://deploybot.com/blog/guest-post-how-to-set-up-and-deploy-nodejs-express-application-for-production)

## Built With

* [Teachable Machine by Google](https://teachablemachine.withgoogle.com/)
* [Google Cloud Storage Services](https://cloud.google.com/gcp/getting-started)
* [NodeJS](https://nodejs.org/en/docs/)
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [HTML & CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Versioning

This is the alpha version for the project. V 1.0.0.
To see Trung's version of the project during the hackathon, [click here](https://treehacks-trashier.appspot.com/).

## Authors
<table>
  <tr>
    <td align="center"><a href="https://github.com/markgacoka"><img src="https://avatars2.githubusercontent.com/u/23658445?s=460&v=4" width="100px;" alt=""/><br /><sub><b>Gacoka Mbui</b></sub></a><br /><a href="https://github.com/markgacoka/SafePath" title="Backend and Documentation">📖💻🤔</a></td>
    <td align="center"><a href="https://github.com/Nguyen-ATrung"><img src="https://avatars2.githubusercontent.com/u/55957585?s=460&v=4" width="100px;" alt=""/><br /><sub><b>Trung Nguyen</b></sub></a><br /><a href="https://github.com/Nguyen-ATrung/Treehacks" title="Front End, Marketing and Design">🐛🎨💻</a></td>
  </tr>
</table>

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- **[Creative Commons Attribution 3.0 License - (CC BY 3.0)](https://colorlib.com/wp/template/imagine/)**

## Acknowledgments
* TreeHacks Judges for the feedback on the code and the overall project.
* TreeHacks mentors for helping us when stuck.

Submitted to [TreeHacks 2020](https://devpost.com/software/trashier) at Stanford.

