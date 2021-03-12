# Groupomania project : create a social network

> The social network by Groupomania

## Getting started

Clone each submodule on your local machine and follow the instructions. You can also clone this global repo :

```git clone --recurse-submodules --remote-submodules https://github.com/antoinebollinger/AntoineBollinger_7_03022021```

## Backend

Before your start, make sure you have access to a Mysql server. You'll need to create a .env file a the root of your backend file, with the following:

```DB_HOST=/your host - can be localhost
DB_USER=/your user - can be root
DB_PASSWORD=/your password - empty when localhost
DB_DATABASE=groupomania```


- Clone the global project (https://github.com/antoinebollinger/AntoineBollinger_7_03022021) on your local machine. 
=> As it's using git submodule, please ensure to use 'git clone --recurse-submodules --remote-submodules'

- See each peticular instructions on both front and back end part




# @vue/cli-plugin-babel

> babel plugin for vue-cli

## Configuration

Uses Babel 7 + `babel-loader` + [@vue/babel-preset-app](https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/babel-preset-app) by default, but can be configured via `babel.config.js` to use any other Babel presets or plugins.

By default, `babel-loader` excludes files inside `node_modules` dependencies. If you wish to explicitly transpile a dependency module, you will need to add it to the `transpileDependencies` option in `vue.config.js`:

``` js
module.exports = {
  transpileDependencies: [
    // can be string or regex
    'my-dep',
    /other-dep/
  ]
}
```

## Caching

Cache options of [babel-loader](https://github.com/babel/babel-loader#options) is enabled by default and cache is stored in `<projectRoot>/node_modules/.cache/babel-loader`.

## Parallelization

[thread-loader](https://github.com/webpack-contrib/thread-loader) is enabled by default when the machine has more than 1 CPU cores. This can be turned off by setting `parallel: false` in `vue.config.js`.

`parallel` should be set to `false` when using Babel in combination with non-serializable loader options, such as regexes, dates and functions. These options would not be passed correctly to `babel-loader` which may lead to unexpected errors.

## Installing in an Already Created Project

``` sh
vue add babel
```

## Injected webpack-chain Rules

- `config.rule('js')`
- `config.rule('js').use('babel-loader')`
