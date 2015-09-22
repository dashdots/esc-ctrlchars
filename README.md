# esc-ctrlchars
Escape control characters.

```javascript
const escape = require('esc-ctrlchars')
escape("< + - * \\ = >") // => "&lt; \\+ \\- \\* \\\\ \= &gt;"
```

es6 example:
```javascript
import escape from 'esc-ctrlchars';
escape`< + - * \ = >` // => "&lt; \\+ \\- \\* \\\\ \= &gt;"
```
