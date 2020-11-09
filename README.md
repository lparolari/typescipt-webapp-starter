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

## License

The project is MIT licensed. See [LICENSE](LICENSE) file.

## References

\[^1\]: [https://it.wikipedia.org/wiki/Node.js](https://it.wikipedia.org/wiki/Node.js) \
\[^2\]: [https://it.wikipedia.org/wiki/Npm\_(software)](<https://it.wikipedia.org/wiki/Npm_(software)>)
