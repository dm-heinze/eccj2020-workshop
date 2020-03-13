## Motivation


### Herausforderungen Agenturgeschäft
- unterschiedliche Shop Systeme <!-- .element: class="fragment" -->
- hohe Entwicklungszeiten <!-- .element: class="fragment" -->
- wenig Flexibilität <!-- .element: class="fragment" -->
- veraltete Frontend Technologien <!-- .element: class="fragment" -->
- schlechte Performance <!-- .element: class="fragment" -->


### Jeder Shop ist gleich.
- Komponenten die jeder Shop braucht definieren (Liste, Detail, Suche, etc...) <!-- .element: class="fragment" -->
- Einheitliche Datenstruktur ableiten <!-- .element: class="fragment" -->
- Daten via Headless API bereitstellen <!-- .element: class="fragment" -->
- Backend Agnostik hergestellt <!-- .element: class="fragment" -->


### Reaktives JS
- Strukturierung nach Komponenten  <!-- .element: class="fragment" -->
- bessere Performance  <!-- .element: class="fragment" -->
- dank Model Binding und reaktivem Verhalten, schnellerer Zugriff auf Daten  <!-- .element: class="fragment" -->
- Angular? React? Vue? <!-- .element: class="fragment" -->
- Vue.js <!-- .element: class="fragment" -->


### Erster Prototyp
- Shop: Magento 1 <!-- .element: class="fragment" -->
- hubble API (Elastic Search Index + Laravel API) <!-- .element: class="fragment" -->
- Frontend: Laravel + Vue.js Components<!-- .element: class="fragment" -->


### hubble Prototyp
![Image of DMF]()<!-- .element data-src="assets/hubble-stack-prototype.svg" width="700" style="border: 0; background: None; box-shadow: None;" -->


### noch mehr Herausforderungen
- SEO (JS gerenderte Komponenten fehlen im DOM) <!-- .element: class="fragment" -->
- Komponenten weiter entkapseln, da Laravel in Templates arbeitet und nicht mit Komponenten <!-- .element: class="fragment" -->
- besser eine einheitliche (JS basierte) Lösung <!-- .element: class="fragment" -->
- Setup und Konfiguration von mehreren Frameworks aufwändig <!-- .element: class="fragment" -->


### Nuxt.js
- SSR (serverside Rendering) löst SEO Problem <!-- .element: class="fragment" -->
- basiert komplett auf Komponenten <!-- .element: class="fragment" -->
- Vue.js basiert <!-- .element: class="fragment" -->
- bietet sein eigenes Modulsystem, gute Erweiterbarkeit <!-- .element: class="fragment" -->
- bringt node.js Server mit sich inkl. Hot Module Replacement für superschnelles Entwickeln <!-- .element: class="fragment" -->


### hubble API Stack
![Image of DMF]()<!-- .element data-src="assets/hubble-stack-pwa.svg" width="900" style="border: 0; background: None; box-shadow: None;" -->


### hubble Saleschannel API Stack
![Image of DMF]()<!-- .element data-src="assets/hubble-stack-sw-pwa.svg" width="900" style="border: 0; background: None; box-shadow: None;" -->
