# Análise da Qualidade do Vinho

## Visão Geral do Projeto
Este projeto é uma análise da qualidade de vinhos usando um conjunto de dados contendo atributos físico-químicos dos vinhos e suas notas de qualidade. O objetivo é aplicar técnicas de análise de dados e aprendizado de máquina para explorar a relação entre esses atributos e a qualidade do vinho, bem como construir modelos preditivos.

## Estrutura do Diretório
A organização do projeto segue a seguinte estrutura:

```
wine+quality/
├── data/             
│   ├── winequality-red.csv
│   ├── winequality-white.csv
│   └── winequality.names
├── notebooks/        
│   └── winequality.ipynb
├── README.md      
```

### Descrição dos Arquivos
- **`data/winequality-red.csv`**: Dados dos vinhos tintos.
- **`data/winequality-white.csv`**: Dados dos vinhos brancos.
- **`data/winequality.names`**: Descrição dos atributos do conjunto de dados.
- **`notebooks/winequality.ipynb`**: Jupyter Notebook com o processo de análise e modelagem.
- **`README.md`**: Este arquivo, que documenta o projeto.

## Conjunto de Dados
O conjunto de dados utilizado neste projeto contém os seguintes atributos:

- Acidez fixa
- Acidez volátil
- Ácido cítrico
- Açúcar residual
- Cloretos
- Dióxido de enxofre livre
- Dióxido de enxofre total
- Densidade
- pH
- Sulfatos
- Álcool
- Qualidade (nota entre 0 e 10, usada como a variável alvo)

O conjunto de dados inclui vinhos tintos e brancos, e as notas de qualidade são baseadas em dados sensoriais (por exemplo, gosto e aroma).

## Notebook
O processo de análise e modelagem está detalhado no Jupyter Notebook fornecido (`notebooks/winequality.ipynb`). O notebook inclui as seguintes etapas:

1. **Carregamento e Preprocessamento dos Dados**:
   - Carregamento do conjunto de dados.
   - Tratamento de valores ausentes e outliers.
   - Normalização ou padronização dos atributos.

2. **Análise Exploratória de Dados (EDA)**:
   - Visualização da distribuição dos atributos.
   - Análise de correlações entre os atributos e a qualidade do vinho.

3. **Desenvolvimento do Modelo**:
   - Divisão do conjunto de dados em conjuntos de treino e teste.
   - Aplicação de algoritmos de aprendizado de máquina, como modelos de regressão ou classificação.
   - Avaliação do desempenho dos modelos usando métricas como acurácia, precisão, recall e F1-score.

4. **Conclusão**:
   - Resumo dos achados da análise e discussão sobre o desempenho dos modelos preditivos.

## Como Usar

1. Clone o repositório.
2. Certifique-se de ter o Python e o Jupyter Notebook instalados.
3. Instale as dependências necessárias (listadas em `requirements.txt`, se disponível).
   ```bash
   pip install -r requirements.txt
   ```
4. Navegue até o diretório `notebooks` e abra o Jupyter Notebook:
   ```bash
   jupyter notebook winequality.ipynb
   ```
5. Execute as células passo a passo.

## Resultados
O projeto tem como objetivo:
- Identificar as principais propriedades físico-químicas que influenciam na qualidade do vinho.
- Construir um modelo preditivo confiável para classificação da qualidade do vinho.

## Licença
Este projeto está licenciado sob a Licença MIT.
