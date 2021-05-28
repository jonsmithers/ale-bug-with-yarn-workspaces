```bash
# this reports lint
cd ./ && yarn exec eslint react-app/src
```

```bash
# this reports no lint
cd react-app && yarn exec eslint src/
```

The [`eslint-plugin-import`] readme says:

> Relative paths will be resolved relative to the source's nearest `package.json` or the process's current working directory if no package.json is found.

[`eslint-plugin-import`]: https://github.com/benmosher/eslint-plugin-import
