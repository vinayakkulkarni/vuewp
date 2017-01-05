# vuewp
Wordpress Twentyseventeen theme with Vue (VueJS) and GraphQL. Still in progress. You can find a demo here: [http://prutstuin.be](http://prutstuin.be).

### Install
+ git clone vuewp
+ cd vuewp
+ npm install

A graphql js client is included (Lokka). I had to set credentials to false in Lokka to fix cors-errors (see documentation in graphql-vuewp repo).

### Dependencies
+ wordpress backend of course
+ [graphql-vuewp](https://github.com/whuysmans/vuewp-graphql) plugin
+ acf if you want it

### Todo
+ fix cors in a more sustainable way
+ add animations

### SEO
+ after a lot of trial and error, I decided to redirect the bots through mod_rewrite to the base WP install; a poor man's SSR; a node server on the backend was outside the scope of this demo, since my intent was to provide all backend functionality in a single WP plugin. It is probably bad, but it's working. 
