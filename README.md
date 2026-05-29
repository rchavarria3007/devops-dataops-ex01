# Visão Geral

Este projeto demonstra um pipeline simples de **CI/CD** utilizando **GitHub Actions** para automatizar validações, testes básicos e publicação de uma página estática no **GitHub Pages**.

O objetivo é mostrar, de forma prática, como fluxos automatizados ajudam a manter qualidade, padronização e rapidez no desenvolvimento.

---

# Estrutura do Projeto

A estrutura de pastas é a seguinte:
seu-projeto/
│
├── site/
│   └── index.html        # Página estática publicada no GitHub Pages
│
└── .github/
└── workflows/
├── ci.yml        # Pipeline de Integração Contínua (CI)
└── cd.yml        # Pipeline de Deploy Contínuo (CD)

## Descrição dos Arquivos

### 📁 `site/index.html`
Página HTML simples que será publicada automaticamente no GitHub Pages.

### 📁 `.github/workflows/ci.yml`
Workflow responsável por:
- Validar arquivos
- Executar testes simples
- Garantir consistência antes do deploy

### 📁 `.github/workflows/cd.yml`
Workflow responsável por:
- Gerar artefatos do site
- Publicar automaticamente no GitHub Pages

---

Esse README descreve apenas a estrutura necessária para o funcionamento do pipeline.
