# klasa-member for v12

## Setup

```js
const { Client } = require('klasa');

Client.use(require('klasa-member'));

// Modifying the Schema
Client.defaultMemberSchema
    .add('experience', 'integer', { default: 0 })
    .add('level', 'integer', { default: 0 });
```
