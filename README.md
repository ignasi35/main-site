# blog-eines-digitals

Repo de recursos i notes sobre Eines Digitals per a familiies amb infants.

## Canvis del tema

Per a canviar el tema, obrir l'[origen del tema](https://github.com/jekyll/minima/blob/master/_layouts/home.html) i copiar el/s fitxer/s a sobreescriure (per exemple, mireu a `_includes`).

## Desenvolupament del blog

El blog usa [Jekyll](https://jekyllrb.com/) i es desplega a GitHub Pages.

1. Instal·lar Jekyll seguint les [instruccions oficials](https://jekyllrb.com/docs/installation/).
2. Clonar aquest repositori.
3. A la carpeta del projecte, executar: 
   ```bash
   bundle install
   ```
4. Per executar el servidor localment:
   ```bash
   bundle exec jekyll serve
   ```
5. Obrir el navegador a [http://localhost:4000](http://localhost:4000).

## Verificar que no hi ha links trencats

[source](https://gist.github.com/danflies/958840ba3d417c7b02ac3abfac87c414):

```bash
# bundle exec jekyll serve & 
wget --spider -o ~/wget.log -e robots=off  -r -p http://localhost:4000/
grep -B 2 '404' ~/wget.log     
```
