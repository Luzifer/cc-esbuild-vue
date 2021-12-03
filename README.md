# Luzifer / cc-esbuild-vue

This repository contains a [cookiecutter](https://github.com/cookiecutter/cookiecutter) project template for a Vue.js / ESBuild single-page application.

It can be initialized into a new project as follows:

```console
# cookiecutter gh:Luzifer/cc-esbuild-vue
folder_name [myfolder]:
main_component_name [MyFolder]:
output_folder_name [public]:

# l --tree myfolder
drwxr-xr-x   - luzifer luzifer  3 Dec 17:52 myfolder
drwxr-xr-x   - luzifer luzifer  3 Dec 17:52 ├── ci
.rw-r--r-- 404 luzifer luzifer  3 Dec 17:52 │  └── build.mjs
.rw-r--r-- 168 luzifer luzifer  3 Dec 17:52 ├── Makefile
.rw-r--r-- 350 luzifer luzifer  3 Dec 17:52 ├── package.json
drwxr-xr-x   - luzifer luzifer  3 Dec 17:52 ├── public
.rw-r--r-- 380 luzifer luzifer  3 Dec 17:52 │  └── index.html
drwxr-xr-x   - luzifer luzifer  3 Dec 17:52 └── src
.rw-r--r--  95 luzifer luzifer  3 Dec 17:52    ├── app.vue
.rw-r--r-- 436 luzifer luzifer  3 Dec 17:52    └── main.js
```

Afterwards have a look at the `src` files, the `Makefile`, the `ci/build.mjs` and the `package.json` for further usage.
