# Draft de um caso de uso do Duolingo

Cenário:

Por algum motivo que o incomoda o usuário decide cancelar sua conta, porém o motivo some e o usuário passa a usar o aplicativo e esquece que mandou cancelar a conta.

Processo de cancelamento:

O processo de cancelamento demora 7 dias.

Ocorrido:

- Usuário pediu para cancelar a conta por conta de inconsistencia de dados
- O usuário percebeu que um dia depois essa incosistencia de dados tinha desaparecido
- O usuário esqueceu que mandou cancelar a conta
- O usuário passou a usar o aplicativo todos os dias ao menos uma hora
- A conta foi cancelada depois do prazo de 7 dias
- O usuário se viu frustrado perdendo todo seu histórico de rank


Questionamento:

Não deveria ter uma checagem para esses casos? Um usuári que faz o processo de cancelar a conta mas desiste e esquece de cancelar a conta.

O sistema não deveria usar os dados para pelo menos no último dia emitir um alerta máximo para o usuário perguntando se ele tinha certeza do cancelamento?