# 📦 Sistema de Controle de Estoque (Java)

Aplicação de console desenvolvida em Java para gerenciamento de inventário com controle de grade de tamanhos e movimentação de unidades. 

O projeto foi estruturado para consolidar na prática os fundamentos de **Programação Orientada a Objetos (POO)**, estruturas de dados e boas práticas de versionamento, servindo como base evolutiva para uma futura API REST com **Spring Boot** e **SQL**.

---

## 🚀 Funcionalidades (v0.1)

- **Cadastro de Itens:** Registro de produtos contendo ID único, nome, tamanho e quantidade inicial.
- **Validação de Unicidade:** Bloqueio automático de IDs duplicados no momento do cadastro.
- **Movimentação de Estoque:** Entrada e saída de unidades por ID, com validação para impedir saldo negativo.
- **Consulta e Listagem:** Exibição completa do inventário e busca direta de itens utilizando `Stream API`.
- **Limpeza de Catálogo:** Remoção automática de itens com saldo zerado utilizando expressões lambda (`removeIf`).

---

## 🛠️ Tecnologias e Ferramentas

- **Linguagem:** Java
- **Paradigma:** Programação Orientada a Objetos (POO)
- **IDE:** IntelliJ IDEA
- **Versionamento:** Git & GitHub

---

## 🗺️ Roadmap de Evolução

- [x] **v0.1** — Estrutura base da entidade, listas, streams e validação de IDs.
- [ ] **v0.2** — Padronização dos tamanhos com `Enum` e composição de objetos (registro de histórico de movimentações).
- [ ] **v0.3** — Herança e polimorfismo para diferentes categorias de produtos.
- [ ] **v0.4** — Tratamento de exceções personalizadas para regras de negócio.
- [ ] **v0.5** — Desacoplamento da camada de dados utilizando `Interfaces`.
- [ ] **v1.0** — Persistência em banco de dados relacional com JDBC e SQL.
- [ ] **v2.0** — Migração da regra de negócio para API Web RESTful com Spring Boot e JPA/Hibernate.

---

## ⚙️ Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/pedrohenryquelj/nome-do-repositorio.git