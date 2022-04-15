## Lojinha API Automação
Repositório gerado nas praticas do programa de testes e qualidade de software, automatizando API Rest denominada Lojinha.

## Tecnologias utilizadas

- Java
  https://www.oracle.com/java/technologies/downloads/

- RestAssured
  https://mvnrepository.com/artifact/io.rest-assured/rest-assured/5.0.1

- Junit
  https://mvnrepository.com/artifact/junit/junit/4.13.2

- Maven
  https://maven.apache.org/download.cgigi

Testes para validar os limites proibidos do valor do produto na API Lojinha, vinculados diretamente a regra de negocios que diz que o valor do produto deve estar entre R$ 0,01 e R$ 7000,00.

## Notas Gerais

- Sempre utilizamos a anotação Before Each para capturar o token que serão utilizados posteriormente nos métodos de teste.
- Armazenamos todos os dados que são enviado para a API através do uso de classes POJO.
- Criamos dados iniciais através do uso de classes Data Factory, para facilitar a criação e controle dos mesmos.
- Fazemos uso do Junit 5, o que possibilita de usar a anotação DisplayName para dar descrições em português em nossos testes