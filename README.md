Português
# Projeto ETL - Involves (Google Colab)
Este projeto foi desenvolvido em Python (pandas) no Google Colab, reproduzindo as etapas de um processo ETL tradicional do Pentaho Data Integration PDI.

## Objetivo
Construir um fluxo de ETL com base no dataset fornecido (`DATASET_TESTE_DE.csv`), criando dimensões e fatos conforme as especificações do teste técnico da Involves.

## Ferramentas utilizadas
- Google Colab (Cloud) – ambiente de execução  
- Python 3 + pandas – extração, transformação e carga de dados  
- GitHub – versionamento e publicação  

## Estrutura das transformações
- **Dimensões**
  - DIM_CALENDARIO
  - DIM_PONTO_VENDA
  - DIM_LINHA_PRODUTO  
- **Fatos**
  - FT_DISPONIBILIDADE
  - FT_DISPONIBILIDADE_AGREGADA
  - FT_PONTO_EXTRA
  - FT_PONTO_EXTRA_AGREGADA

## Execução
1. Abra o notebook [`main.ipynb`](./main.ipynb) no [Google Colab](https://colab.research.google.com).  
2. Faça o upload do arquivo `dataset_teste_de.csv`.  
3. Execute todas as células.  
4. Os arquivos `.csv` gerados ficam disponíveis em `/content/output/`.

## Observação
Embora desenvolvido em Python, este projeto reproduz integralmente as etapas de um job Pentaho (PDI), aplicando o entendimento dos conceitos de ETL, modelagem dimensional e integração dos dados solicitados pela Invoves.

#==============================================================================================================================================================
English
# ETL_Python_Pandas_Involves  
Repository for hosting the project developed in a cloud environment using Python (pandas) to simulate ETL processes in Pentaho Data Integration (PDI).  

# ETL Project - Involves (Google Colab)  
This project was developed in Python (pandas) using Google Colab, reproducing the steps of a traditional ETL process from Pentaho Data Integration (PDI).  

## Objective  
Build an ETL workflow based on the provided dataset (`DATASET_TESTE_DE.csv`), creating dimensions and fact tables according to the specifications of the Involves technical test.  

## Tools Used  
- **Google Colab (Cloud)** – execution environment  
- **Python 3 + pandas** – data extraction, transformation, and loading  
- **GitHub** – version control and publication  

## Transformation Structure  
- **Dimensions**  
  - DIM_CALENDARIO  
  - DIM_PONTO_VENDA  
  - DIM_LINHA_PRODUTO  

- **Facts**  
  - FT_DISPONIBILIDADE  
  - FT_DISPONIBILIDADE_AGREGADA  
  - FT_PONTO_EXTRA  
  - FT_PONTO_EXTRA_AGREGADA  

## Execution  
1. Open the notebook [`main.ipynb`](./main.ipynb) in [Google Colab](https://colab.research.google.com).  
2. Upload the file `dataset_teste_de.csv`.  
3. Run all cells.  
4. The generated `.csv` files will be available in `/content/output/`.  

## Note  
Although developed in Python, this project fully replicates the steps of a Pentaho (PDI) job, applying the understanding of ETL concepts, dimensional modeling, and data integration requested by Involves
