# Descrição do programa
Para este programa, foi feita um código especializado em otimizar o tempo do usuarío, gerenciando assim uma lista de tarefas que ordena e priopriza as tarefas a serem completadas.

O programa é capaz de armazenar até 100 tarefas e permitir que o usuário cadastre, delete e liste as tarefas. O usuario digita cada tarefa que deve conter uma descrição, uma categoria e uma prioridade (quanto maior o valor, maior a prioridade da tarefa).

# Estrutura de criação
* O programa foi realizado em linguagem C
  
* Prioridade da tarefa (valor inteiro entre 0 e 10)

* Descrição da tarefa (array de char de até 300 letras)

* Categoria (array de char de até 100 letras)

# Atualização do sistema e funções implementadas

* Adicionado o tratamento de erros

* Modificação na função listar

* Carregamento e Salvamento de usuário

* Exportar lista 

* Definir variaves fixas

* Limite de propriedade adicionado

* Erro de quebra de linha solucionado

# Guia para usuário 

# Inicialização

Ao iniciar o progama vai ser perguntado ao usuario de qual arquivo carregar os dados(se o usuario deixar o campo vazio os dados serão carregados de um arquivo padrão).

# Menu

O menu sera apresentado para o usuário da segunte maneira

* Menu Principal
* 1 - Criar Tarefa
* 2 - Deletar Tarefa
* 3 - Listar Tarefa
* 0 - Sair
* Escolha uma opção:

#  1- Criar Tarefa

Se o usuario selecionar o número "1" no teclado, ele sera direcionado para as seguntes perguntas: 

* Entre com a prioridade(0 a 10) // Exigindo assim que o usuário entre com a prioridade desejada.
* Entre com a categoria: // Exigindo assim o tema do trabalho
* Entre com a descrição: // Exigindo assim que o usuário entre com um breve resumo sobre a tarefa

#  2 - Deletar Tarefa

Se o usuario selecionar o número "2" no teclado, ele vai deletar alguma tarefa que não deseja mais, e sera direcionado para a pergunta: 

* Entre com a posição da tarefa a ser deletada:

E assim que o usuário digitar a posição, a tarefa sera excluida

# 3 - Listar Tarefas

Se o usuario selecionar o número "3" no teclado, ele vai ser vai entrar na função de listamento de tarefas.
O progama pedira uma categoria para ser listada (ou nenhuma e lista todas), ao selecionar a categoria, o progama lista todas as tarefas com essa categoria.
O usuario tem a opção de salvar essa lista em um txt.

# 0 - Sair

Se o usuario selecionar o número "0" no teclado, ele vai sair do programa.
Antes do progama fechar ele vai perguntar ao usuario qual arquivo salvar os dados(se o usuario deixar o campo vazio os dados serão salvos em um arquivo padrão).



  




