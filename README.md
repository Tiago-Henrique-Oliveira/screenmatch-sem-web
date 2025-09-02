🎬 Screenmatch Sem Web

Um projeto em Java que consome a OMDb API para buscar informações sobre séries e episódios diretamente no console.
Este projeto foi desenvolvido como prática de estudos, focando em consumo de API, manipulação de JSON e boas práticas com Java.

📌 Funcionalidades

Buscar informações de uma série pelo título

Listar temporadas e episódios

Exibir detalhes como ano de lançamento, número de episódios e avaliação

Filtrar episódios por nota ou ano

Exibir os 10 melhores episódios da série

Executar tudo via linha de comando (sem interface web)

🛠️ Tecnologias Utilizadas

Java 17+

Spring Boot (CommandLineRunner)

HttpClient (Java) para requisições HTTP

Jackson / Gson para conversão de JSON em objetos Java

Maven para gerenciamento de dependências

🚀 Como Executar
Pré-requisitos

Ter o Java 17+ instalado

Ter o Maven configurado

Obter uma API Key gratuita em: OMDb API

Passos
# Clonar o repositório
git clone https://github.com/Tiago-Henrique-Oliveira/screenmatch-sem-web.git

# Acessar a pasta
cd screenmatch-sem-web

# Rodar o projeto com Maven
mvn spring-boot:run


Durante a execução, o programa solicitará o nome da série e exibirá as informações no console.

📂 Estrutura do Projeto
src/
 └── main/
      ├── java/com/screenmatch
      │     ├── principal/        # Classe principal com o menu interativo
      │     ├── model/            # Classes de domínio (Série, Temporada, Episódio)
      │     ├── service/          # Consumo da API e conversões
      │     └── util/             # Utilitários e conversores
      └── resources/
            └── application.properties  # Configurações (ex: chave da API)

📖 Aprendizados

Consumo de APIs externas em Java

Manipulação de JSON e mapeamento para objetos

Uso de Streams e Collections para filtrar e ordenar dados

Estruturação de projetos Java com boas práticas

🔮 Possíveis Melhorias

Salvar séries e episódios em um banco de dados (MySQL ou PostgreSQL)

Criar uma API REST para disponibilizar os dados

Desenvolver uma interface web usando Spring MVC ou React

Implementar testes automatizados (JUnit)

👨‍💻 Autor

Desenvolvido por Tiago Oliveira
📎 https://www.linkedin.com/in/tiago-henrique-moraes-de-oliveira/
