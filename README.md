# ESLint config

> This project is a fork of [@rocketseat/eslint-config](https://github.com/Rocketseat/eslint-config-rocketseat)

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:
```
npm i -D eslint @emanueltavecia/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@emanueltavecia/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint @emanueltavecia/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@emanueltavecia/eslint-config/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint @emanueltavecia/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@emanueltavecia/eslint-config/node"
}
```
