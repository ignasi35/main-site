# CONTRIBUTORS

Per a contribuir a aquest projecte, podeu seguir els passos següents:

## Desenvolupament local

El blog usa [Jekyll](https://jekyllrb.com/) i es desplega a GitHub Pages.

### Instal.lació inicial

1. Instal·lar Jekyll seguint les [instruccions oficials](https://jekyllrb.com/docs/installation/).
2. Clonar aquest repositori.
3. A la carpeta del projecte, executar: 
   ```bash
   bundle install
   ```

### Execució local

1. Per executar el servidor localment:
   ```bash
   bundle exec jekyll serve
   ```
2. Obrir el navegador a [http://localhost:4000](http://localhost:4000).

## Afegir nous articles

Per a afegir un nou article al blog, creeu un nou fitxer a la carpeta `_posts` seguint el format de nomació `YYYY-MM-DD-titol-del-post.md`. Assegureu-vos d'incloure les metadades necessàries al principi del fitxer, com ara `layout`, `title`, `date` i `categories`.

Creeu una PR amb els vostres canvis i un cop revisada, es farà el merge al repositori principal. Si la PR no rep comentaris en 7 dies, contacteu via email (einesdigitals365@gmail.com) per a accelerar el procés de revisió.
