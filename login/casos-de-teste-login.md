# 🔐 Casos de Teste – Login

| ID | Cenário | Pré-condição | Passos | Resultado Esperado | Prioridade |
|----|--------|-------------|--------|-------------------|------------|
| CT-LOGIN-01 | Login com dados válidos | Usuário cadastrado | 1. Acessar a tela de login<br>2. Informar e-mail válido<br>3. Informar senha válida<br>4. Clicar em Entrar | Usuário autenticado e redirecionado para a área logada | Alta |
| CT-LOGIN-02 | Login com senha inválida | Usuário cadastrado | 1. Acessar a tela de login<br>2. Informar e-mail válido<br>3. Informar senha inválida<br>4. Clicar em Entrar | Sistema deve exibir mensagem de credenciais inválidas | Alta |
| CT-LOGIN-03 | Login com campos vazios | Nenhuma | 1. Acessar a tela de login<br>2. Clicar em Entrar sem preencher os campos | Sistema deve exibir mensagem de campos obrigatórios | Média |
