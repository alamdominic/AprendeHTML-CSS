# 📘 Cheatsheet HTML

Una guía rápida con las principales etiquetas HTML, organizada por categorías. Ideal para estudiantes, desarrolladores principiantes o como referencia rápida.

---

## 🧩 Categorías incluidas

### 📌 Meta datos
- `<title>` — Título del documento (pestaña del navegador)
- `<meta>` — Información como charset, viewport, etc.
- `<link>` — Enlaces a recursos externos (como CSS)
- `<style>` — CSS dentro del HTML
- `<script>` — JavaScript

### 📝 Texto y encabezado
- `<h1>` al `<h6>` — Títulos jerárquicos
- `<p>` — Párrafo
- `<br>` — Salto de línea
- `<hr>` — Línea horizontal
- `<pre>` — Texto preformateado

### 🧱 Contenido Agrupado
- `<div>` — Contenedor general
- `<span>` — Contenedor en línea
- `<header>`, `<footer>`, `<main>`, `<section>`, `<article>`, `<aside>` — Estructura semántica
- `<nav>` — Navegación
- `<a>` — Enlaces (`href`, `target="_blank"`)

### ✍️ Formato de texto
- `<strong>`, `<b>` — Negrita
- `<em>`, `<i>` — Cursiva / énfasis
- `<u>` — Subrayado
- `<mark>` — Texto resaltado
- `<small>` — Texto pequeño
- `<sub>`, `<sup>` — Subíndice / superíndice
- `<code>` — Fragmento de código
- `<blockquote>`, `<q>`, `<cite>` — Citas
- `<abbr>` — Abreviaturas
- `<time>` — Fechas u horas

### 🖼️ Multimedia
- `<img>` — Imagen (`src`, `alt`, `width`, `height`)
- `<figure>` / `<figcaption>` — Figura con pie
- `<video>`, `<source>`, `<track>` — Video y subtítulos

### 📋 Listas
- `<ul>` / `<ol>` — Listas no ordenadas / ordenadas
- `<li>` — Elemento de lista
- `<dl>`, `<dt>`, `<dd>` — Lista de definición

### 📊 Tablas
- `<table>`, `<tr>`, `<th>`, `<td>` — Estructura de tabla
- `<thead>`, `<tbody>`, `<tfoot>` — Secciones
- `<caption>` — Título de la tabla

#### ✅ Ejemplo:
```html
<table border="1">
  <caption>Ejemplo de tabla</caption>
  <thead>
    <tr><th>Nombre</th><th>Edad</th></tr>
  </thead>
  <tbody>
    <tr><td>Juan</td><td>30</td></tr>
    <tr><td>Ana</td><td>25</td></tr>
  </tbody>
</table>
