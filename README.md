# Interactive Things ESLint Config

We (mostly) structure and lint our JS code according to [AirBnB's JavaScript styleguide](https://github.com/airbnb/javascript). Exceptions are noted below.

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
- Allows the `__DEV__` global

## Development

- Create single commits for each rule change, and describe the reason for the change in the commit message (*why* not just *what*).
- List any deviations from AirBnB's style in this README
- Create a new version using `npm version x.x.x`
