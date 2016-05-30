# An example using a Bootstrap Theme

## What is this?

This is project using [a sample Bootstrap theme](https://github.com/web-course/webdev-bootstrap-theme) in Github.
It shows how developers can create and use bower components using Github without an additional package repository.

## Installation

To install the dependencies, you may run `bower`

 ```
 bower install
 ```

## How it works

The project includes a `bower.json` file describing the dependencies.
For one of the components, it specifies the Github repository where the component may be downloaded.
The `bower` will download the component and all its dependencies to the `bower_components` folder.

```json
{
  "dependencies": {
    "webdev-bootstrap-theme": "https://github.com/web-course/webdev-bootstrap-theme.git"
  }
}
```


## Copyright and License

Copyright (c) 2016  TiCsw Research Group, Uniandes / Jaime Chavarriaga.
Code released under the [MIT](https://opensource.org/licenses/MIT) license.