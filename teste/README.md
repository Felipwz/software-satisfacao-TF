Sistema para pesquisar Satisfação de alunos

Componentes
PostgreSQL: Banco de dados relacional para dados estruturados.
MongoDB: Banco NoSQL para dados flexíveis.
Node.js (v22): Ambiente de execução da aplicação web.
Como rodar
Clone o repositório:
git clone https://github.com/Felipwz/software-satisfa-o-TF
cd software-satisfacao-TF

Execute os containers com Docker Compose:


## Acesse os serviços: 

- **Aplicação Node.js:**  
  Acesse a aplicação web de pesquisa de satisfação em [http://localhost:3000](http://localhost:3000).

- **PostgreSQL:**  
  Você pode acessar o banco de dados PostgreSQL com as seguintes credenciais:
  - Host: `localhost`
  - Porta: `5432`
  - Usuário: `devuser`
  - Senha: `devpassword`
  - Banco: `pesquisa`

- **MongoDB:**  
  Você pode acessar o banco de dados MongoDB com as seguintes credenciais:
  - Host: `localhost`
  - Porta: `27017`
  - Usuário: `devuser`
  - Senha: `devpassword`