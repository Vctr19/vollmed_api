# Vollmed API

### Projeto do curso [Spring Boot 3: Desenvolva uma API Rest em JAVA](https://cursos.alura.com.br/course/spring-boot-3-desenvolva-api-rest-java) da plataforma Alura

### O curso visa ensinar as seguintes práticas no mundo JAVA:

- Criação de API Rest em JAVA com Spring Booot
- Desenvolvimento de CRUDs utilizando o banco de dados MYSQL
- Utilização do Flyway como ferramenta de migrations da API
- Realização de validações utilizando o Bean Validation
- Realização de paginação dos dados da API

### Como inicializar a API:

1. Com o [Docker](https://docs.docker.com/get-docker/) instalado na máquina, vá até o diretório **/api/docker** e utilize o seguinte comando para subir o banco de dados MySQL:
```shell
docker-compose up
```

2. Instale as dependências do projeto e o compile via [Maven](https://maven.apache.org/download.cgi) com o comando a seguir: 
```shell
mvn clean install
```

3. Inicie a API com o seguinte comando:
```shell
java -jar target/*.jar
```

### Uma vez que a API está online, os seguintes endpoints ficam disponíveis: