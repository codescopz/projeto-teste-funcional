Casos de Teste – Cadastro de Usuário
CT-01 — Cadastro com dados válidos
Cenário Positivo

Pré-condição: Usuário não cadastrado no sistema
Passos:
Acessar a tela de cadastro
Preencher todos os campos obrigatórios com dados válidos
Clicar no botão “Cadastrar”
Resultado esperado:
Usuário cadastrado com sucesso e mensagem de confirmação exibida.

Cenário Negativo

CT-02 — Cadastro com e-mail já cadastrado
Pré-condição: Usuário já cadastrado no sistema
Passos:
Acessar a tela de cadastro
Preencher os campos obrigatórios
Informar um e-mail já cadastrado
Clicar em “Cadastrar”
Resultado esperado:
Sistema deve impedir o cadastro e exibir mensagem informando que o e-mail já está em uso.

CT-03 — Cadastro com campos obrigatórios em branco
Pré-condição: Estar na tela de cadastro
Passos:
Acessar a tela de cadastro
Não preencher um ou mais campos obrigatórios
Clicar em “Cadastrar”
Resultado esperado:
Sistema deve impedir o cadastro e exibir mensagens de validação nos campos obrigatórios.

CT-04 — Cadastro com e-mail em formato inválido
Pré-condição: Usuário não cadastrado no sistema
Passos:
Acessar a tela de cadastro
Preencher os campos obrigatórios
Informar e-mail em formato inválido (ex: usuario@com)
Clicar em “Cadastrar”
Resultado esperado:
Sistema deve impedir o cadastro e exibir mensagem informando e-mail inválido.

CT-05 — Cadastro com senha fora do padrão
Pré-condição: Usuário não cadastrado
Passos:
Acessar a tela de cadastro
Preencher os campos obrigatórios
Informar senha que não atende aos critérios definidos
Clicar em “Cadastrar”
Resultado esperado:
Sistema deve impedir o cadastro e exibir mensagem informando os critérios de senha.

CT-06 — Cadastro sem confirmação de senha
Pré-condição: Usuário não cadastrado
Passos:
Acessar a tela de cadastro
Preencher senha e confirmação de senha com valores diferentes
Clicar em “Cadastrar”
Resultado esperado:
Sistema deve impedir o cadastro e exibir mensagem informando que as senhas não coincidem.
