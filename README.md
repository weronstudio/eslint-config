# Weron ESLint config

## What's included?

- Standard base configuration;
- React and React Hooks plugins;
- JSX a11y for accessibility;
- Prettier integration;
- Next.js support;
- Node.js support.

## Installation

Install dependencies:

```
npm i -D @weron/eslint-config
```

## Usage

Add the appropriate configuration to your `.eslintrc.json` based on the project type:

### React (with Next.js)

```
{
  "extends": "@weron/eslint-config/next"
}
```

### React (without Next.js)

```
{
  "extends": "@weron/eslint-config/react"
}
```

### Node.js

```
{
  "extends": "@weron/eslint-config/node"
}
```
