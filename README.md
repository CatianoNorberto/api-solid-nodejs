<!-- Requisições da aplicação -->

<!-- Gympass style app. -->

# Regra Funcional

- [] Deve ser possível se cadastrar;
- [] Deve ser possível se autenticar;
- [] Deve ser possível obter o perfil de um usuario logado;
- [] Deve ser possível obter o número de check-ins realizado pelo usuário logado;
- [] Deve ser possível o usuário obter seu histórico de check-ins;
- [] Deve ser possível o usuário buscar academia próxima;
- [] Deve ser possível o usuário buscar academias pelo nome;
- [] Deve ser possível o usuário realizar check-ins em uma academia;
- [] Deve ser possível validar o check-ins de um usuário;
- [] Deve ser possível cadastrar uma acadaemia;

# Regra de negócios

- [] O usuário não deve poder se cadastrar com o mesmo e-mail duplicado;
- [] O usuário não pode fazer 2 check-ins no mesmo dia;
- [] O usuário não pode fazer check-ins se não estiver perto(100m) da academia;
- [] O check-in só pode ser validado até 20 min após ser criado;
- [] O check-in só pode ser validado por adminstradores;
- [] A academia só pode ser cadastrada por adminstradores;

# Regras não funcioais

- [] A senha do usúario precisa estar criptografada;
- [] Os dados da aplicação precisam estar persistidos em um banco PostgreSQL;
- [] Todas listas de dados precisam estar paginadas com 20 itens da página;
- [] O usúario deve ser identificado por um JWT(JSON Web Token);
