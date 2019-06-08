Vuejs Argon Design System - coded by AppSeed App Generator
====
Vue.js App enhanced with JWT Authentication. Can be used with [Express](https://github.com/app-generator/express-starter), [Flask](https://github.com/app-generator/flask-starter) or [Laravel](https://github.com/app-generator/laravel-starter). Read more on [AppSeed](https://appseed.us/apps/argon-design-system). 

![Vue Argon Design](https://github.com/app-generator/vuejs-argon-design-system/blob/master/screenshots/vue-argon-design-system.png)

## Requirements
- [Node.js](https://nodejs.org/) >= 6.x

## Setting up for development
* clone the project: `git clone https://github.com/app-generator/vuejs-argon-design-system.git`
* change directory to `vuejs-argon-design-system`
* (Optionally) start the [Express](https://github.com/app-generator/express-starter/blob/master/README.md) backend server (default ip/port: `locahost:3000`)
* Default backend URL `http://127.0.0.1:3000`. This can be overwritten by updating the file: `src/views/Login.vue`

## Scripts
**Install Modules**
```bash
$ npm i
$ npm install -g serve # (optionally) 
```

**Run**
* `npm run serve` to start the app. Visit [localhost:8080](http://localhost:8080) in your browser. The `default port 8080` can be overwritten by updating the `package.json`, line with `serve` attribute: `vue-cli-service serve --port 8080`

**Production Build**
* `npm run build` - build the app in `dist` directory

**Test the production build**
`serve -s dist` - and visit [localhost:8080](http://localhost:8080) in your browser. You should see this [app](https://vuejs.appseed.us) running.  

## Support
Live support on [Discord](https://discord.gg/fZC6hup) and [Facebook](https://www.facebook.com/groups/fullstack.apps.generator). 

## License
MIT 

---
Made with ♥ by [AppSeed.us]("https://appseed.us")
