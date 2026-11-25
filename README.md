# Granota Saltadora

Joc d'una sola pantalla fet amb HTML5 canvas, en un únic fitxer (`index.html`), sense dependències.

Mantén el dit (o l'espai) per carregar el salt: com més temps, més lluny. Salta de penya-segat en penya-segat sense caure a l'aigua.

## Característiques

- Control d'un sol toc, apte per a mòbil i escriptori.
- Plataformes generades amb una simulació que garanteix que sempre es pot arribar a la següent.
- Dificultat progressiva: gel, plataformes mòbils, roques que cauen, vent i rampes.
- Mosques (5 = escut), perfectes, combo i doble salt.
- 3 mons: Prat, Glacera i Volcà.
- Monedes, 8 skins i 4 habilitats amb millores.
- Repte diari (mateix recorregut per a tothom) amb ratxa, i 3 missions noves cada dia.
- Hall of Fame local. Les dades es guarden al dispositiu (`localStorage`).

## Icona i instal·lació

Inclou icona (`icons/`), `manifest.webmanifest` i un `sw.js` senzill per poder instal·lar-lo com a aplicació des del navegador i jugar sense connexió.

## Com jugar en local

Obre `index.html` al navegador. No cal cap servidor.

## Publicar a GitHub Pages

1. Crea un repositori nou a github.com i puja'hi aquests fitxers.
2. A *Settings > Pages*, tria *Source: GitHub Actions*.
3. En fer `push` a `main`, el workflow `.github/workflows/pages.yml` el publica a `https://<usuari>.github.io/<repositori>/`.

## Cap a Google Play

El joc es pot empaquetar com a aplicació Android amb [Capacitor](https://capacitorjs.com/) o una Trusted Web Activity (Bubblewrap). Cal un compte de desenvolupador de Google Play.

## Llicència

MIT. Consulta `LICENSE`.
