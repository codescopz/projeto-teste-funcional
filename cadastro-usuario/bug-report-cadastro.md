Relatório de Bug – Cadastro de Usuário

ID do Bug: BUG-001  
Título: Campo e-mail permite cadastro com formato inválido  

Ambiente:
- Sistema: Sistema de Cadastro de Usuário
- Ambiente: Homologação
- Navegador: Google Chrome
- Dispositivo: Desktop

Descrição:
O campo de e-mail permite a realização do cadastro mesmo quando informado um endereço de e-mail em formato inválido, sem a devida validação.

Pré-condição:
- Usuário não possuir cadastro prévio no sistema
- Estar na tela de cadastro de usuário

Passos para reprodução:
1. Acessar a tela de cadastro de usuário
2. Preencher os campos obrigatórios com dados válidos
3. Informar um e-mail em formato inválido (ex: usuario@com)
4. Clicar no botão “Cadastrar”

Resultado esperado:
O sistema deve impedir a realização do cadastro e exibir uma mensagem de erro informando que o e-mail informado é inválido.

Resultado atual:
O sistema realiza o cadastro com sucesso mesmo com o e-mail em formato inválido.

Evidências:
- Cadastro concluído com e-mail inválido (sem validação)

Prioridade: Alta  
Severidade: Alta  

Status: Aberto  
Responsável: A definir

