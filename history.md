## Motivation


### Herausforderungen
- unterschiedliche Shop Systeme <!-- .element: class="fragment" -->
- hohe Entwicklungszeiten <!-- .element: class="fragment" -->
- wenig Flexibilität <!-- .element: class="fragment" -->
- veraltete Frontend Technologien <!-- .element: class="fragment" -->
- schlechte Performance <!-- .element: class="fragment" -->


### Jeder Shop ist gleich
- Gemeinsame Komponenten definieren (Liste, Detail, Suche, etc...) <!-- .element: class="fragment" -->
- Datenstruktur vereinheitlichen <!-- .element: class="fragment" -->
- via Headless API bereitstellen <!-- .element: class="fragment" -->
- Backend agnostisch <!-- .element: class="fragment" -->


### Reaktives JS
- Strukturierung nach Komponenten  <!-- .element: class="fragment" -->
- Performance  <!-- .element: class="fragment" -->
- Schnellerer Zugriff auf Daten dank Model Binding und reaktiven Verhaltens  <!-- .element: class="fragment" -->
- Angular? React? Vue? <!-- .element: class="fragment" -->
- Vue.js <!-- .element: class="fragment" -->


### Erster Prototyp
- Shop: Magento 1 <!-- .element: class="fragment" -->
- hubble API (Elastic Search Index + Laravel API) <!-- .element: class="fragment" -->
- Frontend: Laravel + Vue.js Components<!-- .element: class="fragment" -->


### (Schaubild von Barstuff Rocket Architektur)


### noch mehr Herausforderungen
- SEO <!-- .element: class="fragment" -->
- Komponenten weiter entkapseln (Laravel = Templates) <!-- .element: class="fragment" -->
- JS basierte Lösung <!-- .element: class="fragment" -->
- Setup und Konfiguration aufwändig <!-- .element: class="fragment" -->


### Nuxt.js
- SSR (serverside Rendering) <!-- .element: class="fragment" -->
- basiert auf Komponenten <!-- .element: class="fragment" -->
- Vue.js basiert <!-- .element: class="fragment" -->
- bietet sein eigenes Modulsystem <!-- .element: class="fragment" -->
- bringt node.js Server mit sich inkl. Hot Module Replacement  <!-- .element: class="fragment" -->


### (Schaubild von hubble API + nuxt App + 6 Direktanbindung)
