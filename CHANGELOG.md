# Changelog

Todas as mudanças importantes deste projeto serão documentadas neste arquivo.


## v0.0.0 - 2026-07-22



### Outras alterações


- Update manifest.json

- Update manifest.json

- Change commit sort order to newest

Update cliff.toml configuration to sort commits in reverse chronological order (newest first) instead of oldest first.

- Automate changelog and release workflow

Refactored the changelog workflow to automatically detect version changes from manifest.json, create git tags for new versions, and generate GitHub releases with changelog notes. Replaced manual cargo installation with the orhun/git-cliff-action for improved reliability.

- Add changelog workflow and git-cliff config

Add .github/workflows/changelog.yml and cliff.toml. Workflow runs on pushes to main, installs git-cliff via cargo, generates CHANGELOG.md and auto-commits it using stefanzweifel/git-auto-commit-action with message 'docs: atualiza CHANGELOG.md [skip ci]'. cliff.toml defines header/body templates, enables conventional commits parsing, maps commit types to Portuguese headings (with emojis), and sets git-cliff options including tag pattern v[0-9]*.

- Initial commit


### ♻️ Refatoração


- mod folder and update README/manifest


### 📚 Documentação


- Add alchemist recipes to README

- Add changelog and roadmap to README

- atualiza CHANGELOG.md [skip ci]


### 🔧 Manutenção


- Remove example configurations from content.json

- Reset version to 0.0.0

- Restructure mod files and update manifest


