<img src="assets\logo.jpg" alt="Logo do Projeto" width="300" align="lef" justify="center">

#  Mapeamento de Nomes de Pagamentos em Faturas no Brasil 🇧🇷
![GitHub repo size](https://img.shields.io/github/repo-size/Gill3s0x01/OSINT-purchase-analisys)
![GitHub contributors](https://img.shields.io/github/contributors/Gill3s0x01/OSINT-purchase-analisys)
![GitHub issues](https://img.shields.io/github/issues/Gill3s0x01/OSINT-purchase-analisys)
![GitHub pull requests](https://img.shields.io/github/issues-pr/Gill3s0x01/OSINT-purchase-analisys)
## Introdução
Projeto colaborativo para mapear e documentar e facilitar o uso em DORKS, com os nomes que aparecem nas faturas de cartão de crédito no Brasil — tanto **compras nacionais quanto internacionais**.

# 📖 Sumário

- [Mapeamento de Nomes de Pagamentos em Faturas no Brasil 🇧🇷](#mapeamento-de-nomes-de-pagamentos-em-faturas-no-brasil-)
  - [Introdução](#introdução)
- [📖 Sumário](#-sumário)
  - [Objetivo](#objetivo)
  - [🤝 Como contribuir](#-como-contribuir)
  - [📂 Categorias](#-categorias)
  - [✅ Tabelas por Categoria](#-tabelas-por-categoria)
    - [🍔 Alimentício](#-alimentício)
    - [📺 Assinaturas/Streaming](#-assinaturasstreaming)
    - [🎓 Educação](#-educação)
    - [🎮 Lazer](#-lazer)
    - [🎰 Cassino / Apostas Online](#-cassino--apostas-online)
    - [🩺 Saúde](#-saúde)
    - [🎥 Cinema](#-cinema)
    - [💻 Serviços Digitais](#-serviços-digitais)
    - [🚗 Transporte](#-transporte)
    - [🛒 Marketplace](#-marketplace)
  - [📖 Referência Payflow Pro (para compras internacionais)](#-referência-payflow-pro-para-compras-internacionais)
  - [📖 Referência Payflow Pro (para compras internacionais)](#-referência-payflow-pro-para-compras-internacionais-1)
  - [📋 Exemplo de nomes comuns a adicionar](#-exemplo-de-nomes-comuns-a-adicionar)
  - [📢 Licença](#-licença)
  - [📫 Contato](#-contato)
- [📖 Mapeamento das seções sobre Soft Descriptor no PayPal Payflow Pro Guide](#-mapeamento-das-seções-sobre-soft-descriptor-no-paypal-payflow-pro-guide)
  - [📑 Capítulo 2 – Transaction Process Overview](#-capítulo-2--transaction-process-overview)
  - [📑 Capítulo 3 – Submitting Transactions](#-capítulo-3--submitting-transactions)
    - [📄 Página 32 — Optional Parameters](#-página-32--optional-parameters)
    - [📄 Página 36 — Optional Parameters](#-página-36--optional-parameters)
  - [📑 Apêndice: API Parameter Reference](#-apêndice-api-parameter-reference)
  - [✅ Resumo Rápido](#-resumo-rápido)

## Objetivo
O objetivo é ajudar usuários e analistas de segurança, fraude e finanças pessoais a identificar corretamente as origens das compras, categorizando os nomes comerciais e padrões de soft descriptors utilizados por adquirentes e gateways de pagamento.

## 🤝 Como contribuir

- Envie novos nomes de pagamentos com a categoria e descrição.
- Faça pull requests ou issues com os dados.
- Mantenha as categorias organizadas para facilitar a consulta.

---

## 📂 Categorias

- Saúde
- Restaurante
- Alimentício
- Telefonia
- Lazer
- Vestuário
- Marketplace
- Serviços Digitais
- Transporte
- Serviços Públicos (Água, Luz)
- Comércio Varejo
- Hospitalar
- Assinaturas/Streaming
- Educação

---

## ✅ Tabelas por Categoria

---

### 🍔 Alimentício

| 🆔 | Nome na Fatura         | Descrição                          |
|:----|:------------------------|:--------------------------------------|
| 1  | **Supermercado X Loja Y** | Compra física em supermercado local |
| 2 | **Ifd\*Nome da loja**    | Compra via iFood                   |
| 3 | **Rappi\*Nome da loja**   | Compra via Rappi                   |
| 4 | **Uber Eats**             | Compra via Uber Eats               |
| 5 | **Picpay\*Nome da loja**  | Compra via PicPay                  |
| 6 | **Dl\*Nome da loja**      | Compra via Delivery (ex: James Delivery) |

---

### 📺 Assinaturas/Streaming

| 🆔 | Nome na Fatura       | Descrição                         |
|:----|:----------------------|:-------------------------------------|
| 1  | **Mp\*Paramountplus** | Assinatura Paramount+ via MercadoPago |
| 2 | **Amazonprimebr**     | Assinatura Amazon Prime            |
| 3 | **Dm\*Spotify**        | Assinatura Spotify                 |
| 4 | **Netflix.com**        | Assinatura Netflix                 |
| 5 | **HBO Max**            | Assinatura HBO Max                 |
| 6 | **Disney+**            | Assinatura Disney+                 |
| 7 | **Apple Music**        | Assinatura Apple Music             |
| 8 | **Google Play Music**  | Assinatura Google Play Music       |
| 9 | **Tidal**              | Assinatura Tidal                   |

---

### 🎓 Educação

| 🆔 | Nome na Fatura        | Descrição                      |
|:----|:-----------------------|:----------------------------------|
| 1  | **Dm\*Udemy**          | Compra de curso na Udemy       |
| 2 | **www.eccouncil.org**  | Certificação ou curso EC-Council |
| 3 | **Dm\*Coursera**       | Compra de curso na Coursera    |
| 4 | **Dm\*Alura**          | Assinatura Alura               |
| 5 | **Dm\*Khan Academy**   | Acesso a cursos Khan Academy   |


---

### 🎮 Lazer

| 🆔 | Nome na Fatura          | Descrição                         |
|:----|:-------------------------|:-------------------------------------|
| 1  | **Ebn\*Sonyplaystatn**  | Compra na PlayStation Store        |
| 2 | **Steamgames.com**       | Compra de jogos na Steam           |
| 3 | **Dl\*Google Play Store**| Compra de aplicativos na Google Play |
| 4 | **Dl\*Apple iTunes**     | Compra de aplicativos na Apple Store |
| 5 | **Dl\*Xbox Live**        | Compra de jogos na Xbox Live       |
| 6 | **Dl\*Nintendo eShop**   | Compra de jogos na Nintendo eShop  |
| 7 | **Dl\*Epic Games Store** | Compra de jogos na Epic Games Store |

---

### 🎰 Cassino / Apostas Online

| 🆔 | Nome na Fatura         | Descrição                                           |
|:----|:-------------------------|:--------------------------------------------------|
| 20 | **EBX\*APOSTASBR**       | Plataforma intermediária EBANX para casas de apostas |
| 21 | **BRPAY\*BETXYZ**        | Casa de apostas via BRPay                          |
| 22 | **ASTROPAY**             | Carteira digital usada para cassinos e apostas      |
| 23 | **DLOCAL\*APOSTAS365**   | Intermediador DLocal para Bet365, Betano e outras   |
| 24 | **PAYREDE\*MEGABETS**    | Apostas esportivas                                  |
| 25 | **PIX\*123PAYCASSINO**   | Pagamento via Pix para site de cassino              |
| 26 | **DigiCertBet**          | Nome camuflado usado por plataformas de jogos       |
| 27 | **99BET**                | Plataforma de apostas brasileira                    |
| 28 | **PIX\*BETPIX**          | Pagamento via Pix para casa de apostas               |
| 29 | **BRPAY\*FTGAMES**       | Jogos estilo Tigrinho (Fortune Tiger)               |
| 30 | **PAYREDE\*TGRNGAME**    | Transação de jogo Tigrinho                          |
| 31 | **PIX\*FRTIGER**         | Pagamento via Pix para cassino de Fortune Tiger     |
| 32 | **PIX\*ASTROCARD**       | Carteira digital usada para apostas e cassinos      |

---

### 🩺 Saúde

| 🆔 | Nome na Fatura                   | Descrição                      |
|:----|:------------------------------------|:----------------------------------|
| 1 | **Intermedica Sist.de.saude S/A** | Plano de saúde Intermédica     |
| 2 | **Unimed**                        | Plano de saúde Unimed          |
| 3 | **Amil**                          | Plano de saúde Amil            |
| 4 | **Bradesco Saúde**                | Plano de saúde Bradesco       |
| 5 | **Hapvida**                       | Plano de saúde Hapvida        |
| 6 | **Plameds**                       | Plano de saúde Plameds        |
| 7 | **Hospital São Luiz**             | Hospital São Luiz              |
| 8 | **Hospital Sírio Libanês**        | Hospital Sírio Libanês         |

---

### 🎥 Cinema

| 🆔 | Nome na Fatura       | Descrição                                     |
|:----|:------------------------|:--------------------------------------------------|
| 33 | **CINEMARK**             | Compra de ingresso ou bomboniere no Cinemark       |
| 34 | **CINEPOLIS**            | Compra de ingresso ou bomboniere no Cinépolis      |
| 35 | **KINOPLEX**             | Compra de ingresso no Kinoplex                    |
| 36 | **UCI**                  | Compra de ingresso no UCI Cinemas                 |
| 37 | **MOVIECLUB**            | Assinatura ou ingresso de cinema                   |
| 38 | **INGRESSO.COM**         | Compra de ingressos de cinema via Ingresso.com     |
| 39 | **Ingresso.net**         | Antiga plataforma de venda de ingressos            |
| 40 | **CLAROCLUBE CINEMA**    | Promoções de ingresso via Claro Clube               |

---


### 💻 Serviços Digitais

| 🆔 | Nome na Fatura              | Descrição                         |
|:----|:-----------------------------|:-------------------------------------|
| 1  | **Dl\*Google Nome**  | Compra via Google Play Store        |
| 2  | **Pagar.me Pagamentos S.A** | Intermediador de pagamentos         |
| 3  | **PbKaspersky**              | Assinatura de antivírus Kaspersky   |
| 4  | **Picpay\***                 | Pagamentos via PicPay               |
| 5  | **Dlocal\*Spotify**          | Assinatura Spotify via Dlocal       |
| 6  | **Ebanx\*AliExpress**       | Compras no AliExpress via Ebanx     |
| 7  | **Ebx\*Shopee**              | Compras no Shopee via Ebanx         |
| 8  | **Picpay\*Nome do serviço**  | Pagamento de serviços via PicPay    |

---

### 🚗 Transporte

| 🆔 | Nome na Fatura | Descrição                |
|:----|:----------------|:----------------------------|
| 1  | **Uber**        | Corrida ou serviço Uber  |
| 2  | **99**          | Corrida ou serviço 99    |
| 3  | **Cabify**      | Corrida ou serviço Cabify |
| 4  | **BlaBlaCar**   | Viagem compartilhada     |
| 5  | **Movida**      | Aluguel de carro Movida  |
| 6  | **Localiza**    | Aluguel de carro Localiza|
| 7  | **Rentcars**    | Aluguel de carro Rentcars|
| 8  | **99app**       | Corrida ou serviço 99    |

---

### 🛒 Marketplace

| 🆔 | Nome na Fatura           | Descrição                          |
|:----|:--------------------------|:--------------------------------------|
| 1  | **Mp\*Melimais**         | Marketplace Melimais via MercadoPago |
| 2 | **Pg\*nome da loja**     | Venda via PagSeguro                 |
| 3 | **Mp\*Aliexpress**       | Compra via MercadoPago no AliExpress |
| 4 | **Dl\*Alipay Alipay Bras**| Compra via Alipay (AliExpress)      |
| 5 | **Ebanx\*Shopee**        | Compras no Shopee via Ebanx         |
| 6 | **Ebanx\*AliExpress**    | Compras no AliExpress via Ebanx     |

___

## 📖 Referência Payflow Pro (para compras internacionais)

| 📄 Página | 📌 Seção                       | 🔍 Importância                                      |
|:------------|:--------------------------------|:----------------------------------------------------|
| 15         | Transaction Process Overview     | Explica como parâmetros seguem até o adquirente     |
| 32         | Optional Parameters              | Mostra `COMMENT1`, `COMMENT2`, `CUSTREF`            |
| 36         | Optional Parameters              | Mostra `HOSTEDDESCRIPTOR` (nome na fatura)          |
| 150+       | API Parameter Reference          | Descrição completa dos parâmetros e seus usos       |

---

---

## 📖 Referência Payflow Pro (para compras internacionais)

| 📄 Página | 📌 Seção                       | 🔍 Importância                                      |
|:------------|:--------------------------------|:----------------------------------------------------|
| 15         | Transaction Process Overview     | Explica como parâmetros seguem até o adquirente     |
| 32         | Optional Parameters              | Mostra `COMMENT1`, `COMMENT2`, `CUSTREF`            |
| 36         | Optional Parameters              | Mostra `HOSTEDDESCRIPTOR` (nome na fatura)          |
| 150+       | API Parameter Reference          | Descrição completa dos parâmetros e seus usos       |

---

## 📋 Exemplo de nomes comuns a adicionar

- **Steamgames.com** → Lazer  
- **Apple.com/Bill** → Assinaturas/Serviços Digitais  
- **Dlocal\*Spotify** → Assinaturas/Streaming  
- **Ebanx\*AliExpress** → Marketplace  
- **EBX\*Shopee** → Marketplace  
- **Picpay\*** → Serviços Digitais  

---

## 📢 Licença

Projeto colaborativo open source — uso livre com atribuição.

---

## 📫 Contato

Sugestões, dúvidas ou contribuições: abra uma issue ou pull request.



# 📖 Mapeamento das seções sobre Soft Descriptor no PayPal Payflow Pro Guide

## 📑 Capítulo 2 – Transaction Process Overview

**📄 Página 15**

> *“When a transaction is processed, your application passes transaction parameters to the Payflow Gateway. The gateway processes the transaction and forwards it to the appropriate payment processor or bank.”*

**🔍 Comentário:**  
Aqui explica o fluxo de como a aplicação envia os parâmetros para o Payflow, e como isso chega ao adquirente/banco — etapa onde o **Soft Descriptor** (nome na fatura) é repassado.

---

## 📑 Capítulo 3 – Submitting Transactions

### 📄 Página 32 — Optional Parameters

**Parâmetros relevantes:**
- `COMMENT1`
- `COMMENT2`
- `CUSTREF`

**Descrição:**
> **COMMENT1 and COMMENT2**: Optional fields to pass information for display on reports or transaction logs.  
> **CUSTREF**: Optional. Customer reference or order number. It appears in reports.

**🔍 Comentário:**  
Esses parâmetros podem ser usados para registrar informações adicionais, e dependendo da configuração do adquirente ou do gateway, podem ser incluídos ou concatenados no campo do Soft Descriptor que aparece na fatura.

---

### 📄 Página 36 — Optional Parameters

**Parâmetro:**
- `HOSTEDDESCRIPTOR`

**Descrição:**
> **HOSTEDDESCRIPTOR**: Soft descriptor sent to the acquiring bank for display on the customer’s credit card statement.

**🔍 Comentário:**  
**Esse é o parâmetro principal para definir o nome que aparece na fatura do cliente.** Nem todos os adquirentes permitem alterar isso via API, mas quando permitido, é enviado aqui.

---

## 📑 Apêndice: API Parameter Reference

**📄 Página 150 em diante**

**Parâmetros importantes:**
- `COMMENT1`
- `COMMENT2`
- `CUSTREF`
- `HOSTEDDESCRIPTOR`

**🔍 Comentário:**  
Aqui estão as definições formais dos campos e seus usos. O `HOSTEDDESCRIPTOR` é explicitamente para o nome da fatura, e os `COMMENT1`, `COMMENT2` e `CUSTREF` são para registros internos, mas podem acabar compondo o nome na fatura se mal configurados ou por padrão de adquirentes.

---

## ✅ Resumo Rápido

| 📄 Página | 📌 Seção                       | 🔍 Importância                                      |
|:------------|:--------------------------------|:----------------------------------------------------|
| 15         | Transaction Process Overview     | Explica como parâmetros seguem até o adquirente     |
| 32         | Optional Parameters              | Mostra `COMMENT1`, `COMMENT2`, `CUSTREF`            |
| 36         | Optional Parameters              | Mostra `HOSTEDDESCRIPTOR` (nome na fatura)          |
| 150+       | API Parameter Reference          | Descrição completa dos parâmetros e seus usos       |
