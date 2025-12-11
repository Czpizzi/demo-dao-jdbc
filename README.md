# 🚀 DAO JDBC Project (Java + MySQL)

Projeto profissional demonstrando o uso do padrão **DAO (Data Access Object)** com **Java**, **JDBC** e **MySQL**, aplicando boas práticas de arquitetura, separação de responsabilidades e operações CRUD completas para as entidades **Seller** e **Department**.

---

## 🧩 Tecnologias
- Java  
- JDBC  
- MySQL  
- Eclipse  
- MySQL Connector/J  
- Git e GitHub  

---

## 📁 O que o projeto faz
- CRUD de **Seller**
- CRUD de **Department**
- Uso correto do padrão **DAO**
- Conexão com MySQL via `db.properties`
- Reaproveitamento de instâncias (instantiation pattern)
- SQL organizado e interfaces limpas

---

## 🔧 Como configurar
1. Criar banco MySQL e ajustar `db.properties`
2. Importar o projeto no Eclipse
3. Adicionar o MySQL Connector
4. Executar:
   - `Program` → testes de Seller  
   - `Program2` → testes de Department  

---

🏗 Estrutura do projeto

model.entities → Seller, Department

model.dao → interfaces DAO

model.dao.impl → implementações JDBC

db → conexão, exceções e db.properties

Program e Program2 → testes

👤 Autor

Projeto desenvolvido como parte dos estudos de Java + JDBC + DAO Pattern, com foco em boas práticas e arquitetura limpa, do curso do professor Nelio Alves.
