# ESLint Typescript Node

A boilerplate for starting a [NodeJS](https://nodejs.org/en/) project using [Typescript](https://www.typescriptlang.org/) and [ESLint](https://eslint.org/)

## How to use

- Clone this repository

- Install dependencies

```bash
npm install
```

- Run the project

```bash
npm run dev
```

- compile typescript to javascript

```bash
npm run build
```

- run javascript in production

```bash
npm start
```

## Tips - How to initialize a new project

- `npm init -y`
- `tsc --init`
- `npm init @eslint/config`
- `npm i --save-dev eslint typescript ts-node nodemon @types/node @types/express @typescript-eslint/eslint-plugin @typescript-eslint/parser`
  _NOTE: Install only the packages you need (e.g. if you don't need express, don't install @types/express)_

## Installed packages

- dev dependencies

```bash
eslint typescript ts-node nodemon @types/node @types/express @typescript-eslint/eslint-plugin @typescript-eslint/parser
```

- dependencies

```bash
express
```

## Scripts

- dev `nodemon index.ts` - run the project in development mode
- watch `tsc -w` - watch for changes in typescript files and compile to javascript
- build `tsc` - compile typescript to javascript
- start `node dist/index.js` - run the javascript file in production

## Typescript configuration

- `target` : Specify ECMAScript target version: 'es5', 'es6', 'es2016', 'es2020', or 'ESNext'.
- `module` : Specify module code generation: 'commonjs', 'es6', 'es2020', or 'ESNext'.
- `outDir` : Redirect output structure to the directory.
- `rootDir` : Specify the root directory of input files. Use to control the output directory structure with --outDir.

## ESLint configuration

- `parser` : The parser that will be used to analyze your source code. [docs](https://eslint.org/docs/latest/user-guide/configuring/plugins)
- `parserOptions` : An object containing additional options related to the parser.
- `extends` : An array of configurations to extend.
- `rules` : An object containing the rules that you want to use. [docs](https://eslint.org/docs/latest/rules/)

## Author

[Emanuele Favero](https://emanuelefavero.com/)
