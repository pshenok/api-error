Install:

```sh
$ npm i api-error-class
```


Example create and return error:

```js
const APIError = require("api-error-class");


const someController = (req, res) => {
    //...some kind of functional
    throw new APIError("Message", 401);
};
    

```
