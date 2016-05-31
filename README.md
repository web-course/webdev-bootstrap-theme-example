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

There are other alternatives to define the location of the remote Git endpoints:

| Alternative  | Description |
| -------------|-------------|
| `"some-package": "someone/some-package"` | Shortcut to a Github repository |
| `"some-package": "someone/some-package#1.0.0"` |  An specific version in a Git endpoint |
| `"some-package": "someone/some-package#9203e6166b3"` |  An specific commit in a Git endpoint |



## Copyright and License

Copyright (c) 2016  TiCsw Research Group, Uniandes / Jaime Chavarriaga.
Code released under the [MIT](https://opensource.org/licenses/MIT) license.