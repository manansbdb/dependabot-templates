<p align="center">
  <img src="docs/banner.svg" alt="Dependabot Templates banner" width="100%" />
</p>

<h1 align="center">dependabot-templates</h1>

<p align="center">
  <strong>EN</strong> Example dependabot.yml for npm, Actions & more<br/>
  <strong>PT</strong> Exemplos dependabot.yml para npm, Actions e mais
</p>

<p align="center">
  <a href="https://github.com/manansbdb/dependabot-templates/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/topic-Dependabot-0366d6?style=for-the-badge" alt="Dependabot" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| Ready **Dependabot** YAML examples (npm + Actions, multi-ecosystem). | Exemplos YAML **Dependabot** prontos (npm + Actions, multi-ecossistema). |
| Copy into `.github/dependabot.yml` and adjust directories/schedules. | Copia para `.github/dependabot.yml` e ajusta diretórios/schedules. |

```mermaid
flowchart LR
  A["📅 Schedule"] --> B["🤖 Dependabot"]
  B --> C["📬 PR updates"]
  C --> D["✅ Review & merge"]
  style A fill:#f59e0b,stroke:#b45309,color:#fff
  style B fill:#0366d6,stroke:#024ea4,color:#fff
  style C fill:#8b5cf6,stroke:#6d28d9,color:#fff
  style D fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/dependabot-templates.git
cd dependabot-templates
```

### 2) Apply / Aplica

```bash
mkdir -p /path/to/your-project/.github
# pick one:
cp examples/npm-and-actions.yml /path/to/your-project/.github/dependabot.yml
# or:
cp examples/multi-ecosystem.yml /path/to/your-project/.github/dependabot.yml
cp notes.md /path/to/your-project/docs/dependabot-notes.md
```

### Requirements / Requisitos

- `git`
- GitHub repository with Dependabot enabled

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/dependabot-templates.git
mkdir -p .github
cp dependabot-templates/examples/npm-and-actions.yml .github/dependabot.yml
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `examples/npm-and-actions.yml` | npm + Actions |
| `examples/multi-ecosystem.yml` | Multi ecosystem |
| `notes.md` | Tuning tips |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
dependabot-templates/
├── docs/banner.svg
├── examples/npm-and-actions.yml
├── examples/multi-ecosystem.yml
├── notes.md
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
