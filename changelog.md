## [1.0.0] - 2026-05-12
### Añadido
- Estructura base del pack (`manifest.json`).
- **Modo Oscuro (UI):** Implementación inicial del tema oscuro en menús principales y diálogos mediante `ui_common.json`.
- **Visión en Lava:** Ajustes de niebla en archivos `.json` para permitir visibilidad clara (hasta 64 bloques) bajo la lava permitiendo asi una vista total bajo la lava.
- **Sin Niebla (Nether):** Eliminación de la niebla de distancia y volumétrica en todos los biomas del Nether (Wastes, Crimson, Warped, Soul Sand, Basalt).
- **Textos Personalizados:** Archivo `splashes.txt` con frases sobre programación, juegos y cultura pop.
- **Armadura de Netherite:** Nueva textura base optimizada para ser compatible con Armor Trims y con nuevo estilo legacy.
- **Happy ghast:** Textura del happy ghast actualizada a su version legacy.
- **Madera:** Cambio total de las maderas del juego y todas sus variaciones e items.


### Cambiado
- **Mapeo de Biomas:** Configuración de `biomes_client.json` para estandarizar la atmósfera del Nether.

### Corregido
- **Densidad Volumétrica:** Se eliminó la calima rojiza del Nether ajustando los coeficientes de dispersión y absorción a 0.0.
- **Visibilidad de Texto:** Ajuste de colores RGB en etiquetas de UI para asegurar legibilidad sobre fondos negros.
- Primeros experimentos con la niebla del Nether.

---

## [1.1.0] - 2026-04-15
### Añadido
- Icono del pack temporal.
* **Arnés de Happy ghast:** Arneses tematizados con diversos mobs al rededor del juego, texturas sacadas de [Happy-ghast](https://www.curseforge.com/minecraft/texture-packs/happy-ghast-costumes/files/6583237) via curseforge actualmente se encuentran: 
     - Arnés color Negro: Enderman
     - Arnés color Lima: Creeper
     - Arnés color Gris: Creaking
     - Arnés color Blanco: Esqueleto
     - Arnés color Gris claro: Calabaza gris
<br>
**Todos los items tienen sus correspondientes texturas, es una manera de saber cuales serán las texturas a futuro**
- **Cristales:** Cristales de la version legacy via [Curse forge](https://www.curseforge.com/minecraft/texture-packs/clean-glass-tinted-glass/files/6089906).
- El bloque de deepslate ahora tiene su versión legacy incluidas sus versiones en ore.

### Corregido
- Un error menor en el sonido de los bloques de madera.
- Las animaciones de la madera de Warped y Crinsom han sido corregidas para mostrar la animacion correcta con la textura correcta.

---

## [1.1.1] - 2026-04-16
### Añadido
- Lenguaje customizado en español mexicano (`es_MX.lang`). con cambio de nombres a varios items como:
     - Discos de musica
     - Armas
- **Flores:** Nuevas y coloridas texturas agregadas a las flores silvestres.

### Cambiado
- *Cambios en los discos de musica*
     - **Discos 13:** Recuerdos - José José
     - **Disco wait:** Ditto - New Jeans
     - **Disco ward:** ASAP - New Jeans


> [!IMPORTANT]
> Este proyecto sigue los principios de modularidad aplicados .

