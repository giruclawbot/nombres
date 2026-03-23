# Guía de Contenido — Enciclopedia de Nombres

Cada nombre en `src/content/blog/` debe seguir **exactamente** esta estructura de secciones (en español).

---

## Frontmatter requerido

```md
---
title: 'NombreAquí'
description: 'Significado, origen y variantes del nombre NombreAquí.'
pubDate: 'Mar DD YYYY'
heroImage: '../../assets/blog-placeholder-N.jpg'  # rotar entre 1–5
---
```

---

## Estructura de secciones (obligatorias, en este orden)

### 1. Origen y Significado
Explicar el idioma/cultura de origen, las raíces etimológicas y el significado. Usar negritas para el nombre y bullet points para las raíces.

```md
## Origen y Significado

**Nombre** es un nombre de origen **X**, proveniente de *Y*.

*   Raíz 1 — significado.
*   Raíz 2 — significado.

Su significado se interpreta como **"..."**. Breve contexto cultural o histórico.
```

---

### 2. Variantes Internacionales
Lista de equivalentes en otros idiomas.

```md
## Variantes Internacionales

*   **Inglés:** ...
*   **Francés:** ...
*   **Alemán:** ...
*   **Italiano:** ...
*   **Portugués:** ...
*(incluir los idiomas que apliquen)*
```

---

### 3. Variantes Femeninas *(o Masculinas si el nombre es femenino)*
Formas del nombre en el género opuesto.

```md
## Variantes Femeninas

*   Nombre1
*   Nombre2 (idioma)
```

Si no existen variantes del género opuesto, indicarlo brevemente.

---

### 4. Personajes Históricos
Figuras de la historia (siglos pasados, política, realeza, ciencia, arte).

```md
## Personajes Históricos

*   **Nombre Completo:** Breve descripción (época/país).
*   **Nombre Completo:** Breve descripción.
```

Mínimo 2, máximo 4 entradas.

---

### 5. Personajes Famosos
Figuras contemporáneas (artistas, deportistas, actores, políticos recientes).

```md
## Personajes Famosos

*   **Nombre Completo:** Breve descripción (profesión/país).
*   **Nombre Completo:** Breve descripción.
```

Mínimo 2, máximo 4 entradas.

---

### 6. Dato Curioso
Un hecho interesante, estadística, tradición o curiosidad sobre el nombre.

```md
## Dato Curioso

Un párrafo breve con un dato interesante sobre el nombre: popularidad, etimología inusual, récord, tradición cultural, etc.
```

---

## Pie de página (obligatorio)

```md
---
*Este post es parte del proyecto diario de nombres de Giru.* 👾
```

---

## Notas adicionales

- Escribir todo en **español**, excepto las variantes internacionales que se dan en su idioma original.
- Los `heroImage` deben rotar entre `blog-placeholder-1.jpg` hasta `blog-placeholder-5.jpg` para variedad visual.
- El slug (nombre del archivo) debe ser el nombre en **minúsculas sin acentos**, ej: `enrique.md`, `guadalupe.md`.
- Evitar duplicar personas entre "Personajes Históricos" y "Personajes Famosos".
