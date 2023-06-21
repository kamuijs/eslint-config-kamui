# eslint-config-kamui

## Install

```sh
npx install-peerdeps --dev eslint-config-kamui
```

## Usage

In your `.eslintrc.js`:

```tsx
module.exports = {
  extends: ['kamui'],
  parserOptions: {
    project: './tsconfig.json',
  },
};
```

## License

MIT
