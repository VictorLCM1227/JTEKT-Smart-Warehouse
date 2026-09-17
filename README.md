# JTEKT Smart Warehouse

Sistema desenvolvido como protótipo para otimização e monitoramento do estoque da JTEKT.

O projeto busca melhorar o controle dos materiais armazenados, aumentar a capacidade de armazenagem e reduzir a utilização de áreas produtivas como espaço de estoque, sem necessidade de alterações estruturais na planta.

---

## Sobre o projeto

O crescimento da operação da JTEKT aumentou a necessidade de espaço para armazenamento de materiais.

Atualmente, parte do estoque ocupa áreas destinadas à produção, representando aproximadamente **580 posições** que precisam ser retiradas das áreas produtivas.

Ao mesmo tempo, existe a necessidade de ampliar a capacidade do warehouse em aproximadamente **1.579 posições até 2030**.

O JTEKT Smart Warehouse foi concebido para auxiliar nesse processo por meio da identificação dos materiais, controle de suas posições e utilização de dados para melhorar a organização do estoque.

---

## Objetivos

### Objetivo principal

Desenvolver uma solução de baixo custo para monitorar os materiais e suas posições no estoque, contribuindo para a reorganização do warehouse e para a liberação das áreas produtivas atualmente utilizadas como armazenamento.

### Objetivos específicos

- Monitorar os materiais armazenados.
- Identificar a posição de cada material.
- Registrar movimentações de estoque.
- Permitir a consulta da quantidade disponível.
- Melhorar a rastreabilidade dos materiais.
- Auxiliar na organização das posições do warehouse.
- Contribuir para a criação de **1.579 novas posições**.
- Retirar **580 posições de estoque das áreas produtivas**.
- Preparar a solução para futuras funcionalidades de otimização.

---

## Problema

O crescimento da operação gera maior demanda por espaço de armazenamento.

Como consequência, parte dos materiais acaba sendo mantida em áreas produtivas, ocupando posições que poderiam ser utilizadas para a produção.

O problema envolve dois aspectos principais:

1. **Capacidade física de armazenamento**
2. **Controle e localização dos materiais**

A solução proposta trabalha principalmente sobre o segundo aspecto e fornece suporte para a reorganização do primeiro.

---

## Proposta da solução

O projeto utiliza a identificação digital dos materiais e das posições do warehouse para criar uma representação atualizada do estoque.

A proposta inicial utiliza **QR Codes** associados aos produtos e às posições.

O funcionamento conceitual é:

```text
Produto
   ↓
QR Code
   ↓
Leitura pelo dispositivo
   ↓
Sistema
   ↓
Banco de dados
   ↓
Localização e quantidade do estoque
