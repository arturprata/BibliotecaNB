# 📚 BibliotecaNB

## 📌 Descrição do Projeto

Este projeto consiste na implementação de um sistema de gerenciamento de biblioteca, desenvolvido em **Java**, que permite administrar clientes, funcionários e livros, além de realizar operações essenciais como **empréstimos e devoluções**.

A aplicação foi estruturada utilizando o padrão de projeto **Data Access Object (DAO)**, garantindo uma arquitetura organizada, modular e de fácil manutenção.

---

## 🚀 Funcionalidades

- CRUD de Clientes (Criar, Ler, Atualizar e Deletar)
- CRUD de Funcionários
- CRUD de Livros
- Realização de Empréstimos
- Processamento de Devoluções

---

## 🏗️ Arquitetura

O sistema foi desenvolvido com base em:

- **Programação Orientada a Objetos (POO)**
- **Padrão DAO (Data Access Object)**
- Separação de responsabilidades entre camadas

Essa abordagem permite maior organização do código e facilita manutenção e evolução do sistema.

---

## 📂 Estrutura do Projeto

O projeto está organizado em módulos seguindo as divisões propostas pelas *User Stories*.

Para execução simplificada, recomenda-se utilizar:

- `src/` → Contém os pacotes do sistema já organizados
- `BibliotecaDB` → Script SQL para criação do banco

---

## 🛠️ Tecnologias Utilizadas

- Java JDK 23
- MySQL 8.0.41
- MySQL Connector/J 9.2.0

---

## ⚙️ Configuração do Ambiente

### 1. Configurar projeto Java

- Abra sua IDE (Eclipse, IntelliJ, NetBeans, etc.)
- Crie um novo projeto Java
- Adicione a pasta `src/` ao projeto

---

### 2. Configurar banco de dados

- Baixe o arquivo **BibliotecaDB**
- Execute o script SQL para criar as tabelas
- Configure as credenciais no arquivo `ConexaoDAO`

---

### 3. Adicionar dependência

- Adicione o **MySQL Connector/J (9.2.0)** ao projeto

---

### 4. Executar

- Compile e execute o sistema
- O ponto inicial é o formulário:

```bash
frmLoginVIEW
