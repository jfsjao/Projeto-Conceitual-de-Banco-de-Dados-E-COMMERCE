
# Modelo Conceitual - Banco de Dados para E-commerce

## 💡 Descrição
Este projeto representa um modelo conceitual de banco de dados para um sistema de e-commerce. Ele foi desenvolvido como parte do desafio do Bootcamp "Inteligência Artificial Aplicada a Dados com Copilot" da DIO.

## 🎯 Requisitos Atendidos

- Cadastro de cliente como **Pessoa Física (PF)** ou **Pessoa Jurídica (PJ)**, mas não ambos.
- Cada cliente pode ter **várias formas de pagamento**.
- Cada pedido possui uma **entrega com status** e **código de rastreamento**.

## 🔎 Entidades e Relacionamentos

- **Cliente**
- **Pessoa Física** (1:1 com Cliente)
- **Pessoa Jurídica** (1:1 com Cliente)
- **Pagamento** (1:N com Cliente)
- **Pedido** (1:N com Cliente)
- **Entrega** (1:1 com Pedido)

## 🖼️ Diagrama

![Modelo Conceitual](imagens/modelo_conceitual.png)
