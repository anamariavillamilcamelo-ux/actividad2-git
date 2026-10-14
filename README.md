# Actividad 2 - Hands on: configuración de herramientas

Repositorio de la Actividad 2, cuyo objetivo es utilizar herramientas colaborativas básicas de software usadas en proyectos de ciencia de datos: Git y GitHub.

**Autora:** Ana Maria

## Descripción

En este repositorio se documenta un tutorial de Git, elaborado en Microsoft Word a partir del libro oficial *Pro Git* (https://git-scm.com/book/es/v2). Cada capítulo del libro se redactó en un documento de Word independiente y se exportó también a PDF.

## Proceso seguido

1. **Cuenta en GitHub:** se utilizó la cuenta existente `anamariavillamilcamelo-ux`.
2. **Instalación de Git:** se verificó con `git --version`.
3. **Configuración de identidad:** se definieron `user.name` y `user.email` con `git config --global`.
4. **Creación del repositorio:** se creó `actividad2-git` en GitHub con un README inicial.
5. **Clonación:** se clonó con `git clone` en la carpeta `Documents` del equipo local.
6. **Elaboración de documentos:** se redactó un documento de Word por capítulo y se exportó a PDF.
7. **Control de cambios:** por cada capítulo se ejecutó el ciclo:
   - `git add` para agregar los archivos
   - `git commit -m "..."` para confirmar con un mensaje descriptivo
   - `git push origin main` para enviar los cambios a GitHub

## Documentos del repositorio

| Cap. | Documento | Formatos |
|------|-----------|----------|
| 1 | Inicio - Sobre el Control de Versiones | .docx / .pdf |
| 2 | Fundamentos de Git | .docx / .pdf |
| 3 | Ramificaciones de Git | .docx / .pdf |
| 4 | Git en el Servidor | .docx / .pdf |
| 5 | Git en entornos distribuidos | .docx / .pdf |
| 6 | Creación y configuración de la cuenta | .docx / .pdf |
| 7 | Herramientas de Git | .docx / .pdf |
| 8 | Personalización de Git | .docx / .pdf |
| 9 | Git y Otros Sistemas | .docx / .pdf |
| 10 | Los entresijos internos de Git | .docx / .pdf |

## Historial de cambios

| Commit | Mensaje | Cambio realizado |
|--------|---------|------------------|
| f07ca4c | Agrega descripción inicial al README | Se editó el README inicial |
| a2a411b | Agrega tutorial del capítulo 1: Inicio | Se agregó el capítulo 1 (.docx y .pdf) |
| d0a4131 | Confirmación de cap2 | Se agregó el capítulo 2 |
| 8a06fee | Confirmación de cap3 | Se agregó el capítulo 3 |
| dbf226f | Confirmación de cap4 | Se agregó el capítulo 4 |
| ed449bf | Confirmación de cap5 | Se agregó el capítulo 5 |
| c47fb20 | Confirmación de cap6 | Se agregó el capítulo 6 |
| b432d98 | Confirmación de cap7 | Se agregó el capítulo 7 |
| debfb5c | Confirmación de cap8 | Se agregó el capítulo 8 |
| e10966d | Confirmación de cap9 | Se agregó el capítulo 9 |
| 6c8d564 | Confirmación de cap10 | Se agregó el capítulo 10 |

## Comandos utilizados

```bash
git --version
git config --global user.name "Ana Maria"
git config --global user.email "correo@ejemplo.com"
git clone https://github.com/anamariavillamilcamelo-ux/actividad2-git
git status
git add "<archivo>"
git commit -m "<mensaje>"
git push origin main
git log --oneline
```

## Dificultades y soluciones

- **Error `src refspec mai does not match any`:** un error de digitación al escribir la rama en `git push`. Se corrigió usando `git push origin main`.
- **Nombres de archivo con espacios y tildes:** se solucionó escribiendo los nombres entre comillas en `git add`.
- **Archivos temporales de Word (`~$...`):** aparecían como archivos sin seguimiento; no se agregaron al repositorio.