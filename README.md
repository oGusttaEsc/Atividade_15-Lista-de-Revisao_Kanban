Projeto: Sistema de Gerenciamento de Tarefas

Descrição:
Sistema web para cadastro e gerenciamento de tarefas. Permite criar usuários, associar tarefas e gerenciá-las (visualizar, editar, excluir e marcar como concluídas).

1. Diagrama Entidade-Relacionamento (DER)

Arquivo: docs/DER_Modelo_Logico.png

Entidades principais:

Usuário

id_usuario (PK)

nome

email

senha

Tarefa

id_tarefa (PK)

titulo

descricao

status (pendente/concluída)

data_criacao

data_limite

id_usuario (FK)

Relacionamento:
Um usuário pode ter várias tarefas, mas cada tarefa pertence a um único usuário (1:N).
