# cookie-manager-js
Lightweight, simple and easy cookie management library in JavaScript


![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg) 
![PyPI - Status](https://img.shields.io/pypi/status/Django.svg)

This is a library for providing more useful and powerful interface to manage your cookies.
- No Dependency
- Supports AMD, CommonJS and Node modules
- Lightweight 1 KB
- Supported by all browsers

## Installation
Download "cookie-manager.min.js" and include in your project.

```html
  <script src="cookie-manager.min.js"></script>
```


## Usage
After include the "cookie-manager.min.js", you will be able to use "CookieManager" object.

You can also load "CookieManager" object as an AMD, CommonJS or Node module.


## Functionalities

### Creating a cookie
```js
  CookieManager.set(name, value, expires, domain, path, secure);
```

- 'name(String)' cookie name
- 'value(String)' cookie value
- 'expires(Optional) (Number)' cookie expiration in days
- 'domain(Optional) (String)' cookie domain
- 'path(Optional) (String)' cookie path
- 'secure(Optional) (Boolean)' cookie ssl support flag

### Retrieving a cookie

### Updating a cookie

### Deleting a cookie

### Listing a cookie

### Clearing all cookies
  
