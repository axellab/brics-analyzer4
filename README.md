# Demo GitHub Actions - Análisis BRICS

Este proyecto demuestra el uso de **GitHub Actions** para automatizar workflows de CI/CD.

## 📊 ¿Qué hace?

Analiza datos de países BRICS (Brasil, Rusia, India, China, Sudáfrica) usando:
- **Python 3.9**
- **Pandas** para análisis de datos
- **GitHub Actions** para automatización

## 🔄 Workflows

### `basic-ci.yml`
- **Trigger**: Push y Pull Request a main
- **Runner**: ubuntu-latest
- **Acciones**: Install → Test → Run

## 🚀 Ejecución automática

Cada vez que:
- Haces `git push` a main
- Abres un Pull Request
- El workflow se ejecuta automáticamente

## 📋 Resultados

El programa calcula:
- Población total de países BRICS
- Área total
- País más poblado
- País con mayor área
- Información del entorno de ejecución

## 🔗 Ver workflows

- Ve a la pestaña **Actions** de este repositorio
- Observa los workflows en ejecución
- Revisa los logs detallados
