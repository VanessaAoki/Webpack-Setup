<p align="center">
  <a href="https://www.microverse.org/">
    <img alt="Microverse" src="https://img.shields.io/badge/-Microverse-blueviolet?style=flat-square">
  </a>
  <a href="https://github.com/VanessaAoki/Webpack-Setup/blob/main/LICENSE">
    <img alt="MIT Licensed" src="https://img.shields.io/github/license/VanessaAoki/Webpack-Setup?style=flat-square">
  </a>
  <a href="https://github.com/VanessaAoki/Webpack-Setup">
    <img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/VanessaAoki/Webpack-Setup/main?color=blue&style=flat-square">
  </a>
  <a href="https://github.com/VanessaAoki/Webpack-Setup">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/VanessaAoki/Webpack-Setup?color=pink&label=%E2%98%85%20stars%20&style=flat-square">
  </a>
  <a href="https://github.com/VanessaAoki">
    <img alt="GitHub followers" src="https://img.shields.io/github/followers/VanessaAoki?color=yellow&logo=github&style=flat-square">
  </a>
</p>

# Webpack-Setup

This repository is a starting point for JavaScripts projects, according to Microverse standards.

## Getting Started

After creating a directory, cd into it, initialize npm, install webpack locally, and install the webpack-cli (the tool used to run webpack on the command line):
```sh
npm init -y
npm install webpack webpack-cli --save-dev
```

To set ut the HTMLWebpackPlugin, adjust the webpack.config.js file and run `$ npm install --save-dev html-webpack-plugin`.

After that, in order to import a CSS file from a JS module, you need to install and add the style-loader and css-loader to your module configuration. To do that, run `$ npm install --save-dev style-loader css-loader` and add the module rule in your webpack.config.js.

Lastly, to set up a live server, run `$ npm install --save-dev webpack-dev-server` and confire devServer at the webpack configuration file.

## Author

👩🏼‍💻 **Vanessa Aoki**

- GitHub: [@VanessaAoki](https://github.com/VanessaAoki)
- Twitter: [@VanessaSAoki](https://twitter.com/VanessaSAoki)
- Linkedin: [Vanessa Aoki](https://www.linkedin.com/in/vanessasaoki/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/VanessaAoki/Webpack-Setup/issues).

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [MIT](./LICENSE) licensed.
