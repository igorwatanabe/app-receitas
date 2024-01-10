# app-receitas
Esse projeto já vem com Node, TypeScript, Express, JWT, Bcrypt, MySQL e Sequelize instalados e com a configuração do Sequelize pronta! Mesmo assim, é recomendado que você dê uma olhada no arquivo package.json.
Trybeteca API
App para gestão de bibliotecas desenvolvidas no conteúdo do dia 10.1.

Iniciando o Projeto
Clone esse repositório com o comando:

git clone git@github.com:tryber/trybeteca-api.git
Entre no diretório raiz:

cd trybeteca-api
Instale as dependências do projeto:

npm install
Inicie os containers do banco de dados e backend:

docker-compose up -d
A aplicação estará disponível em http://localhost:3001.

Também é possível ver os logs da aplicação com o comando:

docker logs -f trybeteca_api
Rodando os testes unitários
npm test
Nota: O comando pode ser rodado tanto fora quanto dentro do container Docker.

Dica
Caso tenha conflitos com portas já usadas. Use os comandos:

killall node # Parar qualquer aplicação node que esteja sendo executados na máquina!
docker stop $(docker ps -qa) # Para containers que estão sendo executados!
