# Localization Directory Structure from Spanish Translation (English)

## General Overview

This directory contains all localization and translation files for the mod, organized by functional categories and content modules.

---

## 📁 Main Folder Structure

### Special Content Folders

- **00 Adoption Options/** – Adoption options  
- **00 Cities of Wonder/** – COW Mod by Valaddar
- **00 Community Culture Utility/** – CCU Mod by Vertimnus

### Game Mechanics Folders

- **accolades/** – Accolades and achievements  
- **activities/** – Activities  
- **artifacts/** – Artifacts  
- **bookmark/** – Bookmarks  
- **commodities/** – Commodities  
- **culture/** – Culture (including the `traditions/` subfolder)  
- **custom_localization/** – Custom localization  
- **diarchies/** – Diarchies  
- **dynasties/** – Dynasties  
- **domiciles/** – Domiciles  

### Events and Decisions Folders

- **event_localization/** – Event localization  
  - `activities/` – Activity events  
  - `childhood_events/` – Childhood events  
  - `court_events/` – Court events  
  - `death_events/` – Death events  
  - `decisions/` – Decisions  
  - `experimental/` – Experimental events  
  - `hold_court_events/` – Hold court events  
  - `lifestyle/` – Lifestyle  
    - `governance/` – Governance  
    - `scholarship/` – Scholarship  
    - `warfare/` – Warfare  
  - `religion_events/` – Religious events  
  - `stress_events/` – Stress events  
  - `yearly_events/` – Yearly events  

### Thematic Folders

- **flavorization/** – Flavor text  
- **governments/** – Governments  
- **gui/** – Graphical user interface  
- **interactions/** – Interactions  
- **inventory/** – Inventory  
- **lifestyles/** – Lifestyles  
- **modifiers/** – Modifiers  
- **names/** – Names  
- **opinions/** – Opinions  
- **portraits/** – Portraits  
- **religion/** – Religion  
  - `doctrines/` – Doctrines  
- **situations/** – Situations  
- **struggles/** – Struggles  
- **titles/** – Titles  
- **travel/** – Travel  
- **triggers/** – Triggers  
- **tutorial/** – Tutorial  
- **wars/** – Wars  

### DLC Folders

- **dlc/bp2/** – Basegame Patch 2  
- **dlc/bp3/** – Basegame Patch 3  
- **dlc/ce1/** – Community Edition 1  
- **dlc/ep1/** – Expansion Pack 1  
- **dlc/ep3/** – Expansion Pack 3  
- **dlc/fp1/** – Featured Pack 1  
- **dlc/fp2/** – Featured Pack 2  
- **dlc/fp3/** – Featured Pack 3  
- **dlc/mpo/** – Music Pack Overture  

---

## 📄 Main Localization Files

### Base Files (ATE – Advanced Terrains Expansion)

- `00_ate_deaths_l_spanish.yml` – Death localizations (Spanish)  
- `ate_activities_l_spanish.yml` – Activities (Spanish)  
- `ate_board_game_events_l_english.yml` – Board game events  
- `ate_buildings_l_english.yml` – Buildings  
- `ate_buildings_overwrite_l_english.yml` – Building overrides  
- `ate_california_l_english.yml` – California content  
- `ate_character_l_english.yml` – Characters  
- `ate_commodites_l_english.yml` – Commodities  
- `ate_contracts_l_english.yml` – Contracts  
- `ate_council_tasks_l_english.yml` – Council tasks  
- `ate_court_authority_laws_l_english.yml` – Court authority laws  
- `ate_domicile_buildings_l_english.yml` – Domicile buildings  
- `ate_elective_succession_l_english.yml` – Elective succession  
- `ate_epidemics_l_english.yml` – Epidemics  
- `ate_focuses_l_english.yml` – Focuses  
- `ate_game_concepts_l_english.yml` – Game concepts  
- `ate_game_concepts_religions_l_english.yml` – Religion concepts  
- `ate_glossary_l_english.yml` – Glossary  
- `ate_holy_order_l_english.yml` – Holy orders  
- `ate_imperial_faction_l_english.yml` – Imperial faction  
- `ate_important_actions_l_english.yml` – Important actions  
- `ate_interactions_l_english.yml` – Interactions  
- `ate_memories_l_english.yml` – Memories  
- `ate_mercenaries_south_america_l_english.yml` – South American mercenaries  
- `ate_music_l_english.yml` – Music  
- `ate_nomads_l_english.yml` – Nomads  
- `ate_nomad_decisions_l_english.yml` – Nomad decisions  
- `ate_succession_laws_l_english.yml` – Succession laws  
- `ate_traits_replace_l_english.yml` – Traits (replacement)  
- `ate_weapon_portrait_modifiers_l_english.yml` – Weapon portrait modifiers  

### Complementary Mod Files

- `borrowed_rice_misc_l_english.yml` – Miscellaneous  
- `court_positions_l_english.yml` – Court positions  
- `equal_exchange_locs_l_english.yml` – Equal exchange  
- `government_replace_l_english.yml` – Governments (replacement)  
- `hcc_succession_laws_l_english.yml` – Succession laws (HCC)  
- `knight_culture_l_english.yml` – Knight culture  
- `mercenaries_l_english.yml` – Mercenaries  
- `More's_lore_l_english.yml` – Additional lore  
- `morereligions_game_concepts_hostilities_l_english.yml` – Religion and hostility concepts  
- `nicknames_ate_l_english.yml` – Nicknames  
- `regions_l_english.yml` – Regions  
- `religion_replace_l_english.yml` – Religion (replacement)  
- `religion_salvager_l_english.yml` – Religion salvager  
- `salvage_artifact_modifiers_l_english.yml` – Salvaged artifact modifiers  
- `signature_weapon_custom_loc_l_english.yml` – Signature weapon custom localization  
- `single_combat_events_l_english.yml` – Single combat events  
- `terrains_l_english.yml` – Terrains  
- `traits_ate_l_english.yml` – Traits  

### Spanish-Specific Files

- `zz_game_concepts_l_spanish.yml` – Game concepts (Spanish)  
- `ate_game_rules_l_english.yml` - Game Rules (Pending translation)

### Documentation

- `README.md` – Readme file  
- `estructure.md` – Estructure folders and importants mod files
- `CHANGELOG.md` - Translation Version Archive
- `CONTRIBUTING.md` - How to Contribute to the Translation
- `LICENSE.md` - License of the Original Mod After the End

---

## 📊 Statistics

- **Main folders:** 33  
- **Subfolders:** 50+  
- **Localization YAML files:** 54+  
- **Languages:** Spanish and English  
- **Compatible mods:** ATE, HCC, and others  

---

## 🎯 Categorization by Content Type

### Core Game Localization

Mainly located in `event_localization/` and root YAML files

### DLCs and Expansions

Organized under `dlc/` with subfolders for each DLC/patch

### Specific Game Systems

- Governments: `governments/`  
- Culture: `culture/`  
- Religion: `religion/` (including doctrines)  
- Mercenaries: `mercenaries_l_english.yml` and DLC folders  
- Artifacts: `artifacts/`  
- Combat: `wars/`, `single_combat_events_l_english.yml`  

### User Interface and User Experience

- GUI: `gui/`  
- Tutorial: `tutorial/`  
- Custom Localization: `custom_localization/`  

---

**Last updated:** 29 December 2025
