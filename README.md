# Ishan Translator

Simple nodejs library for talking to Google's Translate API.

## Usage

Install package

```node
npm install ishan-Translator
```

### Import module

```js
const ishanTranslator = require("ishan-Translator");
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
