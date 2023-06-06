
<a name="readme-top"></a>
<div align="center">
  <br/>
  <h2><b>Set up Webpack tool</b></h2>
</div>

# 📗 Table of Contents

- [📗 Table of Contents](#-table-of-contents)
- [Set up Webpack tool ](#set-up-webpack-tool-)
  - [🛠 Built With ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
    - [Key Features ](#key-features-)
  - [💻 Getting Started ](#-getting-started-)
    - [Setup](#setup)
    - [Prerequisites](#prerequisites)
    - [Install](#install)
    - [Usage](#usage)
  - [👥 Authors ](#-authors-)
  - [🔭 Future Features ](#-future-features-)
  - [🤝 Contributing ](#-contributing-)
  - [⭐️ Show your support ](#️-show-your-support-)
  - [🙏 Acknowledgments ](#-acknowledgments-)
  - [📝 License ](#-license-)

# Set up Webpack tool <a name="about-project"></a>

**Set up Webpack tool** is a project that consists of creating a repository template with all the necessary configuration to work with webpack and HTML, CSS and Javascript.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://webhint.io/">Webhint.io</a></li>
    <li><a href="https://stylelint.io/">Stylelint.io</a></li>
    <li><a href="https://eslint.org/">ESlint.org</a></li>
    <li><a href="https://nodejs.org">Node.js</a></li>
    <li><a href="https://webpack.js.org">Webpack</a></li>
  </ul>
</details>

### Key Features <a name="key-features"></a>

- **Webpack setup**
- **Webpack dev server to reload the page automatically**
- **HTML File generated automatically**
- **CSS Styles loaded automatically with Javascript**


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Setup

Clone this repository to your desired folder:

```sh
  cd my-folder-name
  git clone git@github.com:NitBravoA92/setup-project-webpack.git
```

### Prerequisites
In order to install, modify and run this project, it is necessary to have the following applications installed:
- **Git:** to manage the project versions of source code. [You can Download Git here](https://git-scm.com/)
- **Nodejs and NPM:** to install and manage the project dependencies. [Nodejs and NPM installation guide](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
- **A code editor** like Visual Studio Code (Recommended) or any other of your preference. It is necessary to open the project and add or modify the source code. [You can Download Visual Studio Code here](https://code.visualstudio.com/)

It is also important to have at least basic knowledge of HTML, CSS and Javascript languages, so you will be able to understand and work with the html and css code of the project. 
- [Learn the basics of HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [Learn the basics of CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)
- [Webpack - Getting Started](https://webpack.js.org/guides/getting-started/)


### Install

Install this project by running the next command into your project folder:

```sh
  npm install
```

### Usage

First, open the HTML, CSS or Javascript files and modify the internal code, then run the following command:

HTML Linter
```sh
  npm start .
```

CSS Linter
```sh
  npx stylelint "**/*.{css,scss}"
```

Javascript Linter
```sh
  npx eslint .
```

This will show you a log with details about errors (if any) and changes that would be necessary to solve those errors and improve the code.

**Note**: Please only modify the HTML, CSS and Javascript files. Do not modify the configuration files of the project.

After reviewing your code with the linters, start the application following the below command:

```sh
  npm start
```
You only need to run this command once. If you keep making changes to the files, the installed webpack server will reload the page so you can see the changes immediately.

## 👥 Authors <a name="authors"></a>

👤 **Nitcelis Bravo**

- GitHub: [Nitcelis Bravo](https://github.com/NitBravoA92)
- Twitter: [@softwareDevOne](https://twitter.com/softwareDevOne)
- LinkedIn: [Nitcelis Bravo Alcala](https://www.linkedin.com/in/nitcelis-bravo-alcala-b65340158)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🔭 Future Features <a name="future-features"></a>

- [ ] **Install and set up other webpack loaders to support other technologies**


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, suggestions and feature requests are welcome!
Feel free to check the [issues page](../../issues/).

To do Contributions, please fork this repository, create a new branch and then create a Pull Request from your branch. You can find detailed description of this process in: [A Step by Step Guide to Making Your First GitHub Contribution by Brandon Morelli](https://codeburst.io/a-step-by-step-guide-to-making-your-first-github-contribution-5302260a2940)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⭐️ Show your support <a name="support"></a>

If you liked this project, give me a "Star" (clicking the star button at the beginning of this page), share this repo with your developer community or make your contributions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thank my Microverse teammates for their support. They have supported me a lot in carrying out this project, giving me suggestions, good advice and solving my code doubts.


## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>