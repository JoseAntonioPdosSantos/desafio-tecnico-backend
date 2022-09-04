# Update Card

> ## Caso de sucesso
1. Sistema executa o comando "Update"
2. Sistema valida se os campos Título, Conteúdo e Nome da Lista foram preenchidos
3. Sistema busca o card pelo id recebido como parâmetro
4. Sistema altera todas as informações do card antigo com as novas informações recebidas
4. Sistema salva o card
4. Sistema retorna o card salvo com todos os atributos

> ## Exceção - Campo obrigatório não preenchido
1. Sistema valida os campos obrigatórios
2. Sistema retorna erro

> ## Exceção - Id preenchido
1. Sistema ignora se o id foi preenchido no corpo da requisição e apenas considera o id recebido na url como parâmetro 