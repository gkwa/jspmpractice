# jspmpractice

Stepping through this guide:
JavaScript Modules and Dependencies with jspm by Jack Franklin
http://javascriptplayground.com/blog/2014/11/js-modules-jspm-systemjs/

npm serve:
https://www.npmjs.com/package/serve

bundle for production
https://github.com/jspm/jspm-cli/wiki/Getting-Started

jquery addition
https://github.com/components/jquery

```sh
npm install --global jspm
jspm init -y
# No: jspm install -g npm:serve # https://github.com/jspm/jspm-cli/issues/585#issuecomment-82209908
npm install -g serve
jspm bundle lib/main --inject
```
