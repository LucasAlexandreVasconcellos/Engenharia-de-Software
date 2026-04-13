HU - 01
Descrição:
Como um usuário do sistema, eu quero informar meu e-mail/login e senha para acessar minha conta com segurança.

Critérios de Aceite:

-O sistema deve permitir o preenchimento dos campos de e-mail/login e senha.
-O sistema deve validar as credenciais informadas antes de conceder acesso.
Caso os dados estejam incorretos, deve ser exibida uma mensagem de erro ao usuário.
-O acesso só deve ser permitido após validação bem-sucedida.
-O processo de autenticação deve ser realizado em até 15 segundos.
-As informações de login devem ser criptografadas.
-A interface deve ser responsiva para diferentes dispositivos.

HU - 02
Recuperar Senha

Descrição:
Como um usuário que esqueceu minha senha, eu quero recuperar o acesso à minha conta para voltar a utilizar o sistema.

Critérios de Aceite:

-Deve existir um link de “Esqueci minha senha” na tela de login.
-Ao clicar no link, o usuário deve informar seu e-mail cadastrado.
-O sistema deve enviar um link ou nova senha para o e-mail informado.
-O usuário deve ser obrigado a redefinir a senha no primeiro acesso após a recuperação.
-Deve ser exibida uma mensagem confirmando o envio do e-mail.
-Caso o e-mail não esteja cadastrado, o sistema deve informar o erro.

HU - 03
Alterar Senha

Descrição:
Como um usuário autenticado, eu quero alterar minha senha para manter minha conta segura.

Critérios de Aceite:

-O sistema deve permitir que o usuário informe a senha atual e a nova senha.
-A senha atual deve ser validada antes da alteração.
-A nova senha deve atender aos requisitos de segurança (mínimo de caracteres, letras, números e caracteres especiais).
-O sistema deve confirmar a alteração com uma mensagem de sucesso.
-Caso a senha atual esteja incorreta, o sistema deve impedir a alteração e exibir erro.
-O sistema deve exigir confirmação da nova senha (digitar duas vezes).
