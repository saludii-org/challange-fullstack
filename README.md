# Desafio Full-Stack: Lista de Tarefas

## Requisitos

Neste desafio, você irá construir um app web de uma aplicação de lista de tarefas. Nesse desafio, você deve utilizar as seguintes tecnologias:

- RedwoodJS
- Material UI (@mui/material)
- dndkit
- tiptap ou simular
- socket.IO ou SSE


## Instruções de entrega

Você deve subir o código fonte em um repositório git privado e adicionar o usuário `@matheusAle` como um colaborador.


## Desafio

Este aplicativo tem como objetivo permitir que os usuários gerenciem suas tarefas diárias, podendo adicioná-las, atualizá-las, marcá-las como concluídas e excluí-las conforme necessário. Cada tarefa deve ter um texto descritivo e um status indicando se está pendente ou concluída bem como a data de quando foi criada e a data de da ultima modificação, caso tenha sido editada. 

Todas as tarefas cadastradas são públicas, portanto, qualquer pessoa pode criar ou mudar algo na lista de tarefas. Para uma melhor experiência, devemos replicar qualquer atualização nas tarefas para todos os usuários conectados.

### Funcionalidades

- Lista de Tarefas: Permite que o usuário veja todas as suas tarefas cadastradas. Deve mostrar o conteúdo bem como o status dessa tarefa.
- Filtrar Lista de Tarefas: Permite que o usuário visualize apenas as tarefas marcadas como concluídas.
- Criar Tarefa: O usuário pode criar uma nova tarefa. O conteúdo da tarefa pode ser em markdown suportando links, títulos, texto em itálico e negrito.
- Editar Tarefa: O usuário pode dar dois cliques em qualquer tarefa na lista e editar o seu conteúdo.
- Reordenar Tarefas: O usuário é livre para ordenar as tarefas como bem entender utilizando drag and drop.

### Instruções Gerais

- O campo de texto para criar/editar uma tarefa deve suportar edição de texto. Utilize o tiptap para implementar essas funcionalidades.
- Você está livre para usar qualquer outra biblioteca React no seu projeto.
- Você deve utilizar o máximo possível dos componentes e recursos do Material UI.
- *Dica*: Não salve a ordem das tarefas como um valor inteiro sequencial. Use um float ou dê um intervalo numérico arbitrário entre a última tarefa e a nova.
