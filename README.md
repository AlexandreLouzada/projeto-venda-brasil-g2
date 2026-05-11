
# Dashboard Executivo de Vendas no Brasil

## 1. Descrição do projeto

Este projeto apresenta uma análise executiva de vendas no Brasil com foco em receita, lucro, margem de lucro, ticket médio, canais de venda, categorias de produto e distribuição geográfica por UF.

O projeto foi desenvolvido como referência para a avaliação G2 da disciplina **Linguagem de Programação — Análise e Visualização de Dados com Python**.

A proposta é demonstrar um fluxo completo de projeto analítico:

1. entendimento do problema;
2. leitura e preparação dos dados;
3. criação de KPIs;
4. análise exploratória;
5. visualização de dados;
6. persistência em banco SQLite com SQLAlchemy;
7. construção de dashboard interativo com Streamlit;
8. publicação em repositório GitHub;
9. disponibilização do dashboard online.

---

## 2. Problema de negócio

Uma empresa de varejo que atua em diferentes estados, canais e categorias precisa responder às seguintes perguntas:

- Qual é a receita total do negócio?
- Qual é o lucro total?
- Qual é a margem de lucro?
- Qual canal gera mais receita?
- Qual canal apresenta melhor margem?
- Quais categorias têm melhor desempenho?
- Quais UFs concentram maior receita?
- Há variação temporal relevante nas vendas?

---

## 3. Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Streamlit
- SQLAlchemy
- SQLite
- GitHub

---

## 4. Estrutura do projeto

```text
projeto_venda_brasil_g2/
│
├── app.py
├── requirements.txt
├── README.md
├── dados/
│   └── vendas_brasil.csv
├── database/
│   └── vendas_brasil.sqlite
├── notebooks/
│   └── analise_venda_brasil.ipynb
└── imagens/
```

---

## 5. Como executar localmente

### 5.1 Clonar o repositório

```bash
git clone <URL_DO_REPOSITORIO>
cd projeto_venda_brasil_g2
```

### 5.2 Instalar dependências

```bash
pip install -r requirements.txt
```

### 5.3 Executar o dashboard

```bash
streamlit run app.py
```

---

## 6. KPIs utilizados

| KPI | Descrição |
|---|---|
| Receita Total | Soma da receita das vendas |
| Lucro Total | Soma do lucro das vendas |
| Margem de Lucro | Lucro total dividido pela receita total |
| Ticket Médio | Receita total dividida pela quantidade vendida |
| Itens Vendidos | Soma da quantidade de produtos vendidos |

---

## 7. Funcionalidades do dashboard

O dashboard possui:

- filtros por UF;
- filtros por canal;
- filtros por categoria;
- filtros por segmento;
- filtro por período;
- KPIs dinâmicos;
- gráficos de evolução temporal;
- gráficos por canal;
- gráficos por categoria;
- gráficos por UF;
- consulta SQL demonstrativa;
- tabela interativa dos dados filtrados.

---

## 8. Principais insights esperados

O projeto permite identificar:

- canais mais relevantes para receita;
- canais com melhor rentabilidade;
- categorias mais importantes;
- estados com maior concentração de vendas;
- variações temporais de receita e lucro;
- diferenças entre volume financeiro e eficiência operacional.

---

## 9. Publicação

O projeto pode ser publicado usando:

- GitHub para versionamento e portfólio;
- Streamlit Community Cloud para disponibilizar o dashboard;
- GitHub Pages para documentação do projeto.

---

## 10. Objetivo pedagógico

Este projeto demonstra aos alunos como transformar uma base de dados em um produto analítico completo.

O foco não está apenas em gerar gráficos, mas em responder perguntas de negócio e apoiar a tomada de decisão.
