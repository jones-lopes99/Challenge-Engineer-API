# 💱 Challenge Engineer API - Coletor de Cotações com AwesomeAPI

Este projeto consiste em uma aplicação que consome dados de câmbio em tempo real a partir de uma **API pública**, normaliza essas informações e salva os dados em um arquivo `.csv` para análises futuras.

---

## 🎯 Objetivo

Desenvolver um script em **Python** capaz de:

- Acessar a [AwesomeAPI - API de Moedas](https://docs.awesomeapi.com.br/api-de-moedas)
- Normalizar os dados recebidos
- Armazenar os dados localmente em formato `.csv`

---

## 🔗 API Utilizada

- **AwesomeAPI - API de Moedas**
  - Documentação oficial: [https://docs.awesomeapi.com.br/api-de-moedas](https://docs.awesomeapi.com.br/api-de-moedas)

---

## 💸 Moedas Consultadas

- 🇺🇸 **USD/BRL** – Dólar Americano
- 🇪🇺 **EUR/BRL** – Euro
- ₿ **BTC/BRL** – Bitcoin

---

## 🛠️ Tecnologias Utilizadas

- [Python 3](https://www.python.org/)
- [Requests](https://pypi.org/project/requests/)
- Módulo nativo `csv`

---

## 📄 Estrutura dos Dados Normalizados

Cada cotação extraída da API é tratada e salva com a seguinte estrutura:

| Campo           | Descrição                                           | Exemplo       |
|----------------|-----------------------------------------------------|---------------|
| `moeda_base`   | Moeda de origem                                     | USD           |
| `moeda_destino`| Moeda de destino                                    | BRL           |
| `valor_compra` | Preço de compra (campo `bid` na API)                | 5.1389        |
| `valor_venda`  | Preço de venda (campo `ask` na API)                 | 5.1402        |
| `data_hora`    | Data/hora da cotação em UTC (`yyyy-MM-dd HH:mm:ss`) | 2025-06-11 14:35:00 |

---

## ▶️ Como Executar

### 1. Abra O Google Colab

Certifique-se de adicionar o arquivo `requirements.txt` , é onde esta as bibliotecas a serem utilizadas.

### 2.Faça o import das bibliotecas que serão utilizadas 

![image](https://github.com/user-attachments/assets/f9249f86-a276-414b-bd82-638fda3b0bb4)

### 3. Cole o restante do Script

![image](https://github.com/user-attachments/assets/bebe9be7-2354-495b-a13c-a9ccd0e6d242)

### 4.Execução

Após feito as etapas anteriores, execute cada script na ordem, para o correto funcionamento.






