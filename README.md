# keycodes

[![GPR](https://img.shields.io/github/release/afractal/keycodes.svg?label=GPR&logo=github)](https://github.com/afractal/keycodes/packages/28631)

Javascript DOM event key codes map.


## Install

Setup the **.yarnrc** file:

```bash
"@afractal:registry" "https://npm.pkg.github.com"
```

Setup the **.npmrc** file:

```bash
@afractal:registry=https://npm.pkg.github.com
```

Add the definition inside **package.json**:

```json
"dependencies": {
    "@afractal/keycodes": "<version>"
}
```

Install the package with **yarn**:

```bash
yarn install
```

## Usage

```typescript
import keycodes from "@afractal/keycodes";

const enterCode = keycodes["enter"];
const enterCode = keycodes.enter;
// both return 13
```

## License

This product is licensed under ther [MIT](./LICENSE.md) license.

---

<p align="center">
    made with :heart: by <a href="https://github.com/afractal">me</a>
</p>
