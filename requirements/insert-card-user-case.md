# Inserir Card

> ## Caso de sucesso
1. Sistema executa o comando "Inserir"
2. Sistema valida se os campos Título, Conteúdo e Nome da Lista foram preenchidos e garanta que o id não pode vir preenchido
3. Sistema salva o card
4. Sistema retorna o card salvo com todos os atributos

> ## Exceção - Campo obrigatório não preenchido
1. Sistema valida os campos obrigatórios
2. Sistema retorna erro

> ## Exceção - Id preenchido
1. Sistema ignora se o id foi preenchido e insere um novo id 