# Aula02 - DashBoard

- Atividades práticas, com importação de dados de diversas fontes.
- Tratamento dos dados na importação
- Criação de Dashboards (Paineis de controle - intereção -visualização de dados)
- Uma boa prática (Desenhar o painel de controle antes de iniciar)
    - podemos utilizar o Paint ou outra ferramenta para desenhar.

## Desenvolvimento do esboço (Layout)
![Fundo](./fundo.png)

## Importar dados de planilha do Excel
![Fonte de dados](./dados.png)

## Tratar os dados
- Validar os formatos das colunas
- Habilitar a exibição de mapas

## Criar um painel de visualização - DashBoard
![Dashboard](./dashboard.png)

## Atividades
- Faça a análise dos dados contidos no arquivo **concessionaria.csv**
- Crie um layout utilizando uma ferramenta de desenho
- Crie um Dashboard destes dados apresentando pelo menos três gráficos básicos
    - Gráfico de barras
    - Gráfico de linhas
    - Gráfico de pizza
- **Desafio:** Realizando análise com cálculos DAX, crie uma coluna comissão com 3% do preço.
- ![Objetivo do exercício](./execicio.png)

## Links
- [Kaggle](https://www.kaggle.com/) Comunidade de Aprendizagem de Máquina e Inteligência Artificial
- [Via CEP](https://viacep.com.br/) API (Aplication Process Interface), (Interface de Processamento de Aplicações) com dados de endereços, CEPs de ruas, etc.

# Conhecimentos
## Modelagem de Dados
- 3.1. Power Query
- 3.2. Power Pivot
- 3.3. Relacionamento de tabelas
- 3.4. Power View

## Power Query:
O Power Query é uma ferramenta de transformação de dados usada para conectar, importar e preparar dados para análise. Ele permite que você se conecte a várias fontes de dados, como bancos de dados, planilhas, serviços web e arquivos, e depois transforme esses dados de acordo com suas necessidades.
Você pode realizar tarefas como limpeza de dados, remoção de duplicatas, renomear colunas, aplicar filtros e criar colunas calculadas. O Power Query possui uma interface amigável que facilita a transformação de dados complexos em um formato adequado para análise.
Após preparar os dados usando o Power Query, você pode carregá-los em uma ferramenta como o Power Pivot para criar um modelo de dados.
Power Pivot:

## Power Pivot:
O Power Pivot é uma ferramenta de modelagem de dados dentro do Excel e do Power BI que permite criar modelos de dados complexos e relacionados.
Com o Power Pivot, você pode criar tabelas de fatos e tabelas de dimensões para modelar dados de maneira eficiente. Ele usa o DAX (Data Analysis Expressions), uma linguagem de fórmula, para criar medidas personalizadas e colunas calculadas que agregam e analisam os dados.
O Power Pivot também oferece recursos avançados de gerenciamento de relacionamento, permitindo que você estabeleça conexões entre tabelas com base em colunas-chave.

## Relacionamento de Tabelas:
O relacionamento de tabelas é uma parte essencial da modelagem de dados em Power BI e Power Pivot. Ele permite que você conecte diferentes tabelas em seu modelo de dados com base em campos comuns.
Os relacionamentos ajudam a criar uma estrutura hierárquica em que as tabelas de dimensão (que contêm informações descritivas, como datas, produtos ou clientes) se relacionam com a tabela de fatos (que contém métricas ou medidas de negócios).
Os relacionamentos são usados para combinar dados de várias tabelas e criar visualizações significativas nos relatórios.

## Power View:
O Power View é uma ferramenta de visualização de dados interativa que faz parte do Microsoft Excel e do Power BI. Com o Power View, você pode criar relatórios interativos e painéis de controle que permitem a exploração de dados de maneira intuitiva.
Ele oferece uma variedade de tipos de visualizações, como gráficos, tabelas dinâmicas, mapas e segmentações, que podem ser conectados dinamicamente para explorar diferentes aspectos dos dados.
O Power View é particularmente útil para criar relatórios que permitem aos usuários explorar dados e descobrir insights por conta própria.
Em resumo, essas ferramentas e conceitos estão interconectados e desempenham papéis complementares na criação de modelos de dados robustos e na apresentação de informações de maneira eficaz. O Power Query ajuda a preparar os dados, o Power Pivot permite a criação de modelos de dados, o relacionamento de tabelas une os dados e o Power View facilita a criação de visualizações interativas para comunicar os insights derivados desses dados. Tudo isso faz parte do ecossistema do Microsoft Power BI, que é amplamente utilizado para análise de dados e geração de relatórios.
