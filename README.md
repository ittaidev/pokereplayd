# PokéReplay

Catálogo personal para ver episodios públicos del anime de Pokémon que el canal oficial ha subido a YouTube.

## Objetivo

Tener en un solo sitio los episodios públicos del canal oficial, agrupados por región y temporada, con el reproductor de YouTube. No es un servicio de streaming: no se descargan ni se alojan vídeos. Cada episodio se reproduce en el iframe oficial de YouTube, con su audio, subtítulos y controles.

La página está pensada para uso privado (por ejemplo detrás de Cloudflare Access).

## Cómo funciona

- Los episodios se cargan desde el canal oficial de YouTube mediante el reproductor embebido.
- Las temporadas se agrupan por región (Kanto, Johto, Hoenn, etc.).
- Se puede marcar un episodio como visto y seguir donde se dejó (los datos se guardan en el navegador).
- Modo claro y modo oscuro.
- Las imágenes de temporada son opcionales: si se añaden como `images/S1.jpg`, `images/S2.jpg`, etc., sustituyen el número de la tarjeta.

## Despliegue

Sitio estático, listo para Cloudflare Pages.

1. Conectar el repositorio en Cloudflare Pages.
2. Framework preset: None.
3. Build command: vacío.
4. Output directory: `/` (la raíz).
5. Activar Cloudflare Access sobre el dominio y dejar solo tu correo.

## Descargo de responsabilidad

PokéReplay es un proyecto personal y no oficial.

- No está afiliado, asociado, autorizado, respaldado ni patrocinado por Nintendo, The Pokémon Company, Creatures, Game Freak, TV Tokyo ni YouTube.
- Pokémon y los nombres relacionados son marcas de sus respectivos propietarios.
- Los vídeos pertenecen a sus titulares. Este sitio no copia, descarga, aloja ni redistribuye ningún episodio: solo incrusta el reproductor público de YouTube de vídeos que el canal oficial ha publicado.
- El uso de la página es bajo la responsabilidad de quien la visita. El autor no se hace responsable del contenido de los vídeos, de cambios en la disponibilidad de YouTube, ni de cualquier reclamación derivada del uso del sitio.
- Si un titular solicita la retirada de un enlace o de la página, se atenderá.

Este repositorio y la página se mantienen para uso privado del autor.
