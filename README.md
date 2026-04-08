# REST with Spring Boot & Java - Erudio Study

[![Java Version](https://img.shields.io/badge/Java-21-orange?style=for-the-badge&logo=openjdk)](https://openjdk.org/projects/jdk/21/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.4.0-brightgreen?style=for-the-badge&logo=spring-boot)](https://spring.io/projects/spring-boot)
[![Maven](https://img.shields.io/badge/Maven-Build-blue?style=for-the-badge&logo=apache-maven)](https://maven.apache.org/)

Este repositório é dedicado ao estudo do desenvolvimento de APIs RESTful utilizando as tecnologias mais recentes do ecossistema Java. O projeto é baseado nos aprendizados do treinamento da **Erudio**, focando em boas práticas, escalabilidade e padrões de projeto.

## 🚀 Tecnologias Utilizadas

- **Java 21 (LTS):** Utilizando as últimas funcionalidades da linguagem, como record types e melhorias de performance.
- **Spring Boot 3.4.0:** Framework base para a construção da aplicação.
- **Maven:** Gerenciador de dependências e build do projeto.
- **Spring Web:** Para criação de endpoints REST.
- **Spring Boot DevTools:** Agilidade no desenvolvimento com hot swap.
- **Spring Boot Starter Test:** Suporte completo para testes unitários e de integração com JUnit 5 e Mockito.

## 🛠️ O que está sendo estudado

Durante o desenvolvimento deste projeto, os seguintes conceitos são aplicados:

- Arquitetura em camadas (Controller, Service, Repository).
- Manipulação de verbos HTTP (GET, POST, PUT, DELETE).
- Tratamento de exceções customizado.
- Content Negotiation (JSON/XML).
- Serialização e Desserialização de objetos.
- Padrão VO (Value Object) / DTO (Data Transfer Object).

## 📋 Pré-requisitos

Para rodar o projeto localmente, você precisará de:

- [JDK 21](https://www.oracle.com/java/technologies/downloads/#java21) instalado.
- [Maven 3.9+](https://maven.apache.org/download.cgi) (ou utilizar o Maven Wrapper incluído).
- Uma IDE como IntelliJ IDEA, Eclipse ou VS Code.

## 🔧 Como Executar

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/esthefanydev/rest-with-spring-boot-and-java-erudio.git
   ```

2. **Navegue até o diretório:**

   ```bash
   cd rest-with-spring-boot-and-java-erudio
   ```

3. **Execute a aplicação:**
   ```bash
   mvn spring-boot:run
   ```

A API estará disponível em `http://localhost:8080`.

## 🧪 Testes

Para executar a suíte de testes do projeto:

```bash
mvn test
```

---

Desenvolvido por **Esthefany** no curso de SpringBoot - Estudo e Prática em Engenharia de Software.
