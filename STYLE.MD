# Design Guidelines

### General

- Reuse borders from adjacent provinces, so they can be stitched together to create entire continent maps.

### Font

- Font (must be installed on your computer): [Sovngarde](https://www.nexusmods.com/skyrimspecialedition/mods/386)
- Font size: 
  - Settlements: 11 (small), 18 (medium), 28 (large);
  - Holds (or equivalent): 18 (minor political power), 28 (major political power);
  - Water: 11 (small rivers, bays, lakes), 14 (large rivers, gulfs), 28 (seas);
  - Provinces: 48 (adjacent), 96 (main).
- Font style:
  - Settlements: normal;
  - Holds (or equivalent): all caps;
  - Water: normal;
  - Provinces: all caps.

### Color

- Borders: #000000;
- Land: #DEC7B0 (main), #CABCAA / #B6B2A7 (adjacent);
- Water: #85A4B3;
- Lava: #ED2939;
- Mountains: #000000;
- Text: #000000 (main, mountain text on mountain), #FFFFFF (text in water, mountain text on land), #85A4B3 (water on land).

### Settlement

- Outline: #000000, 1.5px;
- Fill: #808080;
- Style: polygon with sides 10px in length. Number of sides determine the city size/importance.

### Escutcheon

- Width: 32px (minor political power), 64px (major political power).

### Outline

- Borders: 1px, #000000;
- Water: #85A4B3, 2px (small rivers), 5px (large rivers).
