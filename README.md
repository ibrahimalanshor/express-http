# Express HTTP

## Install

```bash
npm install @ibrahimanshor/express-http
```

## Usage

### Exceptions

```js
const { Exception, Response } = require('@ibrahimanshor/express-http');

new Exception.BadRequestException('bad request', {
  detail: 'requiest invalid',
});
new Response.CreatedResponse('user created', { id: 1 }).use(res);
```
