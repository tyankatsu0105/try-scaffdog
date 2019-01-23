---
name: 'hello'
description: 'hello of description'
message: 'Please enter any text.'
root: 'src'
output: '**/*'
ignore: []
---

# `{{ input }}.js`

```javascript
export const {{ input | camel }} = () => true;
```