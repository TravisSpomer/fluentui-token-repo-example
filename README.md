# fluentui-token-repo-example

This sample project illustrates a possible CD workflow using the `fluentui-token-pipeline` project.

Whenever the `tokens.json` file in this repo changes, GitHub Actions automatically processes the tokens and produces source code as a [package on NPM](https://www.npmjs.com/package/@travisspomer/fluentui-token-repo-example) and [build artifact](https://github.com/TravisSpomer/fluentui-token-repo-example/actions), and produces a token reference on [GitHub Pages](https://travisspomer.github.io/fluentui-token-repo-example/).

## Private NPM package

Since `fluentui-token-pipeline` isn't on NPM at the moment, this repo uses a privately-published version. The original source I used for that version was identical to the [state of the original repo](https://github.com/microsoft/fluentui-token-pipeline/commit/c45b5e9f657d4e7bd8c2bea7a0890d10e371eb57) except with a different package name.
