# Service Desk Acadêmico

Aplicativo web estático feito em HTML, CSS e JavaScript para demonstrar versionamento de código em aula.

## Como abrir sem servidor

Este projeto não precisa de servidor local, Node.js, Python ou instalação de dependências.

Opção mais simples:

1. Dê dois cliques no arquivo `abrir-service-desk.bat`.
2. O navegador padrão abrirá o arquivo `index.html`.

Também é possível abrir diretamente o arquivo `index.html` com dois cliques.

## Funcionalidades

- Tela do usuário para abrir chamados.
- Painel do analista para selecionar chamados.
- Fila de atendimento ordenada por prioridade (Crítica, Alta, Média e Baixa), com os mais antigos primeiro em caso de empate.
- Alteração de status.
- Alteração de prioridade.
- Registro de correção.
- Histórico dos chamados em quadros Kanban organizados por status.
- Persistência simples usando `localStorage`.

## Arquivos principais

- `index.html`: estrutura das telas.
- `styles.css`: aparência do aplicativo.
- `app.js`: regras de interação e persistência local.
- `abrir-service-desk.bat`: atalho para abrir o app no navegador sem subir servidor.
