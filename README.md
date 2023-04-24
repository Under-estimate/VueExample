Minimal Reproduction Example for https://github.com/vuejs/language-tools/issues/2671

**This issue has been solved**, thanks to [@johnsoncodehk](https://github.com/johnsoncodehk). This is an intended behavior of JSX. Remove `"jsxTemplates": true` in [tsconfig.json](/tsconfig.json) will disable the error.

![screenshot](/images/screenshot.png)
