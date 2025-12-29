# Estructura del Directorio de Localización (Español)

## Descripción General

Este directorio contiene todas las localizaciones y archivos de traducción para el mod, organizados por categorías funcionales y módulos de contenido.

---

## 📁 Estructura de Carpetas

### Archivos de Localización (.yml)

Los archivos principales de traducción son archivos YAML con formato `*_l_spanish.yml`. Contienen pares clave-valor donde se traduce el contenido del juego.

**Tipos principales:**

- **`zz_*.yml`** - Archivos prioritarios que se cargan al final (prefijo `zz_` asegura carga tardía)
- **`ate_*.yml`** - Traducción de contenido específico del mod After the End
- **`*_replace_l_spanish.yml`** - Sobrescrituras de textos originales del juego

### Carpetas Temáticas

| Carpeta | Contenido |
| --------- | ----------- |
| `accolades/` | Reconocimientos y honores |
| `activities/` | Actividades y acciones |
| `artifacts/` | Artefactos y objetos |
| `culture/` | Culturas y etnias |
| `religion/` | Religiones y conceptos religiosos |
| `government/` | Sistemas de gobierno |
| `lifestyles/` | Estilos de vida y perks |
| `traits/` | Rasgos de personaje |
| `titles/` | Títulos nobiliarios |
| `gui/` | Interfaz de usuario |
| `situations/` | Situaciones y conflictos |
| `struggles/` | Luchas y tensiones |
| `custom_localization/` | Localizaciones personalizadas |
| `portrait/` | Descripciones de retratos |
| `event_localization/` | Textos de eventos |
| `dlc/` | Contenido específico de DLCs |

---

## 📁 Estructura de Carpetas Principales

### Carpetas de Contenido Especial

