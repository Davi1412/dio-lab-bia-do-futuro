# Base de Conhecimento

## Dados Utilizados

Descreva se usou os arquivos da pasta `data`, por exemplo:

| Arquivo | Formato | Utilização no Agente |
|---------|---------|---------------------|
| `historico_atendimento.csv` | CSV | Contextualizar interações anteriores e dar continuidade a  |
| `perfil_investidor.json` | JSON | Personalizar recomendações |
| `produtos_financeiros.json` | JSON | Sugerir produtos adequados ao perfil |
| `transacoes.csv` | CSV | Analisar padrão de gastos do cliente e utuilizar de forma didática |

---

## Adaptações nos Dados

> Você modificou ou expandiu os dados mockados? Descreva aqui.

Foi adicionado o produto fundo imobíliario para um leque mais amplo de produtos.

---

## Estratégia de Integração

### Como os dados são carregados?
> Descreva como seu agente acessa a base de conhecimento.

Existem duas opções para carregar os dados.
- Injetando diretamente no código Ctrl + c Ctrl + V
- Carregando os arquivos separadamente como no exemplo abaixo

```python
import pandas as pd
import json

# CSVs
historico = pd_read_csv('data/historico_atendimento.csv')
transacoes = pd.read_csv('data/transacoes.csv)

# JSON
with open(data/perfil_investidor.json', 'r' encoding='utf-8') as f:
  perfil = json.load(f)

with open('data/produtos_financeiro.json', 'r', encoding='8') as f:
  produtos = json.loas(f)
```
### Como os dados são usados no prompt?
> Dados nas váriaveis são consultados no começo da conversa para uso das informações e não a necessidade de consultar constatemente porque isso causaria lentidão no sistema.

```text

DADOS DO CLIENTE:



TRANSAÇÕES DO CLIENTE:



HISTÓRICO DO CLIENTE:


PRODUTOS DISPONIVEIS PARA ENSINO:

```
---

## Exemplo de Contexto Montado

> Mostre um exemplo de como os dados são formatados para o agente.

```
Dados do Cliente:
- Nome: João Silva
- Perfil: Moderado
- Saldo disponível: R$ 5.000

Últimas transações:
- 01/11: Supermercado - R$ 450
- 03/11: Streaming - R$ 55
...
```
