### FullStack TypeScript, React starter kit.

---

## Under development


#### What's included
* TypeScript (With Source maps)
* React
* React router v4


#### What's not included
* Babel (Not needed)
* Universal
* Redux [How to add]
* Styling library [How to add]

##### Notes:
* Separated `tsconfig.json` for server and client.
* Server is emitted by TypeScript, client is bundled using Webpack.
* Server can client can share code (And types). For example: Validation.ts, IUserDTO.d.ts

##### Usage:
* `npm run dev` - Server and client are in watch mode with source maps
* `npm build` - `dist` folder will include all the needed files, both client (Bundle) and server.
* `npm start` - Just runs `node ./dist/server`  

##### Requirements
* Node 6.9.5+




---
### todo
* More docs
* example for shared code
* tslint? (Only on pre-commit?)
* minify on build?
 
* client
  * add react router
  * add nav bar
  * call the server api
  * static files  
  
* server
  * Currently is using static html, let webpack generate the html out of a template
  * The server is is using /dist/public, for statics... what can we do here?
  * favicon
