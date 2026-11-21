# Como contribuir / How to contribute

[Português (Brasil)](#português-brasil) · [English](#english)

## Português (Brasil)

Obrigado pelo interesse! Leia o [Código de Conduta](CODE_OF_CONDUCT.md) antes de participar.

### Relatar um problema ou sugerir algo

1. Procure nas issues do repositório se já existe algo igual.
2. Abra uma issue usando o modelo (problema ou sugestão), com versões, ambiente e passos para reproduzir.
3. Para **vulnerabilidades**, não abra issue pública: siga o [`SECURITY.md`](SECURITY.md).

### Enviar código

1. Abra (ou comente) uma issue antes de uma mudança grande.
2. Faça um *fork* e crie uma branch a partir da `main` (sugestão: `issues/<número da issue>`).
3. Siga o estilo e os linters do repositório (veja o `README.md` e o `.pre-commit-config.yaml`, quando houver).
4. Escreva ou atualize os **testes**, a **documentação** e o `CHANGELOG.md`.
5. Abra o pull request. O CI precisa passar.

### Mensagens de commit

Usamos *Conventional Commits* detalhados, em português: `tipo(escopo): [TAG] Descrição no imperativo`, com `[ADD]`,
`[FIX]`, `[UPD]`, `[DEL]` ou `[UPG]`, e um corpo com **Motivo**, **Impacto** e **Arquivos/Mudanças**. Contribuições em
inglês também são aceitas.

### Licença

Ao contribuir, você concorda que seu código será distribuído sob a licença do repositório (arquivo `LICENSE`).

## English

Thanks for your interest! Please read the [Code of Conduct](CODE_OF_CONDUCT.md) first.

### Report a problem or suggest something

1. Search the repository's issues for duplicates.
2. Open an issue using the template (bug or suggestion), with versions, environment and steps to reproduce.
3. For **vulnerabilities**, do not open a public issue: follow [`SECURITY.md`](SECURITY.md).

### Send code

1. Open (or comment on) an issue before a large change.
2. Fork and branch from `main` (suggestion: `issues/<issue number>`).
3. Follow the repository's style and linters (see its `README.md` and `.pre-commit-config.yaml`, when present).
4. Write or update the **tests**, the **documentation** and `CHANGELOG.md`.
5. Open the pull request. CI must pass.

### Commit messages

We use detailed Conventional Commits, in Portuguese: `type(scope): [TAG] Imperative description`, with `[ADD]`,
`[FIX]`, `[UPD]`, `[DEL]` or `[UPG]`, and a body with **Motivo** (reason), **Impacto** (impact) and
**Arquivos/Mudanças** (files/changes). English contributions are welcome too.

### License

By contributing you agree that your code is distributed under the repository's license (`LICENSE` file).
