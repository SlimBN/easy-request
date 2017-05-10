# easy-request

Simple HTTP POST requester.

## Example of use

```
    $ npm i easy-request --save
```

After install:

```
    /* jshint esversion: 6 */

    const post = require('easy-request').post;

    post('http://someurl',{someParameter:'someValue'})
        .then((body) => {
            console.log(body);
        })
        .catch((err) => {
            console.error(err);
        });

```
