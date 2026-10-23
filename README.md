# Guia Prático: Como Abrir e Acompanhar Chamados no Jira

Este documento foi criado para auxiliar usuários finais no processo de abertura, detalhamento e acompanhamento de chamados (tickets) de suporte. O objetivo é garantir que a equipe técnica receba todas as informações necessárias para uma investigação ágil e assertiva.

## 1. Como Abrir um Novo Chamado
1. Acesse o painel principal do Jira e clique no botão azul **Criar** na barra de navegação superior.
2. No campo **Projeto**, selecione `[Fictício] Suporte - Planejamento Comercial`.
3. No campo **Tipo de item**, escolha **Bug** (para erros no sistema) ou **Solicitação de Suporte** (para dúvidas de acesso).

## 2. Preenchendo os Detalhes (Boas Práticas)
Para que a equipe de triagem consiga atuar rapidamente, preencha os campos seguindo este padrão:

*   **Resumo:** Seja direto. *Exemplo: Erro de login na ferramenta de planejamento ao usar credenciais padrão.*
*   **Descrição:** Utilize a estrutura abaixo para detalhar o problema:
    *   **O que aconteceu:** A tela carrega infinitamente após inserir a senha.
    *   **O que era esperado:** O sistema deveria redirecionar para o dashboard de vendas.
    *   **Passos para reproduzir:** 1. Entrar na URL X; 2. Digitar o login; 3. Clicar em Entrar.
*   **Anexos:** Sempre inclua um print da tela inteira (mostrando a data e hora do computador) com a mensagem de erro.

## 3. Como Acompanhar o Status
Após criar o chamado, um número de identificação será gerado (ex: SUP-102). 
*   **A Fazer / Backlog:** O chamado foi registrado e está aguardando triagem pela equipe de projetos.
*   **Em Andamento:** Um analista já assumiu o caso e está investigando a causa raiz.
*   **Aguardando Cliente:** A equipe técnica solicitou mais informações. Verifique a seção de comentários do chamado.
*   **Concluído:** O problema foi resolvido ou a dúvida esclarecida.

> **Dica de Ouro:** Sempre verifique as notificações no seu e-mail corporativo, pois as atualizações do Jira disparam alertas automáticos para o solicitante.
