Cenários de Teste – Cadastro de Usuário
Cenário positivo

Cenário 01 – Cadastro realizado com sucesso
Dado que o usuário não possui cadastro no sistema
Quando o usuário informa dados válidos no formulário de cadastro
Então o sistema deve realizar o cadastro com sucesso

Cenário de Teste Negativo

Cenário 02 – Tentativa de cadastro com e-mail já existente
Dado que o usuário já possui cadastro no sistema
Quando o usuário informa um e-mail já cadastrado
Então o sistema deve impedir o cadastro
E exibir uma mensagem de erro informando que o e-mail já está em uso

Cenário 03 – Tentativa de cadastro com campos obrigatórios em branco
Dado que o usuário está na tela de cadastro
Quando o usuário não preenche um ou mais campos obrigatórios
Então o sistema deve impedir o cadastro
E exibir mensagem de validação dos campos obrigatórios

Cenário 04 – Tentativa de cadastro com e-mail inválido
Dado que o usuário está na tela de cadastro
Quando o usuário informa um e-mail em formato inválido
Então o sistema deve impedir o cadastro
E exibir mensagem de erro informando e-mail inválido

Cenário 05 – Tentativa de cadastro com senha fora do padrão
Dado que o usuário está na tela de cadastro
Quando o usuário informa uma senha que não atende aos critérios definidos
Então o sistema deve impedir o cadastro
E exibir mensagem informando os critérios de senha

