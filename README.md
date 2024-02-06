This package converts unicode text to preeti and vice-versa. This is a simple package with only two functions convertToPreeti and convertToUnicode.

```bash
npm install @ankur700/nepali-text-conversion
```

## Functions

### convertToPreeti()

This functions takes one argument of type Unicode string  which get processed and returns the string value as preeti text .

```jsx
import {convertToPreeti} from 'nepali-text-conversion';

const unicode_text = "हेल्लो";
const preeti_text = convertToPreeti(unicode_text);
console.log(preeti_text); // हेल्लो
```

### convertToUnicode()

This functions takes one argument of type string i.e Preeti, which get evaluated and returns the string value as unicode text .

```jsx
import {convertToPreeti} from 'nepali-text-conversion';

const preeti_text = "हेल्लो";
const unicode_text = convertToUnicode(preeti_text);
console.log(preeti_text); // हेल्लो
```