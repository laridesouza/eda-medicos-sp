# 🏥 Análise Exploratória de Dados – Médicos em São Paulo (2024)

Este projeto apresenta uma **Análise Exploratória de Dados (EDA)** baseada em **dados públicos**, com foco na distribuição de médicos nos municípios do estado de São Paulo em 2024.  

A análise considera a segmentação entre o sistema de saúde **SUS** e o setor **Não-SUS**, buscando identificar padrões geográficos, diversidade de especialidades médicas e diferenças estruturais entre os dois sistemas.

---

## 🎯 Objetivo

O objetivo central deste projeto é analisar como os médicos estão distribuídos entre os municípios do estado de São Paulo e entre os setores **SUS** e **Não-SUS**, utilizando dados públicos para gerar insights sobre a organização do sistema de saúde.

A análise foi conduzida para responder a questões como:

- Quais são as especialidades médicas mais frequentes no SUS e no setor Não-SUS?
- Quais municípios apresentam maior diversidade de especialidades médicas em cada setor?
- Quais são os 10 municípios com o maior número total de médicos, considerando ambos os sistemas?
- Existe concentração de profissionais e especialidades em grandes centros urbanos?

---

## ⚙️ Metodologia e Etapas

O projeto foi desenvolvido como uma **Análise Exploratória de Dados (EDA)** utilizando Python, seguindo as seguintes etapas:

- Importação das bibliotecas e carregamento do dataset
- Análise inicial da estrutura e estatísticas descritivas
- Tratamento de valores nulos e verificação de consistência
- Mapeamento dos códigos numéricos de especialidades médicas
- Análises exploratórias por município, especialidade e tipo de vínculo (SUS vs Não-SUS)
- Visualização dos dados por meio de gráficos
- Consolidação dos principais achados

Todas as análises que envolvem municípios utilizam o **código IBGE do município (cod_mun)** como identificador único, garantindo padronização e consistência.

---

## 🔑 Principais Resultados e Insights

- Há uma **forte concentração de médicos e especialidades nos grandes centros urbanos**, com destaque para a cidade de São Paulo.
- O **SUS apresenta maior foco na atenção primária e na formação médica**, com predominância de especialidades como Clínico, Residente e Saúde da Família.
- O setor **Não-SUS concentra especialidades de maior demanda privada**, como Oftalmologia, Dermatologia e Cardiologia.
- Municípios que atuam como polos regionais concentram maior diversidade de especialidades.
- A distribuição de profissionais de saúde no estado é desigual e reflete fatores populacionais, econômicos e estruturais.

---

## 💻 Tecnologias Utilizadas

- **Python 3.12.7**
- **Pandas** – manipulação e tratamento de dados
- **Matplotlib** – visualização de dados
- **Seaborn** – visualização estatística
- **Jupyter Notebook**

---

## 💾 Fonte de Dados

- **Fonte:** SEADE – Sistema Estadual de Análise de Dados  
- **Ano:** 2024  
- **Base:** Médicos por tipo e município – SP  
- **Link:**  
  https://repositorio.seade.gov.br/dataset/saude-painel/resource/2566651a-39dc-47df-a2e2-6c7060dc3fd5

- **Códigos de Municípios:**  
  Os códigos de municípios utilizados na análise seguem o padrão oficial do **IBGE – Códigos de Municípios**, conforme documentação disponível em:  
  https://www.ibge.gov.br/explica/codigos-dos-municipios.php#SP

---

## ▶️ Como Executar o Projeto

Para reproduzir a análise localmente:

1.  **Clone o Repositório:**
    ```bash
    git clone https://github.com/laridesouza/eda-medicos-sp.git
    cd eda-medicos-sp
    ```
2.  **Instale as Dependências:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Abra e Execute:**
    ```bash
    jupyter notebook
    ```
