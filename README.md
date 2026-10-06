# SISGED – MVP front-end

Versão estática do Sistema de Gestão Acadêmica (SESI SENAI), criada para a atividade de hospedagem em GitHub Pages e Cloudflare Pages.

## Como executar localmente
Abra `index.html` no navegador (ou use a extensão Live Server do VS Code).

## Estrutura
- `index.html` – entrada do MVP (perfil simulado)
- `dashboard.html`, `horarios.html`, `instrutores.html`, `salas.html`, `relatorios.html` – telas
- `assets/css`, `assets/js`, `assets/img` – estilos, scripts e imagens (caminhos relativos)

## Limitações do MVP
- Sem backend: não executa PHP e não se conecta a MySQL/MariaDB.
- Sem autenticação real: o login apenas escolhe um perfil de demonstração.
- Dados simulados em `assets/js/sisged.js`; cadastros, movimentações e edição ficaram de fora (exigem backend).
