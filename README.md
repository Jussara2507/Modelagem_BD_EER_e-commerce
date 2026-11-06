# Modelagem_BD_EER_e-commerce
Projeto conceitual e lógico de banco de dados para E-commerce com foco em modelagem EER, contemplando clientes PF/PJ, pagamentos múltiplos e controle de entregas (Desafio DIO).
# 🛒 Projeto de E-commerce: Modelagem Conceitual e Lógica (EER)

Repositório desenvolvido como parte do desafio de projeto da **DIO (Digital Innovation One)**, com foco no refinamento e estruturação de um modelo de banco de dados relacional para uma plataforma de e-commerce.

---

## 📋 Sobre o Projeto
O objetivo deste projeto foi transformar um levantamento de requisitos narrativo em um **Diagrama EER (Entidade-Relacionamento Estendido)** robusto, cobrindo desde o cadastro de clientes até a logística de entrega e o gerenciamento de estoque.

---

## 🚀 Principais Refinamentos Implementados
O modelo conceitual e lógico foi estruturado contemplando as seguintes regras de negócio:

* **Cliente PF e PJ:** Aplicação de especialização/generalização para garantir que uma conta de cliente seja exclusiva de Pessoa Física (com CPF) ou Pessoa Jurídica (com CNPJ e Razão Social), sem sobreposição de dados[cite: 10].
* **Múltiplas Formas de Pagamento:** Estruturação para permitir que um único cliente cadastre e gerencie mais de uma forma de pagamento em seu perfil[cite: 10].
* **Controle de Entregas:** Criação de uma entidade dedicada para a logística, contendo obrigatoriamente **status de entrega** e **código de rastreio**[cite: 10].
* **Produtos, Fornecedores e Estoque:** Mapeamento de relações complexas (incluindo tabelas associativas N:N) para gerenciar produtos próprios, fornecedores, vendedores terceirizados (*marketplace*) e o estoque físico distribuído.

---

## 🛠️ Tecnologias e Ferramentas
* **Modelagem:** Ferramentas de Diagramação Conceitual / EER (ex: Draw.io / MySQL Workbench)
* **Banco de Dados Relacional:** PostgreSQL / SQL Server / DBeaver
* **Versionamento:** Git e GitHub

---
