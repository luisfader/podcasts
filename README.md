# Audio de Litmir / LitFader

Este repositorio guarda **todo el audio** del sitio [Litmir](https://luisfader.github.io/litmir/) (repositorio `luisfader/litmir`), para no ocupar espacio allá:

- `podcasts/` — los episodios de la sección Podcasts (RU «Страницы в эфире», IT «Pagine in onda», ES «Páginas al aire»).
- `novels/<novela>/music/...` — las bandas sonoras de las novelas (MP3 y trozos `.part`) y los audios que se insertan en los capítulos.

Las rutas son las mismas que tenían en `litmir`. Litmir los busca en `https://luisfader.github.io/podcasts/` (constante `AUDIO_BASE` en `litmir/index.html`).

Para agregar audio nuevo: subirlo acá con la misma ruta que tendría en litmir y registrarlo en litmir como siempre (catálogo, capítulo o `PODCASTS`).
