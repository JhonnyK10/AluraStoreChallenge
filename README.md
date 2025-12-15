# AluraStoreChallenge

# Análise de Desempenho - Alura Store

## 📊 Sobre o Projeto

Este projeto realiza uma análise estratégica do desempenho das 4 lojas da rede Alura Store para identificar qual unidade apresenta os menores indicadores de eficiência e deve ser considerada para venda. A análise combina múltiplas métricas financeiras e operacionais para fornecer uma recomendação baseada em dados concretos.

## 🎯 Propósito da Análise

O objetivo principal é auxiliar o Senhor João, proprietário da rede Alura Store, a tomar uma decisão estratégica sobre qual loja vender para otimizar seus recursos e focar nas unidades mais rentáveis. A análise considera:

* **Faturamento total** de cada loja
* **Distribuição de vendas** por categoria de produtos
* **Satisfação dos clientes** através de avaliações médias
* **Desempenho por produto** (mais e menos vendidos)
* **Eficiência operacional** medida pelo frete médio

## 📁 Estrutura do Projeto

**text**

```
AluraStoreBrasilChallenge/
│
├── AluraStoreBrasilChallenge.ipynb    # Notebook principal com análise completa
├── README.md                           # Documentação do projeto
└── .gitattributes                     # Configurações do Git
```

### Detalhamento dos Arquivos:

1. **AluraStoreBrasilChallenge.ipynb** - Contém todo o código de análise, dividido em seções:
   * Carregamento dos dados das 4 lojas
   * Análise de faturamento total
   * Vendas por categoria
   * Média de avaliação por loja
   * Produtos mais e menos vendidos
   * Frete médio por loja
   * Visualizações gráficas
   * Recomendação final baseada em dados
2. **README.md** - Este arquivo, com instruções e documentação

## 📈 Gráficos e Insights Obtidos

### Visualizações Geradas:

1. **Faturamento Total por Loja** (Gráfico de Colunas)
   * Comparação visual direta do desempenho financeiro
   * Destaque para a loja com menor e maior faturamento
2. **Distribuição de Vendas por Categoria** (Gráfico de Pizza)
   * Análise do mix de produtos da loja com menor desempenho
   * Identificação das categorias predominantes
3. **Média de Avaliação por Loja** (Gráfico de Linhas)
   * Tendência de satisfação do cliente entre as lojas
   * Destaque para variações significativas
4. **Frete Médio por Loja** (Gráfico de Área)
   * Evolução dos custos operacionais
   * Análise da relação custo-eficiência

### Principais Insights:

1. **Identificação da Loja 4 como a menos eficiente** :

* Menor faturamento total (R$ 1.384.497,58)
* Terceira pior avaliação média (3,996/5)
* Desempenho fraco em categorias importantes como eletrodomésticos

1. **Padrões de vendas consistentes** :

* Móveis e eletrônicos são as categorias líderes em todas as lojas
* Brinquedos apresentam boa performance em todas as unidades

1. **Variações operacionais significativas** :

* Frete médio varia de R$ 31,28 a R$ 34,69 entre lojas
* Loja com menor frete não converte em maior faturamento

## 🚀 Instruções para Executar o Notebook no Google Colab

### Google Colab (Recomendada)

1. **Acesse o Google Colab** :
   **text**

```
   https://colab.research.google.com/
```

1. **Carregue o notebook** :

* Clique em "Upload" na aba "Arquivo"
* Selecione o arquivo `AluraStoreBrasilChallenge.ipynb`
* Ou copie e cole o conteúdo em um novo notebook

1. **Execute as células em ordem** :

* Clique em cada célula de código
* Pressione `Shift + Enter` para executar
* As bibliotecas necessárias serão instaladas automaticamente

## 🔧 Dependências

O projeto utiliza as seguintes bibliotecas Python:

* **pandas**: Para manipulação e análise de dados
* **matplotlib**: Para criação de visualizações gráficas
* **numpy**: Para operações matemáticas

Todas as dependências são instaladas automaticamente no Google Colab. Para ambiente local, use:

**bash**

```
pip install -r requirements.txt
```

## 📊 Resultados da Análise

### Recomendação Final:

**Venda da Loja 4**

### Justificativa Resumida:

1. **Menor faturamento total** da rede
2. **Desempenho fraco** em categorias estratégicas
3. **Avaliação média baixa** em comparação com outras lojas
4. **Mix de produtos desalinhado** com o perfil local
