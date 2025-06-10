# 📊 Análise de Dados do E-commerce Zoop - 2023

Este projeto foi desenvolvido com o objetivo de analisar o comportamento de vendas e o perfil dos clientes da loja online **Zoop** ao longo do ano de **2023**. Utilizamos técnicas de exploração de dados, visualizações estratégicas e storytelling para gerar insights que apoiem a tomada de decisões de negócio.

---

## 🧭 Etapas da Análise

### 🔍 1. Exploração Inicial das Bases de Dados

Trabalhamos com duas bases principais:
- **clientes**: dados demográficos, localização e comportamento de compra dos usuários.
- **vendas**: informações sobre cada transação realizada, incluindo data, método de pagamento, categoria do produto e valores.

Após uma breve inspeção, confirmamos que os dados já estavam limpos e tratados, o que nos permitiu partir diretamente para a análise exploratória.

---

### 🔗 2. Integração das Bases

Unimos as bases pelo campo **ID_compra**, criando um único DataFrame consolidado chamado `df`. Reorganizamos as colunas para facilitar futuras análises, permitindo uma visão holística de cada transação, desde o cliente até o faturamento.

---

### 📈 3. Visualizações Estratégicas

Criamos uma série de gráficos para responder às perguntas de negócio da Zoop. Abaixo, destacamos as principais análises realizadas:

#### 💳 Métodos de Pagamento Mais Utilizados
- Visualizamos os métodos mais usados pelos clientes.
- Refinamos o gráfico aplicando a **identidade visual da Zoop**.
- Adicionamos um insight textual mostrando que **mais de 60% das vendas foram feitas via Cartão de Crédito ou PIX**, sugerindo uma oportunidade de parceria com bancos.

#### 📅 Faturamento Mensal
- Criamos um gráfico de linha com as vendas mensais.
- Adicionamos círculos e anotações destacando os picos e padrões sazonais.
- A formatação dos valores foi personalizada para representar milhões (R$ M), facilitando a leitura executiva.

#### 🧾 Faturamento por Categoria
- Utilizamos barras horizontais para representar as categorias de produto.
- Adicionamos rótulos e uma anotação contextual mostrando que **eletrônicos representaram quase metade do faturamento total** — um ponto-chave para decisões de portfólio.

#### 📊 Vendas por Trimestre x Método de Pagamento
- Criamos um gráfico de **barras empilhadas** para visualizar a distribuição dos métodos de pagamento ao longo dos trimestres.
- Esta visualização ajuda a identificar mudanças comportamentais sazonais dos clientes.

#### 🎯 Aderência ao Programa de Cashback
- Visualizamos a proporção de clientes que utilizam ou não o programa de cashback.
- Convertido o gráfico para o formato de **rosca**, facilitando a comunicação visual em dashboards.

#### ⭐ Distribuição das Avaliações de Compra
- Criamos um histograma para entender como os clientes avaliam suas experiências de compra.
- Essa métrica é essencial para monitorar a **satisfação** e identificar pontos de melhoria.

#### 👥 Perfil Demográfico dos Clientes
- Usamos um **boxplot** para cruzar idade e sexo biológico dos compradores.
- A visualização permite identificar públicos predominantes por faixa etária, auxiliando em campanhas de marketing segmentadas.

---

## 🎨 Identidade Visual da Zoop

Todos os gráficos foram adaptados para refletirem a identidade da marca Zoop, utilizando cores específicas definidas previamente:

- **CINZA_1** para o fundo
- **AZUL_1** para texto e marcações
- **VERMELHO_1**, **AQUA_1**, entre outras, para elementos visuais

Essa padronização tem como objetivo alinhar as visualizações com o branding da empresa, tornando-as adequadas para uso em relatórios, apresentações executivas e dashboards.

---

## 💡 Conclusões e Próximos Passos

Este projeto demonstrou como é possível aliar **análise de dados**, **visualização** e **storytelling** para gerar insights acionáveis. A jornada envolveu:

- Entendimento do negócio e das métricas-chave
- Exploração e integração de dados
- Criação de gráficos informativos e esteticamente refinados
- Comunicação visual eficaz para públicos técnicos e executivos

### 🔮 Próximos passos sugeridos:
- Aprofundar a análise de churn (retenção de clientes)
- Aplicar modelos de previsão para identificar tendências futuras
- Construir dashboards interativos com ferramentas como Power BI ou Streamlit

---

## 🚀 Tecnologias Utilizadas

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Identidade Visual Customizada (Zoop)

---

**Vamos além de gráficos — transformamos dados em decisões.**  
📦💡📊
