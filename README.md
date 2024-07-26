# Previsão em relação aos consumidores usando Machine Learning

**Descrição**
Este projeto visa criar um modelo de machine learning para prever se um consumidor é considerado "bom" ou "mau" com base em dados financeiros como a renda anual.

**Dados**
Os dados utilizados neste projeto incluem informações sobre clientes, como:

ID: Número do cliente

CODE_GENDER: Gênero

FLAG_OWN_CAR: Possui carro

FLAG_OWN_REALTY: Possui imóvel

CNT_CHILDREN: Número de filhos

AMT_INCOME_TOTAL: Renda anual

NAME_INCOME_TYPE: Categoria de renda

NAME_EDUCATION_TYPE: Nível de educação

NAME_FAMILY_STATUS: Estado civil

NAME_HOUSING_TYPE: Tipo de moradia

DAYS_BIRTH: Idade (em dias, contando para trás a partir do dia atual)

DAYS_EMPLOYED: Data de início do emprego (em dias, contando para trás a partir do dia atual)

FLAG_MOBIL: Possui telefone móvel

FLAG_WORK_PHONE: Possui telefone de trabalho

FLAG_PHONE: Possui telefone

FLAG_EMAIL: Possui e-mail

OCCUPATION_TYPE: Ocupação

CNT_FAM_MEMBERS: Tamanho da família

**Preparação dos Dados:**
- Criação da Variável Alvo: A variável alvo foi criada com base na renda anual (AMT_INCOME_TOTAL). Clientes com renda anual abaixo de 50.000 foram classificados como "maus" consumidores, enquanto aqueles com renda anual acima desse valor foram classificados como "bons" consumidores.
- Tratamento de Valores Faltantes: Utilizei imputação para preencher valores faltantes nas colunas numéricas e categóricas.
- Codificação de Variáveis Categóricas: Apliquei codificação one-hot para transformar variáveis categóricas em numéricas.
