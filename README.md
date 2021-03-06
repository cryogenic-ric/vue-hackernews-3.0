# vue-hackernews-3.0
HackerNews clone built with Vue 3.0, vue-router@next &amp; vuex@next, with server-side rendering 

<p align="center">
 <img src="https://user-images.githubusercontent.com/57749196/97715211-ca9dfe80-1aca-11eb-986e-0fd056c60838.png" width="700px">
</p>

# Info

This is a Vue-3.0 version of the <a href="https://github.com/vuejs/vue-hackernews-2.0">Vue-2.0 hackernews clone</a>. 
  - Vue 3.0, Vue-Router 4.0, Vuex 4.0.
  -  Preliminary Webpack 5 implementation with HMR (sometimes a but clonky), code-splitting
  - Bundle renderer using <a href="https://www.npmjs.com/package/vue-bundle-renderer">this package</a>
  
## More Info

Please refer to the <a href="https://ssr.vuejs.org">vue-2 ssr guide</a> to get an idea how this is working.
As the HN v2 clone this repo is to explore the possibilities of Vue 3.0 SSR. Final build setup is project dependant. 

## Ideas?

With all the new possibilities vue@next brought there's propably other/smarter ways to code parts of the meachanics....

## Build Setup

**Requires Node.js 10.13.0+**  

``` bash
# install dependencies
npm install # or yarn

# serve in dev mode, with hot reload at localhost:8080
npm run start:dev

# build for production
npm run build

# serve in production mode
npm start:prod
```

## Credits

Based, inspired and forked by/from Vue-2.0 Hackernews clone by @evanyou and Hackernews clone by @nuxt

## License

MIT
