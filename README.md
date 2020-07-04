# js-toastr

A lightweight javascript toast library with no dependencies and 1 KB Size.

[Demo](https://rabhinav77.github.io/js-toastr/) 


# Install
```

# You can install js-toastr with npm
$ npm install --save js-toastr
 
# Alternatively you can use Yarn
$ yarn add js-toastr

```

```

// using ES6 modules
import toastr from 'js-toastr'
 
// using CommonJS modules
var toastr = require('js-toastr')

Copy or import css from toast.css

```


# Usage

```
// toastr.message(YOUR_MESSAGE, STATE, TIME_IN_Millisecond);

Example :

toastr.message('Welocome to tiny toast library', 'success', 3000);

toastr.message('Welocome to tiny toast library', 'error', 3000);

toastr.message('Welocome to tiny toast library', 'info', 3000);

toastr.message('Welocome to tiny toast library', 'warning', 3000);

```

# License

MIT