# TCStringParse

Simple parser for transparency and consent strings compatible with TCF2.0.

## Installation

`npm install tc-string-parse`

## Usage

### NodeJS

```js
const TCStringParse = require('tc-string-parse');

const consentString = ''; // your consent string
TCStringParse(consentString);
```

### Browser

```html
<script src="path/to/tc-string-parse.js"></script>

<script>
  const consentString = ''; // your consent string
  TCStringParse(consentString);
</script>
```