## Performance Optimization


### Bewährte Methoden
- Lazy Loading von Bildern <!-- .element: class="fragment" -->
- JS minify <!-- .element: class="fragment" -->
- JS Bundling <!-- .element: class="fragment" -->


### Erweiterte Methoden
- Code splitting <!-- .element: class="fragment" -->
- Dynamic Imports <!-- .element: class="fragment" -->


## Webpack Bundling
![Webpack Bundling]()<!-- .element data-src="assets/what-is-webpack-4.png" width="900" -->


## Code splitting/chunking


![Image of DMF]()<!-- .element data-src="assets/hubble-bundle-analyse.png" width="900" style="border: 0; background: None; box-shadow: None;" -->


## Webpack dynamic imports
```javascript
// Static Import
import MyComponent from './MyComponent.vue'
export default {
    name: 'MyParentComponent',
    components: { MyCoolComponent },
}

// Dynamic Import
export default {
    components: {
        lazyComponent: () => import('MyComponent.vue')
    }
}
```


### Lazy Loading von Komponenten 
- Routen = Vue.js Komponenten = Routenbasiertes Codesplitting <!-- .element: class="fragment" -->
- Laden von Komponenten anhand von Events (scroll, click, etc...)  <!-- .element: class="fragment" -->

![Mind blown]() <!-- .element: data-src="https://media.giphy.com/media/26ufdipQqU2lhNA4g/source.gif" class="fragment" -->


![Image of DMF]()<!-- .element data-src="assets/hubble-data-flow-clientside.svg" width="800" style="border: 0; background: None; box-shadow: None;" -->


### Lazy Loading JS Chunks on scroll
![Lazy Loading JS Chunks on scroll]()<!-- .element data-src="assets/lazy-loading-components.gif" width="900" style="border: 0; background: None; box-shadow: None;" -->
