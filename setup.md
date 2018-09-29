# Run vuegg locally
---

## Auto-run
``` bash
# install, build and serve
npm run vuegg
```
Navigate to `localhost:5000` to serve (a production-ready) vuegg.

</br>

## Step-by-step setup

**1. Installation**

``` bash
# install client & server dependencies
npm run install:all

# OR install only client / server
npm run install:client
npm run install:server
```

**2. Development**
``` bash
# serve vuegg-client with hot reload
npm run client

# start vuegg-server (auto-restarts on changes)
npm run server
```
Navigate to `localhost:8080` to serve *vuegg-client* with hot-reload (development server).

> For detailed explanation on how things work on the client side, checkout the **[vuejs-templates/webpack](http://vuejs-templates.github.io/webpack/)** guide and docs for **[vue-loader](http://vuejs.github.io/vue-loader)**.

> For development *vuegg-server* will only generate vuejs projects (it won't be serving *vuegg-client* resources). Auto-restart capabilities possible thanks to **[nodemon](https://github.com/remy/nodemon)**.

> The above commands should be run in separate terminal instances.

**3. Production**
``` bash
# build vuegg-client for production with minification
npm run build

# start vuegg-server at localhost:5000
npm run start
```
Navigate to `localhost:5000` to serve (a production-ready) vuegg.

</br>

## Connect with github

Vuegg makes use of `.env` files to set up some environment variables. The current setup allows you to have 3 files with different configurations: `.env`, `.env.dev` and/or `.env.test`, containing the following variables:

``` yaml
# Create an OAuth App on github and use your client ID and Secret

CLIENT_ID=y0urcl13nt1d
CLIENT_SECRET=y0urcl13nts3cr3t
CALLBACK_URL=http://localhost:8000/auth
```

> This files should exist only on your local machine, do not add them to the git repository.

Now if you wish to test out the *connect with github* functionality on your local environment, it's necessary to run vuegg-client and vuegg-server through the following command:

``` bash
npm run oauth
```
You should be prompted with 3 options to pick. Run server and client in separate terminal instances.
