# Análise de Propriedades em São Paulo

Este notebook de estudos realiza uma análise detalhada de propriedades na cidade de São Paulo utilizando dados de abril de 2019. A análise inclui desde a limpeza dos dados até a otimização de modelos preditivos para estimativa de preços de imóveis.

## 1. Importação de Bibliotecas e Dados
- Importação das bibliotecas necessárias.
- Carregamento do dataset de propriedades.

## 2. Filtragem dos Dados por Tipo de Negociação
- Separação dos dados de propriedades para aluguel e venda.

## 3. Visualização Geográfica
- Criação de mapas de dispersão para propriedades de aluguel baseados em preço e tamanho.

## 4. Informações Estatísticas e Visualização de Distribuições
- Exibição de estatísticas descritivas e histogramas das variáveis principais.

## 5. Análise de Contagem e Correlação
- Contagem da frequência de tipos de propriedades e análise de correlação entre variáveis.

## 6. Limpeza dos Dados
- Remoção de colunas desnecessárias e exibição do dataframe limpo.

## 7. Codificação de Variáveis Categóricas
- Codificação da coluna de distritos utilizando OrdinalEncoder e OneHotEncoder.

## 8. Divisão dos Dados em Conjuntos de Treinamento e Teste
- Separação dos dados em variáveis dependentes e independentes e divisão em conjuntos de treinamento e teste.

## 9. Treinamento e Avaliação de Modelos
### 9.1 Regressão Linear
- Treinamento e avaliação do modelo de regressão linear.

### 9.2 Regressor de Árvore de Decisão
- Treinamento e avaliação do modelo de árvore de decisão.

### 9.3 Validação Cruzada com Árvore de Decisão
- Realização de validação cruzada no modelo de árvore de decisão.

### 9.4 Validação Cruzada com Regressão Linear
- Realização de validação cruzada no modelo de regressão linear.

## 10. Treinamento com Regressor de Floresta Aleatória
- Treinamento do modelo de regressão de floresta aleatória.

## 11. Avaliação do Modelo de Floresta Aleatória
- Avaliação do modelo de floresta aleatória utilizando validação cruzada.

## 12. Otimização de Hiperparâmetros com Grid Search
- Otimização dos hiperparâmetros do modelo de floresta aleatória utilizando GridSearchCV.

## 13. Avaliação dos Resultados do Grid Search
- Exibição dos melhores parâmetros e estimador encontrados pelo GridSearchCV.

## 14. Avaliação Final do Modelo Otimizado
- Avaliação final do modelo otimizado utilizando o conjunto de teste.

---

