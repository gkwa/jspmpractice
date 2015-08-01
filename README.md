# jspmpractice

Stepping through this guide:
http://javascriptplayground.com/blog/2014/11/js-modules-jspm-systemjs/

Use npm serve
https://www.npmjs.com/package/serve

When I do this then serve isn't found
```sh
npm install --global jspm
jspm init -y
jspm install -g npm:serve
# exit shell
# open new shell
serve # this doesn't work, error: bash: serve: command not found
```

but doing this, serve is found:
```sh
npm uninstall -g serve
npm install -g serve
# exit shell
# open new shell
serve # this works
```
