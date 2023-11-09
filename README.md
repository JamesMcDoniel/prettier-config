# prettier-config

My personal Prettier configuration

## Installation

Install the package as a dev dependency:

```
npm install --save-dev @jamesmcdoniel/prettier-config
```

<br />

You can install the required peer dependencies using the following:

```
npm install --save-dev prettier
```

<br />

or, if you use `install-peerdeps`, you can use the following command:

```
npx install-peerdeps --dev @jamesmcdoniel/prettier-config
```

## Usage

There are a few options to apply this configuration:

<br />

Add a `"prettier":` property to your `package.json` file:

```json
{
  "prettier": "@jamesmcdoniel/prettier-config"
}
```

<br />

or, in a `.prettierrc.*` file, export `'@jamesmcdoniel/prettier-config'` as a string:

<br />

`.prettierrc.json`

```json
"@jamesmcdoniel"
```

<br />

`.prettierrc.js`

```javascript
module.exports = '@jamesmcdoniel/prettier-config';
```
