# Atividade 03 - Avaliação final

- Responda todas as questões abaixo.
- **A resposta de cada questão deve estar abaixo da questão**, que nem numa prova normal.
- Preste atenção, **nem todas usam o mesmo banco de dados**.
- No final deste documento, deixei alguns links que podem ajudar vocês.
## 1) Faça a avaliação geral dos data set e realize uma breve análise dos dados.
### Dados disponíveis neste [link](https://www.kaggle.com/code/alexisbcook/handling-missing-values/data). Faça download do arquivo `NFL Play by Play 2009-2016 (v3).csv` e coloque na mesma pasta do seu código.

O dataset reune métricas de todos os jogos da NFL entre 2009 e 2018. Vamos ver qual a cara desses dados.
#### a) Importe as bibliotecas necessárias e os dados que serão usados
Resposta:
#### b) Faça um print com as informações gerais do data set: a cara geral dele (head), os nome das colunas, dimensões do dataframe (shape) e o tipo de cada variável.
Resposta:
#### c) Há erros nos tipos de dados? Responda "sim", ou "não". Se houverem, os corrija.
Resposta
#### d) Quantos dados faltantes ou nulos há no dataset? 
Resposta
#### e) Corrija os dados nulos.

**Dica**

- Calcule o percentual dos nulos para cada coluna (você pode fazer isso com um loop for):
```python
for coluna in colunas:
    total_nulls = coluna.isnull().sum()
    total_cells = len(coluna)
    percentual_nulls = (total_nulls/total_cells) * 100
    print(percentual_nulls)
```

- Para deletar os nulos, use `dropna()`
- Para substituir os nulos, use `fillna()`
- Repare que, se você decidir deletar, todos os dados vão sumir . . . 
- Talvez seja melhor substituir eles por Zero.

Resposta:
## 2) Calcule os parâmetros estatísticos descritibos do seguinte banco de dados. Não se esqueça de colocar as respostas uma após a outra.

### Dados disponíveis neste [link](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand). Faça download do arquivo `hotel_bookings.csv` e coloque na mesma pasta do seu código.

### Baixe os dados e avalie eles a vontade.
. . . 
### a) Me mosrte uma tabela com as principais variáveis descritivas para todas as colunas: contagem, média, variância, valor mínimo, valor máximo, mediana, e os quartils 25% e 75%.

Dica: é possível fazer isso tudo com apenas uma linha de comando.
Resposta
### b) Faça um histograma dos campos `is_canceld`, `lead_time` e `arrivel_date_month`
Resposta
