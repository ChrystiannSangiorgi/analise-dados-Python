# 📊 Dashboard de Análise de Salários na Área de Dados

Dashboard interativo desenvolvido em Python para explorar e visualizar dados salariais de profissionais da área de tecnologia e dados ao redor do mundo, cobrindo os anos de 2020 a 2025.

🔗 **[Ver aplicação ao vivo](https://dados-python-cagos-tecnoligia.streamlit.app/)**

---

## Sobre o projeto

Este projeto foi desenvolvido como exercício prático de análise de dados com Python, utilizando um dataset real com **133.339 registros** de cargos na área de dados. O objetivo foi transformar dados brutos em visualizações interativas que permitam explorar tendências salariais por cargo, senioridade, tipo de contrato, modelo de trabalho e país.

## Funcionalidades

- **Filtros dinâmicos** por ano, senioridade, tipo de contrato e tamanho da empresa
- **Métricas gerais** em tempo real: salário médio, salário máximo, total de registros e cargo mais frequente
- **Top 10 cargos** por salário médio (gráfico de barras horizontal)
- **Distribuição de salários anuais** (histograma)
- **Proporção dos tipos de trabalho** presencial, remoto e híbrido (gráfico de rosca)
- **Mapa mundial** com salário médio de Cientista de Dados por país
- **Tabela de dados detalhados** com todos os registros filtrados

## Stack

| Tecnologia | Uso |
|---|---|
| Python 3 | Linguagem principal |
| Pandas | Manipulação e análise dos dados |
| Streamlit | Interface web interativa |
| Plotly | Visualizações e gráficos dinâmicos |

## Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/ChrystiannSangiorgi/analise-dados-Python.git
cd analise-dados-Python

# Instale as dependências
pip install -r requirements.txt

# Execute o app
streamlit run app.py
```

## Dataset

O arquivo `dados-final.csv` contém registros de salários globais na área de dados com as seguintes colunas: ano, senioridade, tipo de contrato, cargo, salário, moeda, residência, modelo de trabalho (remoto/presencial/híbrido), empresa e país.

## Autor

**Chrystiann Caesar Sangiorgi de Oliveira**  
Estudante de Ciência da Computação · UNICID · 2º Semestre  
[LinkedIn](https://www.linkedin.com/in/chrystiann-sangiorgi/) · [GitHub](https://github.com/ChrystiannSangiorgi)
