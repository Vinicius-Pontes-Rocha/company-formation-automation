# Company Formation Automation

> 🇧🇷 [Versão em português abaixo](#-português)

Validates the data submitted for a new company, creates the client folder structure by copying a template, and drafts the right type of articles of incorporation (single-member or multi-partner LLC), ready for the legal specialist to check.

```
Form ──► validation (partners, capital, activities) ──► copy template folder ──► generate contract (Docs) ──► specialist review
```

- 39-node workflow with explicit validation and a "bad data" path that explains what is missing
- Tested with single-member, multi-partner and invalid inputs before the pilot

**Stack:** n8n, Google Forms, Google Drive, Google Docs. Personal data and IDs were removed.

---

## 🇧🇷 Português

Confere os dados da abertura de empresa, cria a pasta do cliente copiando o modelo e gera o contrato social do tipo certo (Unipessoal ou Limitada), pronto para a especialista conferir. Testado com SLU, LTDA e dados inválidos. Workflow sanitizado.
