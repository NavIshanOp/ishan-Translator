# Ishan Translator

Simple nodejs library for talking to Google's Translate API.

## Usage

Install package

```node
npm i @navishanop/ishan-translator
```

### Import module

```js
const ishanTranslator = require("@navishanop/ishan-translator");
```

#### Example

```js
(async () => {
  try {
    const source = "es";
    const target = "en";
    const text = "buenos días";
    const translation = await ishanTranslator.translate(source, target, text);
    console.log(translation);
  } catch (error) {
    console.error(error);
  }
})();
```
