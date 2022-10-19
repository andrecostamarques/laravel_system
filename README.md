# <b> Projeto não finalizado, migrado para repositório novo </b>

## <b>PROJETO 01 - ALUNO, MATÉRIA, PROFESSOR E SEUS FILMES!<b>

## Ferramentas utilizadas
- [Laravel](https://laravel.com/)
- [PHP](https://www.php.net/)
- [MySql](https://www.mysql.com/)

## Responsáveis pelo projeto
- [André Marques](https://github.com/andrecostamarques) - RA: 22001640
- [Angelo Pereira](https://github.com/AngeloPJunior) - RA: 21008767
- [Eduardo Perucello](https://github.com/EduardoPerucello) - RA: 22009978
- [Vinicius Alvarez](https://github.com/VinizAA) - RA: 22006181
    
A equipe tem o intuito de criar um sistema com banco de dados relacional que salvará uma relação Aluno - Matéria - Professor - Filme, constando o CRUD (Create, Read, Update e Delete) dessas informações. Deste modo, a plataforma deve exibir listas dos alunos, matérias e professores, bem como uma opção de editá-las.
Para a realização deste trabalho, utilizaremos o framework [Laravel](https://laravel.com), tendo como back-end o sistema [MySQL](https://www.mysql.com/) e front-end a ferramenta [Bootstrap](https://getbootstrap.com/).


## Passo a passo
Clone Repositório criado a partir do template, entre na pasta e execute os comandos abaixo:

Crie o Arquivo .env
```sh
cp .env.example .env
```

Atualize as variáveis de ambiente do arquivo .env
```dosini
APP_NAME=Laravel
APP_URL=http://localhost:8080

DB_PASSWORD=root
```

Suba os containers do projeto
```sh
docker compose up -d
```

Acessar o container
```sh
docker compose exec app bash
```

Instalar as dependências do projeto
```sh
composer install
```

Gerar a key do projeto Laravel
```sh
php artisan key:generate
```

Acesse o projeto
[http://localhost:8080](http://localhost:8080)

Acesse o phpmyadmin
[http://localhost:8081](http://localhost:8081)
