# cz-fprovost-sm360-changelog

Part of the [commitizen](https://github.com/commitizen/cz-cli) family. Prompts for [conventional changelog](https://github.com/stevemao/conventional-changelog-angular/blob/master/index.js) standard.


## How to install and use

Install `commitizen` globally, if you have not already.

```
npm install -g commitizen
```

Install your preferred `commitizen` adapter globally, for example [`cz-fprovost-sm360-changelog`](https://www.npmjs.com/package/cz-fprovost-sm360-changelog)

```
npm install -g cz-fprovost-sm360-changelog
```

Create a `.czrc` file in your `home` directory, with `path` referring to the preferred, globally installed, `commitizen` adapter

```
echo '{ "path": "cz-fprovost-sm360-changelog" }' > ~/.czrc
```

You are all set! Now `cd`into any `git` repository and use `git cz` instead of `git commit` and you will find the `commitizen` prompt.

Protip:  You can use all the `git commit` `options` with `git cz`, for example: `git cz -a`.
