# Cómo contribuir a la Traducción de ATE

## Quieres añadir archivos de traducción completados y funcionales

Para mantener estable la rama de desarrollo, no debes hacer commits directamente en ella. A continuación se describe el flujo de trabajo que debes seguir:

### Opción 1. Crear una nueva rama

Si eres un colaborador con acceso a este proyecto, **crea una nueva rama** a partir de la rama **`develop`** (puedes hacerlo desde GitHub o directamente desde tu repositorio local).  
> Si no eres un colaborador con acceso, puedes hacer un *fork* de este proyecto y trabajar en tus traducciones desde allí.

- Se recomienda nombrar tu rama como **`docs/nombre-conciso-carpeta-o-archivo`** para carpetas o archivos sin traducir o **`fix/nombre-conciso-carpeta-o-archivo`** para una corrección de errores en la traducción.

### OPCIÓN 2. Realizar un Fork del Repositorio

Ahora puedes empezar a trabajar en tus traducciones subiendo tus modificaciones a tu rama.

- Añade únicamente cambios que estén relacionados con la carpeta o archivos que quieres traducir.
- Commit: git commit -m "Traducción: [Carpeta/Tema]"

### Crear un pull request

Una vez que tu traducción esté terminada, o al menos sea estable y funcional (no cause cierres inesperados ni rompa contenido existente), puedes **crear un pull request** desde tu rama hacia la rama de desarrollo.

- Sigue las instrucciones de la plantilla.
- Añade un revisor al pull request (un changelog que explique los cambios y si es posible, notificar otro colaborador que ya haya trabajado en el código que estás modificando).

### Opción 3. Envío Directo

- Traduce los archivos .yml
- Envíalos a los administradores del proyecto vía discord, o steam:
  - Discord: liecshtein
  - Steam: 1259390514
- Incluye notas sobre cambios significativos o dudas
- Checklist Antes de Enviar
- Archivos en formato UTF-8
- Estructura YAML válida (sin errores de indentación)
- Consistencia terminológica verificada
- Sin traducciones incompletas o placeholders
- Probado en juego (si te es posible)

## 🎯 Guía para Contribuyentes

### Requisitos Previos

- Conocimiento de español correcto y contextualizado
- Familiaridad con el juego Crusader Kings III y sobretodo el mod *After The End*
- Editor de texto compatible con YAML (VS Code, Notepad++, etc.)
- Git (opcional pero recomendado)

### ¿Cómo Empezar?

1. **Identifica un archivo sin traducir**
   - Los archivos aún en inglés tienen el sufijo `_l_english.yml`. Por favor después de que completes la traducción del archivo, cámbialos por: `*_l_spanish.yml`
   - Prioriza archivos de las carpetas temáticas principales

2. **Estructura básica de un archivo .yml**

   ```yaml
   l_spanish:
     CLAVE_1: "Tu traducción aquí"
     CLAVE_2: "Otra traducción"
     DESCRIPCION_TITULO: "Descripción completa del concepto"
   ```
