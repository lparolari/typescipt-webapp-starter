# Typescript Web Application Starter

A starter package for building web application in zero time and no configs.

## Install

### Requirements

You need to install following components in your system.

- [nodejs](https://nodejs.org) \[^1\]
- [yarn](https://yarnpkg.com/) or [npm](https://www.npmjs.com/) \[^2\]

### Download

Download the [package zip](https://github.com/lparolari/typescript-webapp-starter/archive/master.zip) or, if you use git, run the following commands:

```bash
git clone https://github.com/lparolari/typescript-webapp-starter.git
cd typescript-webapp-starter
rm -rf .git
```

### Install dependencies

```
yarn

# or, with npm
npm install
```

## Usage

### Start local server

Run a local web server (default at http://localhost:1234) with

```bash
yarn start
```

### Bundle the application

You can also create a bundle for the application:

```bash
yarn build
```

### Run tests

You can run your unit tests with:

```bash
yarn test
```

## About

The package use **parcel** in order to bundle and build the application, **jest** for unit testing and it integrates _typescript_ out-of-the-box.

[index.html](index.html): You can edit this file in order to change the web interface of your application. Add here HTML components with an _id_ and use it with JavaScript/TypeScript to make your page interactive.

[src](src): You can add your own source code in the `src` directory: write new functions and new modules. Export your modules through _index.ts_.

[tests](src/__tests__): You can add your own tests in the `src/__tests__` directory. Remember that you have to import from `src` the functions you need to test. Remember that we are using [jest](https://jestjs.io/) for unit testing.

## License

The project is MIT licensed. See [LICENSE](LICENSE) file.

## References

\[^1\]: [https://it.wikipedia.org/wiki/Node.js](https://it.wikipedia.org/wiki/Node.js) \
\[^2\]: [https://it.wikipedia.org/wiki/Npm\_(software)](<https://it.wikipedia.org/wiki/Npm_(software)>)
