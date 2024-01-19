
# Sistema de Login Simples em PHP e MySQL
Este é um sistema de login simples desenvolvido em PHP e MySQL. Ele oferece funcionalidades básicas de registro e login, permitindo que os usuários acessem áreas protegidas por autenticação. Veja como funciona:

Funcionalidades Principais:
# Registro de Usuário:

Os usuários podem se registrar fornecendo um nome, um endereço de e-mail e uma senha.
A senha é armazenada de forma segura no banco de dados usando o algoritmo bcrypt.
Login:

Os usuários podem fazer login usando seu endereço de e-mail e senha previamente registrados.
As credenciais são verificadas em relação aos registros no banco de dados.

# Autenticação de Sessão:

Após o login bem-sucedido, uma sessão é iniciada, armazenando o ID do usuário e seu nome.
As páginas protegidas verificam a existência da sessão para garantir que apenas usuários autenticados acessem essas áreas.

#  Redirecionamento:

Usuários não autenticados são redirecionados para a página de login ao tentar acessar áreas protegidas.
Estrutura do Código:
**registrar-se.php**: Página de registro de usuários.
**entrar.php**: Página de login para autenticação.
**painel.php**: Página protegida acessível apenas por usuários autenticados.

Próximos Passos:
Este é um exemplo básico e pode ser expandido com recursos adicionais, como recuperação de senha, controle de permissões e melhorias de segurança.
Certifique-se de configurar corretamente as informações de conexão com o banco de dados antes de utilizar.
Considere implementar práticas avançadas de segurança, como validação de entrada e proteção contra ataques.
Este sistema serve como uma base simples para implementações mais complexas de autenticação e pode ser adaptado conforme as necessidades específicas do projeto.
