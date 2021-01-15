Processo de Code Review

O objetivo do Code Review não é sugerir alterações para que o código fique perfeito, e sim, um código melhor.

Lei de Linus
"Dados olhos suficientes, todos os erros são óbvios" (Given enough eyeballs, all bugs are shallow)"

Com um grande número de colaboradores, erros em sistemas tendem a ser detectados e corrigidos mais facilmente. Este é o propósito principal
do nosso Code Review - rever o código do colega para garantir que as boas práticas estejam sendo usadas, que possíveis falhas que possam ter 
escapado do desenvolvedor principal da solução sejam evidenciadas e corrigidas, e ajudar a todos os envolvidos a garantir que a solução
aplicada esteja de fato resolvendo o que precisa ser resolvido.
Com a prática de Code Review, esperamos:

- Diminuir incidência de bugs
- Melhorar a qualidade do código
- Compartilhar conhecimento e experiências
- Uniformidade e padronização de código


O que deve ser verificado durante o processo de Code Review?

- Erros ortográficos
- Organização da solução
- Códigos ou parâmetros hard-coded
- Complexidade da solução
- Clean Code
- Possíveis melhorias com SOLID
- Melhorias de performance e segurança
- Bugs em potencial ou possíveis erros de fluxo para a solução desejada
- Padrões e Convenção de código

Checklist

- Revise seu próprio código
	- Verifique as mudanças que estão sendo enviadas para aprovação, e se só o necessário está subindo;
	- Verifique se o projeto todo está buildando corretamente, e se todos os testes unitários estão passando;
	
- Resumo de alterações
	- Escreve um changelog de forma resumida, para que fique claro o porquê e o quê está sendo enviado para aprovação
- O código possui testes unitários?
- O 
	
Aprovação
Todo Code Review deverá possuir ao menos 1 aprovação para ser elegível de merge e então seguir a esteira de integração e deploy.

Deadline
Para evitar gargalos, todo pull request poderá ser mergeado sem nenhuma aprovação no decorrer de 8h úteis ou em caráter de exceções, desde que
todo merge seja notificado

Pull Request

- Evitar criar um pull request que abrange mais de uma solução, implementação ou correção
- Descrever no Pull Request o objetivo da entrega (História relacionada, problema/solução, TODOs etc)
- Utilizar uma branch para cada história/tarefa no quadro do Jira; O nome da branch deve ser o identificador da task no Jira


