# TC01 - Cadastro de Usuário

## Descrição
Validar que um novo usuário consegue se cadastrar no aplicativo, preenchendo os campos obrigatórios e recebendo confirmação de cadastro.

## Dados de Entrada
- Nome: Teste
- Email: teste@gmail.com
- Senha: senha123
- Confirmação de Senha: senha123

## Dados de Saída Esperados
- Mensagem de sucesso: "Cadastro realizado com sucesso"
- Usuário armazenado no banco de dados com ID único

## Procedimento de Teste
1. Abrir o aplicativo.
2. Clicar na opção "Cadastrar nova conta" na tela de login.
3. Preencher os campos: Nome, Email, Senha, Confirmação de Senha.
4. Clicar no botão "Cadastrar".
5. Verificar se a mensagem de sucesso é exibida.
6. Confirmar que os dados do usuário foram salvos corretamente (ID gerado, email e nome corretos).
