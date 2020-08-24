# klasa-member dv12

[![Build Status](https://dev.azure.com/dirigeants/klasa/_apis/build/status/dirigeants.klasa-member-gateway?branchName=master)](https://dev.azure.com/dirigeants/klasa/_build/latest?definitionId=3&branchName=master)

## Setup

```js
const { Client } = require('klasa');

Client.use(require('klasa-member-gateway'));

// Modifying the Schema
Client.defaultMemberSchema
    .add('experience', 'integer', { default: 0 })
    .add('level', 'integer', { default: 0 });
```
