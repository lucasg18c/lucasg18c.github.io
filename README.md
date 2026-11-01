# lucasg18c.github.io

Sitio común de desarrollador, publicado con GitHub Pages en <https://lucasg18c.github.io>. Es el sitio web que declaran las fichas de las apps en las tiendas y es compartido por todos los productos.

## Qué hay

| Archivo | Para qué |
|---|---|
| `app-ads.txt` | Autoriza a la cuenta de AdMob a vender anuncios. Sirve para todas las apps de esa cuenta |
| `index.html` | Página mínima con las apps publicadas y sus políticas |
| `_config.yml` | Excluye este README de la publicación |

Las páginas legales no van acá: están en el repo `legales`, publicado en `/legales/`.

## Reglas

- **Los cambios van directo a `main`.** Hacer push a `main` publica en internet, sin vista previa.
- **Este repo es público.** Nada de secretos ni datos de usuarios.
- **`app-ads.txt` debe quedar en la raíz.** Google lo busca en `https://lucasg18c.github.io/app-ads.txt`.
- **Solo se publican las páginas.** Cualquier otro archivo de documentación hay que sumarlo a `_config.yml`, porque si no se publica.
- **Identidad git personal:** `Lucas Slavik <lucasg18c@gmail.com>`, configurada en este repo.

## Al publicar una app nueva

1. En la ficha de la tienda, declarar `https://lucasg18c.github.io` como sitio web del desarrollador.
2. Agregar la app a `index.html`.
3. Si la app usa otra red publicitaria, sumar su línea a `app-ads.txt`.
4. Después de hasta 24 horas, comprobar en AdMob, en **Aplicaciones → app-ads.txt**, que quedó verificada.
