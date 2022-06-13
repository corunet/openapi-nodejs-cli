[Summary](#summary) · [Getting started](#getting-started) · [Support](#support) · [License](#license)

## 📜 Summary
`openapi-nodejs-cli` is a typescript code generator from an OpenApi document. 

`openapi-nodejs-cli` can generate nodejs, typescript client and Angular client methods from an OpenApi document.


## 🚀 Getting Started

### How to install 

```bash
npm i @corunet/openapi-nodejs-cli --global
```

### 🧑🏻‍💻 Usage

```bash
openapi-nodejs-cli input/schema.yaml
```

You can retrieve an option list with this command:
```
openapi-nodejs-cli --help
```

```
Usage: openapi-nodejs-cli [options]

Options:
  -V, --version             output the version number
  -i, --input <string...>   OpenAPI spec URLs or directories
  -o, --output <string...>  Output folder
  --client                  only generate client code
  --server                  only generate server code
  --angular                 generate client code for Angular
  -h, --help                display help for command
```
## 🧰 Support

We’ll be glad to talk and discuss how `openapi-nodejs-cli` can help you 😊

Reach us through [GitHub issues](https://github.com/corunet/openapi-nodejs-cli/issues), [email](mailto:info@corunet.com) or [Twitter](https://twitter.com/corunet).

## License

This Source Code Form is subject to the terms of the Mozilla Public License, v. 2.0. If a copy of the MPL was not distributed with this file, You can obtain one at [https://mozilla.org/MPL/2.0/](https://mozilla.org/MPL/2.0/).
 