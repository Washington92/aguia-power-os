# Águia Power

Protótipo navegável do sistema de gestão de ordens de serviço do **Grupo Águia Power**, feito em um único arquivo (`index.html`), sem instalação.

## Como abrir

Abra o `index.html` em qualquer navegador. Não precisa de servidor nem de internet (só as fontes do Google ficam em fallback se estiver offline).

## O que já tem

- **Dashboard:** totais de OS, gráfico por status, ordens recentes e próximas visitas.
- **Ordens de Serviço:** busca, filtros por status, criação em 4 passos (Cliente, Serviço, Equipe, Resumo), edição e exclusão. Coluna de técnico e situação do checklist.
- **Checklist (aba dentro da OS):** todos os campos da Ficha de Check-List, fotos (mínimo de 3), lista de materiais ligada aos produtos cadastrados, assinatura em pop-up de tela cheia e impressão no formato da ficha em PDF.
- **Agenda:** lista, calendário mensal e linha do tempo por técnico, com criação e edição de visitas.
- **Clientes, Unidades (com Sigla e Gerente), Produtos e Colaboradores:** cadastros editáveis.
- **Permissões:** perfis de Administrador e Técnico (a mesma pessoa pode ter os dois), acesso por tela e por ação.

## Publicar no GitHub Pages

1. Envie o `index.html` para a raiz de um repositório.
2. Em **Settings → Pages**, escolha o branch `main` e a pasta `/ (root)`.
3. O link aparece na mesma tela após 1 ou 2 minutos.

## Limitações do protótipo

- Os dados ficam só na memória da página e **somem ao recarregar**.
- Ainda não há login. As permissões são aplicadas na tela, mas não protegem nada no servidor.

## Próximos passos

- Ligar ao Firebase (login por pessoa, dados salvos e regras de segurança no servidor).
- Ajustar o visual conforme as telas de referência.
