# Exemplo de Trabalho com Git em Equipes


## Organização
*Team Leader*
vai criar/manter o repositório onde o projeto está hospedado.
Neste repositório há apenas 2 branches
- Main - onde será publicada a versão oficial do site
- Develop - onde estarão permitidas as operações de desenvolvimento de software, ou seja: novas funcionalidades serão adicionadas a partir da branch develop e se tudo estiver OK, fazemos a integração (merge) com a Branch MAIN

*Developers*
Devem criar um FORK do repositório que irá vincular o repositório criado ao repositório original
Cada dev trabalha sempre na branch develop 

*Modelo de trabalho:*
- Cada DEV inicialmente tem que vincular o repositório ORIGINAL ao seu repo local (clonando-o ou mesmo inicializando) para estar apto a receber as atualizações
- Uma vez trabalhando no seu repo local, é imprescindível
     1. Solicitar as atualizações do repo principal
     2. Fazer as suas tarefas
     3. Fazer o PUSH para o SEU repo (da SUA conta)
     4. Abrir um Pull Request solicitando que o Tem Leader avalie se código e incorpore suas alterações na branch develop

Testando o push