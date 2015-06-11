# Interactive Things ESLint Config

## Usage

```shell
npm install eslint-config-interactivethings --save-dev
```

In your project's `.eslintrc`:

```json
{
  "extends": "interactivethings"
}
```

Override any rules which don't fit your project.

## Differences to AirBnB config

- JSX single quotes
- Capitalized functions don't need to be used with `new`. E.g. `const foo = Immutable.Map();` should be allowed.

## Development

- Create single commits for each rule change, and describe the reason for the change in the commit message (*why* not just *what*).
- List any deviations from AirBnB's style in this README
- Create a new version using `npm version x.x.x`