- **00 Adoption Options/** - Opciones de adopción
- **00 Cities of Wonder/** - COW mod por Valaddar
- **00 Community Culture Utility/** - CCU mod por Vertimnus

### Carpetas de Mecánicas del Juego

- **accolades/** - Aclamaciones y logros
- **activities/** - Actividades
- **artifacts/** - Artefactos
- **bookmark/** - Marcadores de inicio
- **commodities/** - Mercancías
- **culture/** - Cultura (incluyendo subcarpeta `traditions/`)
- **custom_localization/** - Localizaciones personalizadas
- **diarchies/** - Diarquías
- **dynasties/** - Dinastías
- **domiciles/** - Domicilios

### Carpetas de Eventos y Decisiones

- **event_localization/** - Localización de eventos
  - `activities/` - Eventos de actividades
  - `childhood_events/` - Eventos de infancia
  - `court_events/` - Eventos de corte
  - `death_events/` - Eventos de muerte
  - `decisions/` - Decisiones
  - `experimental/` - Eventos experimentales
  - `hold_court_events/` - Eventos de celebración de corte
  - `lifestyle/` - Estilo de vida
    - `governance/` - Gobernanza
    - `scholarship/` - Erudición
    - `warfare/` - Guerra
  - `religion_events/` - Eventos religiosos
  - `stress_events/` - Eventos de estrés
  - `yearly_events/` - Eventos anuales

### Carpetas Temáticas | Detalle

- **flavorization/** - Textos de sabor (flavor text)
- **governments/** - Gobiernos
- **gui/** - Interfaz gráfica
- **interactions/** - Interacciones
- **inventory/** - Inventario
- **lifestyles/** - Estilos de vida
- **modifiers/** - Modificadores
- **names/** - Nombres
- **opinions/** - Opiniones
- **portraits/** - Retratos
- **religion/** - Religión
  - `doctrines/` - Doctrinas
- **situations/** - Situaciones
- **struggles/** - Luchas
- **titles/** - Títulos
- **travel/** - Viaje
- **triggers/** - Disparadores
- **tutorial/** - Tutorial
- **wars/** - Guerras

### Carpetas de DLCs

- **dlc/bp2/** - Basegame Patch 2
- **dlc/bp3/** - Basegame Patch 3
- **dlc/ce1/** - Community Edition 1
- **dlc/ep1/** - Expansión Pack 1
- **dlc/ep3/** - Expansión Pack 3
- **dlc/fp1/** - Featured Pack 1
- **dlc/fp2/** - Featured Pack 2
- **dlc/fp3/** - Featured Pack 3
- **dlc/mpo/** - Music Pack Overture

---

## 📄 Archivos Principales de Localización

### Archivos Base (ATE - Advanced Terrains Expansion)

- `00_ate_deaths_l_spanish.yml` - Localizaciones de muertes (español)
- `ate_activities_l_spanish.yml` - Actividades (español)
- `ate_board_game_events_l_english.yml` - Eventos de juegos de mesa
- `ate_buildings_l_english.yml` - Edificios
- `ate_buildings_overwrite_l_english.yml` - Sobrescrituras de edificios
- `ate_california_l_english.yml` - Contenido de California
- `ate_character_l_english.yml` - Personajes
- `ate_commodites_l_english.yml` - Mercancías
- `ate_contracts_l_english.yml` - Contratos
- `ate_council_tasks_l_english.yml` - Tareas del consejo
- `ate_court_authority_laws_l_english.yml` - Leyes de autoridad de corte
- `ate_domicile_buildings_l_english.yml` - Edificios de domicilio
- `ate_elective_succession_l_english.yml` - Sucesión electiva
- `ate_epidemics_l_english.yml` - Epidemias
- `ate_focuses_l_english.yml` - Focos
- `ate_game_concepts_l_english.yml` - Conceptos de juego
- `ate_game_concepts_religions_l_english.yml` - Conceptos de religión
- `ate_glossary_l_english.yml` - Glosario
- `ate_holy_order_l_english.yml` - Orden santa
- `ate_imperial_faction_l_english.yml` - Facción imperial
- `ate_important_actions_l_english.yml` - Acciones importantes
- `ate_interactions_l_english.yml` - Interacciones
- `ate_memories_l_english.yml` - Recuerdos
- `ate_mercenaries_south_america_l_english.yml` - Mercenarios de Sudamérica
- `ate_music_l_english.yml` - Música
- `ate_nomads_l_english.yml` - Nómadas
- `ate_nomad_decisions_l_english.yml` - Decisiones nómadas
- `ate_succession_laws_l_english.yml` - Leyes de sucesión
- `ate_traits_replace_l_english.yml` - Rasgos (reemplazo)
- `ate_weapon_portrait_modifiers_l_english.yml` - Modificadores de armas en retrato

### Archivos de Mod Complementarios

- `borrowed_rice_misc_l_english.yml` - Miscellaneous
- `court_positions_l_english.yml` - Posiciones de la corte
- `equal_exchange_locs_l_english.yml` - Intercambio equitativo
- `government_replace_l_english.yml` - Gobiernos (reemplazo)
- `hcc_succession_laws_l_english.yml` - Leyes de sucesión (HCC)
- `knight_culture_l_english.yml` - Cultura de caballeros
- `mercenaries_l_english.yml` - Mercenarios
- `More's_lore_l_english.yml` - Lore adicional
- `morereligions_game_concepts_hostilities_l_english.yml` - Conceptos de religión y hostilidades
- `nicknames_ate_l_english.yml` - Apodos
- `regions_l_english.yml` - Regiones
- `religion_replace_l_english.yml` - Religión (reemplazo)
- `religion_salvager_l_english.yml` - Salvador de religión
- `salvage_artifact_modifiers_l_english.yml` - Modificadores de artefacto salvado
- `signature_weapon_custom_loc_l_english.yml` - Localizaciones personalizadas de armas
- `single_combat_events_l_english.yml` - Eventos de combate singular
- `terrains_l_english.yml` - Terrenos
- `traits_ate_l_english.yml` - Rasgos

### Archivos de Reglas del Juego y Configuraciones

- `zz_game_concepts_l_spanish.yml` - Conceptos de juego (español)
- `ate_game_rules_l_english.yml` - Reglas del juego (Pendiente de Traducir)

### Documentación

- `README.md` - Archivo de lectura
- `estructura.md` - Estructura de las carpetas y archivos importantes del mod
- `CHANGELOG.md` - Archivo de Versiones de la traducción del mod
- `CONTRIBUTING.md` - Cómo contribuir a la traducción
- `LICENSE.md` - Licencia del mod original After The End

## 🎯 Categorización por Tipo de Contenido

### Localizaciones Básicas del Juego

Ubicadas principalmente en `event_localization/` y archivos YAML raíz

### DLC y Expansiones

Organizadas en `dlc/` con subcarpetas para cada DLC/parche

### Sistemas de Juego Específicos

- Gobiernos: `governments/`
- Cultura: `culture/`
- Religión: `religion/` (incluyendo doctrinas)
- Mercenarios: `mercenarios_l_english.yml` y carpetas de DLC
- Artefactos: `artifacts/`
- Combate: `wars/`, `single_combat_events_l_english.yml`

### Interfaz y Experiencia de Usuario

- GUI: `gui/`
- Tutorial: `tutorial/`
- Custom Localization: `custom_localization/`

---

## 📊 Estadísticas

- **Carpetas principales:** 33
- **Subcarpetas:** 50+
- **Archivos YAML de localización:** 388
- **Idiomas:** Español
- **Mods compatibles:** A Futuro se planea la compatibilidad con CBO

---

**Última actualización:** 29 Diciembre 2025
