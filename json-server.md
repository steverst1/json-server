## Install package json-server globally.
```js
npm i -g json-server
```
## Start server and bind it with json file.
```js
json-server --watch data/db.json
```
## Server running on `localhost:3000`

```js
localhost:3000/posts/2 //post has index 2 
localhost:3000/posts?title_like=hello
localhost:3000/posts?likes_like=1
localhost:3000/posts?_sort=likes&_order=desc
```
## Note
```js
npm install --save json-server
/*Note:--save
installed modules are added as a dependency by default,
so the --save option is no longer needed. Besides It won't do anything if you don't have a package.json file.
Start by running npm init to create one. If you install it locally in your project, use npx to run it*/
npx json-server --watch db.json
```