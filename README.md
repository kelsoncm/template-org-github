<!-- template:start -->
# template-org-github

Template do repositório `.github` de uma organização: perfil público (`profile/README.md`) e arquivos de saúde da
comunidade que valem para todos os repositórios sem versão própria (código de conduta, contribuição, suporte,
segurança, modelos de issue e de pull request), bilíngues.

## Como usar

1. **Use this template > Create a new repository** com o nome exato `.github`, **público**, dentro da organização.
2. Clone e rode o inicializador (só biblioteca padrão do Python 3.10+):

   ```bash
   python template_init.py --title "Minha Suite" --contact-email contato@exemplo.org \
     --tagline-en "..." --tagline-pt "..."
   ```

3. Liste os repositórios da organização na tabela de `profile/README.md`.

Os arquivos são genéricos. Para uma família de plugins Moodle, acrescente ao modelo de bug os campos de versão do
Moodle, PHP e banco de dados, e ao `CONTRIBUTING.md` as convenções do Moodle (AMOS, Privacy API, `amd/build`).

---
<!-- template:end -->
# .github

Repositório comunitário e de perfil da organização **{{TITLE}}**.

| Arquivo | Uso |
|---|---|
| `profile/README.md` | Página de perfil da organização |
| `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SUPPORT.md`, `SECURITY.md` | Padrões para todos os repositórios sem versão própria |
| `.github/ISSUE_TEMPLATE/`, `.github/PULL_REQUEST_TEMPLATE.md` | Modelos de issue e de pull request |
