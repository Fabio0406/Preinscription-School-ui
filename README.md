# Preinscripción Escolar 2024 — Prototipo de interfaz

Prototipo web de un **formulario de preinscripción escolar** diseñado para la materia de Interacción Humano-Computador. Guía al tutor paso a paso: registra sus datos, luego los de cada estudiante (nuevo o antiguo) y al final muestra una vista previa antes de confirmar.

> Proyecto académico — Interacción Humano-Computador, UAGRM (2024).

## Flujo de pantallas

1. **Datos del tutor** (`Proyecto/index.html`): carnet, complemento, fecha, nombres y apellidos.
2. **Estudiante nuevo** (`Colegio_Estudiante.html`): departamento, colegio y datos del estudiante.
3. **Estudiante antiguo** (`Estudiante-antiguo.html`): datos para estudiantes que ya están inscritos.
4. **Finalizar** (`Finalizar.html`): vista previa de los estudiantes registrados y confirmación.

El botón **Continuar** se habilita solo cuando los campos obligatorios están completos.

## Tecnologías

- HTML5, CSS3, JavaScript
- jQuery
- Plantillas de Nicepage
- [intl-tel-input](https://github.com/jackocnr/intl-tel-input) para el campo de teléfono
- Bootstrap 5 (CDN)

## Estructura

```
index.html               # Redirige a Proyecto/index.html
Proyecto/                # Páginas del formulario y sus estilos
images/                  # Imágenes
intlTelInput/            # Librería del campo de teléfono
nicepage.css / .js       # Estilos y scripts base
jquery.js
```

## Requisitos

- Un navegador web (no necesita servidor)

## Cómo verlo

Abrir `index.html` en el navegador, o publicarlo con GitHub Pages (Settings → Pages → rama `main`).
