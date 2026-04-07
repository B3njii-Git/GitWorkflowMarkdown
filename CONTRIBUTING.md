# Guía de Contribución

¡Gracias por tu interés en colaborar en este proyecto de automatización! Para mantener el orden y la calidad del código, seguimos una serie de pasos obligatorios.

## 🛠️ Proceso de Desarrollo

1. **Sincroniza tu repositorio**: Antes de empezar, asegúrate de estar en la rama `develop` y tener los últimos cambios.
2. **Crea una rama de función**: Usa nombres descriptivos para tus ramas, por ejemplo: `feature/nombre-de-tu-mejora`.
3. **Realiza tus cambios**: Asegúrate de seguir los estándares de formato.

## 📏 Estándares de Documentación (Markdown)

[cite_start]Este proyecto utiliza **GitHub Actions** para validar la sintaxis de todos los archivos Markdown[cite: 49]. 
* [cite_start]No se permiten errores de formato en los archivos `.md`[cite: 68].
* [cite_start]Debes respetar las reglas configuradas en el archivo `.markdownlint.json` de la raíz[cite: 69, 82].

## 🔄 Envío de Pull Requests

Para que tu código sea integrado, debes abrir un **Pull Request (PR)**:
* [cite_start]El PR debe ir dirigido a la rama `develop`[cite: 54].
* [cite_start]El sistema de **CI (Integración Continua)** ejecutará automáticamente el linter.
* [cite_start]Si el workflow "Run Markdownlint" marca un error (círculo rojo), deberás corregir el formato y subir los cambios nuevamente hasta obtener el **check verde**[cite: 87].

---
[cite_start]*Este documento es parte de la Evaluación Práctica: Fundamentos de Git y Automatización.* [cite: 47]