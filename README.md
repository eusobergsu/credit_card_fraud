# credit_card_fraud
trabalho prático de DS

## Contexto

O conjunto de dados referência ao histórico de fraudes em cartões de crédito de uma determinada empresa. Possibilitando, através de algoritmos de aprendizagem supervisionada, determinar se alguma atividade do cartão é referente a alguma fraude ou não.

## Objetivo

Executar a limpeza do conjunto de dados e posteriormente executar três diferentes modelos, baseados em algoritmos de aprendizagem supervisionada, para resolver o problema de classificação. Levando em consideração o desempenho, as vantagens e desvantagens de tais modelos.

## Estrutura dos dados

* **distance_from_home** : A distancia entre onde foi feita a transação e a casa do dono do cartão (em km).
* **distance_from_last_transaction** : A distancia entre onde foram feitas a ultima e a atual transação (em Km).
* **ratio_to_median_purchase_price** : A razão entre a transação mediana e a transação atual. Exemplo: mediana = 50, atual = 60 então "ratio_to_median_purchase_price = 50/60.
* **repeat_retailer** : Define se a transação está sendo feita em um lugar onde o cartão é frequentemente utilizado.
* **used_chip** : Define se a transação foi realizada utilizando um chip RFID.
* **used_pin_number** : Define se foi utilizado o numero pin na transação.
* **online_order** : Define se a transação se trata de um pagamento online.
* **fraud** : A transação é fraudulenta.


## Como executar o projeto
1. Crie o ambiente com o comando:
**python -m venv venv**
2. Ative o ambiente com o comando:
* Windows: **.\venv\Scripts\activate.bat**
* Linux: **source <venv>/bin/activate**
3. Instale as dependências: **pip install -r requirements.txt**