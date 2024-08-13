# Análise Preditiva de Demanda: Estudo de Caso Walmart Sales

## Descrição do Projeto

Este projeto explora técnicas de análise preditiva de demanda usando o dataset **Walmart Sales**. A previsão precisa de demanda é fundamental para otimizar a gestão de estoques, planejar campanhas de marketing, e melhorar a eficiência operacional em grandes cadeias de varejo. Usando dados históricos das vendas semanais de várias lojas do Walmart, este projeto desenvolve modelos de machine learning e séries temporais para prever as vendas futuras.

## Estrutura do Repositório

- `Walmart_Store_sales.csv`: Dataset utilizado para a análise preditiva de demanda, contendo dados de vendas semanais de várias lojas do Walmart.
- `notebooks/`: Contém notebooks Jupyter com a análise e modelagem preditiva.
  - `EDA.ipynb`: Notebook com a Análise Exploratória de Dados (EDA).
  - `Modeling.ipynb`: Notebook com o desenvolvimento dos modelos preditivos.
- `README.md`: Este arquivo, fornecendo uma visão geral do projeto.
- `requirements.txt`: Lista de dependências necessárias para executar o projeto.

## Dataset

O dataset utilizado neste projeto é o **Walmart Store Sales**, que pode ser encontrado no [Kaggle](https://www.kaggle.com/datasets/mikhail1681/walmart-sales). Ele contém as seguintes colunas principais:

- **Store**: Identificação da loja.
- **Dept**: Identificação do departamento.
- **Date**: Data da venda.
- **Weekly_Sales**: Vendas semanais em dólares.
- **IsHoliday**: Indicador se a semana corresponde a um feriado.
- **Temperature, Fuel_Price, CPI, Unemployment**: Variáveis econômicas e externas que podem influenciar as vendas.

## Objetivos

- Realizar uma Análise Exploratória de Dados (EDA) para entender padrões e tendências nas vendas.
- Desenvolver e avaliar modelos preditivos para prever as vendas semanais de diferentes departamentos e lojas.
- Utilizar modelos de machine learning e séries temporais para capturar a sazonalidade e outras variáveis externas que influenciam a demanda.

## Metodologia

1. **Análise Exploratória de Dados (EDA)**:
   - Visualização da distribuição das vendas.
   - Análise das vendas durante períodos de feriado.
   - Estudo das correlações entre variáveis externas e vendas.
  
2. **Preparação dos Dados**:
   - Tratamento de valores ausentes.
   - Feature Engineering para criar variáveis adicionais relevantes.

3. **Modelagem Preditiva**:
   - Implementação de modelos de regressão linear para previsões iniciais.
   - Aplicação de modelos de séries temporais, como ARIMA e Prophet.
   - Teste de modelos mais complexos, como Random Forest e XGBoost.

4. **Avaliação dos Modelos**:
   - Utilização de métricas como MSE e RMSE para avaliar a precisão das previsões.
   - Comparação entre diferentes abordagens para selecionar o modelo mais adequado.

## Como Executar

### Pré-requisitos

- Python 3.x
- Jupyter Notebook
- Bibliotecas listadas em `requirements.txt`

### Configuração

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
   cd NOME_DO_REPOSITORIO

### Instale as dependências:

```bash
pip install -r requirements.txt
```

### Resultados e Discussão

- Os resultados da análise exploratória revelaram padrões sazonais claros nas vendas, com picos durante períodos de feriado.
- O modelo ARIMA se mostrou eficaz para capturar a sazonalidade, enquanto modelos de machine learning como Random Forest capturaram melhor as interações complexas entre variáveis externas e vendas.
- As previsões geradas podem ser usadas para otimizar a gestão de estoques e planejar campanhas de marketing mais eficazes.

### Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

### Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.


