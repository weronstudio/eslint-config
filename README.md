# Weron ESLint config

## Whats included?

- Standard base configuration;
- React and React Hooks plugins;
- JSX a11y for accessibility;
- Prettier integration;
- Next.js support;
- Node.js support.

## Installation

Install dependencies:

```
npm i -D eslint @weron/eslint-config
```

## Usage

### React (with Next.js)

For Next.js projects, extend the configuration with Next.js-specific settings.

In your `.eslintrc.json`

```
{
  "extends": "@weron/eslint-config/next"
}
```

### React (without Next.js)

For React projects without Next.js, extend the configuration as follows:

In your `.eslintrc.json`

```
{
  "extends": "@weron/eslint-config/react"
}
```

### Node.js

For Node.js projects, extend the configuration like this:

In your `.eslintrc.json`

```
{
  "extends": "@weron/eslint-config/node"
}
```
