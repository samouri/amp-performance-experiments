# amp-performance-experiments

1. gather corpus
  1.1 use view-source and copy/paste to generate the `index.default.html`
  1.2 use Chrome and load the same page. Modify all iframes to have loading=lazy. `copy(document.innerHTML)` to generate `index.ssr.html`.
  1.3 remove all extension script tags from the `ssr.html` file to generate `index.nojs.html`
2. create test infra
3. analyze
