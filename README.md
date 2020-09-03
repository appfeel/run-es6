RUN-ES6
-------

A Library to run es6, es7, typescript from command line on the fly through babel 7.

For those who prefer babel to compile typescript files.

# Install

```sh
npm i run-es6
```

# Usage

In your `package.json`:

```json
{
    "scripts": {
        "start": "run-es6 your-script.ts",
        "test": "nodemon node_modules/run-es6 your-script.ts"
    }
}
```

It will use your `.babelrc` configuration.
