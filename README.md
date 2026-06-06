# Pipeline ETL para Acompanhamento de Pacientes com Condições Crônicas

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte do Bootcamp **TOTVS - Fundamentos de Engenharia de Dados e Machine Learning** da DIO.

O objetivo foi aplicar conceitos de Engenharia de Dados por meio da construção de um pipeline **ETL (Extract, Transform, Load)** utilizando Python e Pandas.

## ▶️ Executar no Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ISV3oOabP0e_vsgdRZVZ6H1wf7QNpJaa)

Ou acesse diretamente:

https://colab.research.google.com/drive/1ISV3oOabP0e_vsgdRZVZ6H1wf7QNpJaa

---

## 🎯 Objetivos

- Aplicar conceitos de ETL utilizando Python;
- Realizar transformação e enriquecimento de dados;
- Automatizar regras de negócio relacionadas ao acompanhamento de pacientes;
- Gerar informações úteis para análise e tomada de decisão.

---

## 🔄 Fluxo ETL

### Extract (Extração)

Foi criada uma base de dados contendo:

- ID
- Nome
- Idade
- Sexo
- Condição principal
- Comorbidades
- Data da última consulta

### Transform (Transformação)

- Conversão e tratamento de datas;
- Cálculo automático da próxima consulta (+6 meses);
- Classificação por faixa etária;
- Geração de mensagens personalizadas;
- Organização dos registros por data da próxima consulta.

### Load (Carregamento)

Exportação dos dados para arquivo CSV.

---

## 📊 Análises Realizadas

- Distribuição de pacientes por sexo;
- Distribuição por faixa etária;
- Distribuição das condições crônicas;
- Relação entre condição principal e sexo;
- Relação entre condição principal e faixa etária;
- Média de idade dos pacientes.

---

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib
- Google Colab
- GitHub

---

## 📂 Estrutura do Projeto

```text
├── ETL_Pacientes_Condicoes_Cronicas.ipynb
├── pacientes_com_mensagens.csv
├── README.md
├── images/
│   ├── grafico_sexo.png
│   └── grafico_faixa_etaria.png''''

