# github-setup-skill

[![Release](https://img.shields.io/github/v/release/fxckcode/github-setup-skill?sort=semver)](https://github.com/fxckcode/github-setup-skill/releases)
[![License](https://img.shields.io/github/license/fxckcode/github-setup-skill)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/fxckcode/github-setup-skill)](https://github.com/fxckcode/github-setup-skill/commits/main)

Current version: v0.1.0

Skill experta en preparar el setup basico de repositorios Git/GitHub: `.gitignore`, `.gitattributes`, README con valor, licencias, metadata del repo, tags y releases, y GitHub Actions profesionales con testing.

## Purpose

La skill reemplaza configuraciones ad-hoc con un flujo guiado que:

- revisa el repo antes de escribir
- pregunta solo lo necesario
- crea o refina archivos base de calidad
- añade automatizaciones con GitHub Actions
- deja reglas claras para releases y tags

## Skill Files

- `SKILL.md`
- `references/triggers.md`
- `references/workflow.md`
- `references/templates.md`
- `references/github-actions.md`
- `references/releases.md`
- `references/licenses.md`
- `references/repo-metadata.md`
- `references/testing.md`
- `scripts/README.md`

## Install

Copia esta carpeta dentro de tu directorio de skills. Ejemplo:

```bash
cp -R git-setup-skill "$HOME/.agents/skills/git-setup-skill"
```

## Usage

Frases de activacion tipicas:

- "necesito un buen .gitignore"
- "quiero un README con valor"
- "configura GitHub Actions"
- "prepara releases y tags"
- "ponle licencia al repo"

## What it produces

- `.gitignore` y `.gitattributes` adecuados al stack
- `README.md` con secciones utiles
- `LICENSE` segun la licencia elegida
- `CODE_OF_CONDUCT.md` / `SECURITY.md` si aplica
- workflows de GitHub Actions para CI y releases
- metadata del repositorio (descripcion, topics)

## Compatibility

- Requiere `git` y `gh` para tareas de metadata y releases.
- En Windows, usa una shell compatible con `bash` si se agregan scripts.

## Contributing

Ver `CONTRIBUTING.md`.
