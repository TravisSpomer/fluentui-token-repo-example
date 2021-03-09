# fluentui-token-repo-example

This sample project illustrates a possible CD workflow using the `fluentui-token-pipeline` project (`@fluentui/token-pipeline` on NPM).

Whenever the `tokens.json` file in this repo changes, GitHub Actions automatically processes the tokens and produces source code as a [package on NPM](https://www.npmjs.com/package/@travisspomer/fluentui-token-repo-example) and [build artifact](https://github.com/TravisSpomer/fluentui-token-repo-example/actions), and produces a token reference on [GitHub Pages](https://travisspomer.github.io/fluentui-token-repo-example/).
