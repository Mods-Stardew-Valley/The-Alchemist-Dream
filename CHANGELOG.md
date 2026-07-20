# Changelog

Todas as mudanças importantes deste projeto serão documentadas neste arquivo.


## Unreleased



### Outras alterações


- Initial commit

- Add changelog workflow and git-cliff config

Add .github/workflows/changelog.yml and cliff.toml. Workflow runs on pushes to main, installs git-cliff via cargo, generates CHANGELOG.md and auto-commits it using stefanzweifel/git-auto-commit-action with message 'docs: atualiza CHANGELOG.md [skip ci]'. cliff.toml defines header/body templates, enables conventional commits parsing, maps commit types to Portuguese headings (with emojis), and sets git-cliff options including tag pattern v[0-9]*.


### ♻️ Refatoração


- mod folder and update README/manifest


