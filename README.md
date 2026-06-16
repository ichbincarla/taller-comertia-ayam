# Talent Retention OS · AYAM × Comertia

Recurs web d'una sola pàgina per a responsables de RRHH del retail: un sistema en 4 fases + un repositori de prompts d'IA + una biblioteca d'eines, per fer visible l'ànima de l'empresa i retenir talent.

És el "takeaway" del taller **«Fer visible l'ànima»**. Filosofia: *la IA és el mirall, mai el substitut del criteri humà.*

## Què conté
- **Hero / tesi** — es guanya per pertinença, no pel sou.
- **Roadmap en 4 fases** — Anomena · Contrasta · Prova · Sostén.
- **Repositori de prompts** — el GPT Talent Mirror complet + 3 prompts ràpids per fase, amb botó de copiar i descàrrega en `.txt`.
- **Biblioteca d'eines** — fitxes filtrables per fase i per preu, amb enllaços externs.
- **3 línies vermelles legals** — RGPD / AI Act per a Espanya.
- **Pla de 7 dies.**

## Stack
Un sol fitxer `index.html` autocontingut. Zero build, zero dependències (només Google Fonts per CDN). JS vanilla. Mobile-first.

## Com publicar-ho a GitHub Pages
1. Crea un repositori públic a GitHub (p. ex. `talent-retention-os`).
2. Puja `index.html` i aquest `README.md` (arrossega'ls a la pàgina del repo → *commit*).
3. Vés a **Settings → Pages**.
4. A **Build and deployment → Source**, tria **Deploy from a branch**.
5. **Branch:** `main` · carpeta `/ (root)` → **Save**.
6. Espera 1-2 minuts. La web quedarà a `https://EL-TEU-USUARI.github.io/talent-retention-os/`.

## Com editar el contingut
- Tots els **textos** són a `index.html`.
- Les **eines** són a l'array `TOOLS` dins del `<script>` (afegir/treure cards).
- Els **prompts** són dins de blocs `<pre class="prompt" id="...">`.
Edita, fes *commit*, i GitHub Pages s'actualitza sol.

## Marca
Look & feel AYAM: Verd Blau #344E5A, Crema #F7F7F9, accents Verd #1BA969 / Coral #F36C69 / Groc #EAF24E. Tipografia: Fraunces (serif) + Inter (sans).

---
*Decisions preses: web en català (amb prompts que responen també en castellà), un sol fitxer per a desplegament trivial, enllaços oberts en pestanya nova.*
