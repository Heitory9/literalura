
<p align="center">
  <img src="ONE_logo_rgb.png" width="300" height="150">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Framework-Spring-blue">
  <img src="https://img.shields.io/badge/Language-Java%2017-orange">
  <img src="https://img.shields.io/badge/Database-PostgreSQL-green">
</p>

<p align="center">
  <a href="#english-version">Read in English</a>
</p>

<a id="readme-top"></a>

# 📚 Literalura

**Literalura** é uma aplicação desenvolvida em **Java 17 com Spring Boot** que permite buscar, salvar e consultar livros gratuitos da API pública do [Gutendex](https://gutendex.com/). Os dados são armazenados em um banco relacional PostgreSQL, permitindo consultas e filtros avançados por terminal.

---

## 🚀 Funcionalidades

* 🔍 Buscar livros por título diretamente da API Gutendex
* 💾 Armazenar livros e autores no banco de dados
* 📚 Listar todos os livros e autores salvos
* 🕰️ Filtrar autores vivos em um determinado ano
* 🌐 Filtrar livros por idioma

---

## 🛠️ Tecnologias Utilizadas

* `Java 17`
* `Spring Boot`
* `Spring Data JPA`
* `Hibernate`
* `PostgreSQL`
* `Maven`
* `Jackson` (serialização JSON)
* `Gutendex API` ([gutendex.com](https://gutendex.com))

---

## ✅ Pré-requisitos

Antes de iniciar, você precisará ter instalado:

* Java 17 ou superior
* Maven
* PostgreSQL (em execução)

---

## ⚙️ Configuração do Banco de Dados

Antes de rodar a aplicação, configure suas credenciais no arquivo:

```
src/main/resources/application.properties
```

Exemplo de configuração:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/literalura
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true
```

> 💡 **Dica**: certifique-se de que o banco `literalura` já esteja criado no PostgreSQL.

---

## 📦 Como executar o projeto

1. **Clone o repositório**:

```bash

```

2. **Acesse o diretório do projeto**:

```bash
cd literalura
```

3. **Execute a aplicação**:

```bash
mvn spring-boot:run
```

4. O menu interativo será exibido no terminal. Basta seguir as opções para explorar os recursos.
