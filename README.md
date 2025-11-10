
# Sistema Bancário

Sistema bancário básico desenvolvido em **Java** para console, aplicando conceitos de **Programação Orientada a Objetos (POO)**, **Lombok**, **enums**, **records** e manipulação de coleções.

---

## **Funcionalidades**
- Criação de contas: **Corrente** ou **Poupança**;
- Depósitos e saques com atualização de saldo;
- Transferências via PIX entre contas;
- Histórico de transações (usando `record Transacao`);
- Menu interativo via console;
- Persistência em memória simulada com `Map<String, Conta>`.

---

## **Conceitos de POO aplicados**
- **Herança**: `Conta` (abstrata) com sub-classes `ContaCorrente` e `ContaPoupanca`;
- **Polimorfismo**: método `transferir()` implementado de forma diferente por cada tipo de conta;
- **Encapsulamento**: atributos privados e métodos públicos;
- **Abstração**: classe abstrata `Conta` e métodos genéricos de transação;
- **Reuso de código**: métodos comuns para depósito, saque, validação de saldo;
- **Enums e Records**: `TipoConta`, `TipoTransacao`, `Transacao` (record).

---

## **Tecnologias utilizadas**
- Java 17 (ou superior)
- Lombok (`@Getter`, `@Setter`, `@ToString`)
- Collections (Map, List)
- Console interativo

---

## **Como executar**
1. Clonar o repositório:
   ```bash
   git clone <link-do-repositorio>
