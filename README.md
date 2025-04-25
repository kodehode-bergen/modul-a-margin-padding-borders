# 🧩 Modul A- Margin, padding og borders - Pokédex

Velkommen til Pokédex 1.0! Dette prosjektet visualiserer de tre første evolusjonsrekkene fra den originale Pokémon-generasjonen – Bulbasaur, Charmander og Squirtle. Ved hjelp av **HTML** og **CSS** har vi laget en enkel og stilfull oversikt over evolusjoner, med farger og rammer som reflekterer deres typer 🌱🔥💧

---

## 🧠 Læringsmål

Prosjektet gir praktisk øvelse i:

✅ Semantisk HTML-struktur  
✅ Bruk av `section`, `id` og `class` for layout og styling  
✅ Flex/inline-block-baserte layouts  
✅ Temabasert fargebruk i CSS  
✅ Bruk av spesialfonter fra Google Fonts (`Bytesized`, `Chewy`)  
✅ Enkel bildebruk med `img` og alternativ tekst  
✅ Boksmodellen (`margin`, `padding`, `border`) og dekorative rammer  
✅ Ulike CSS `border-style`-eksperimenter: `inset`, `double`, `groove`

---

## 🔢 Evolusjonsrekkene som vises

| Pokédex ID | Pokémon        | Type   |
|------------|----------------|--------|
| 001–003    | Bulbasaur ➝ Venusaur   | 🌿 Grass |
| 004–006    | Charmander ➝ Charizard | 🔥 Fire  |
| 007–009    | Squirtle ➝ Blastoise   | 💧 Water |

---

## 🎨 Typestil og fargekoding

| Type   | Bakgrunnsfarge       | Border-style            |
|--------|-----------------------|--------------------------|
| Grass  | `rgb(167, 214, 121)`  | `inset green`           |
| Fire   | `rgb(248, 148, 111)`  | `double rgb(227, 61, 61)`|
| Water  | `rgb(144, 226, 199)`  | `groove rgb(66, 66, 212)`|

---

## 🖼️ Eksempel på HTML-struktur

```html
<section class="fire">
  <h2>Pokédex #005</h2>
  <p>Charmeleon</p>
  <img src="./pokemon-images/250px-0005Charmeleon.png" alt="Charmeleon" />
</section>
