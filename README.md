# TechChallenge
Apresentação Tech Challenge Fase I

# Previsão de Risco de AVC – Análise e Modelagem

Este projeto utiliza o conjunto de dados stroke.csv, que contém 5 110 registros de pacientes e 12 variáveis clínicas e demográficas. O objetivo é explorar os fatores associados à ocorrência de AVC (stroke) e construir modelos de machine learning capazes de identificar pacientes com maior risco. A análise foi conduzida no notebook Techchallenge_Modelagem_atualizado_20250811.ipynb.

# 1. Como executar o notebook
   
O notebook é composto por células em Python que podem ser executadas sequencialmente em ambientes compatíveis como Jupyter Notebook ou Google Colab. Para reproduzir a análise:

Certifique‑se de que o arquivo stroke.csv esteja no mesmo diretório do notebook. A primeira célula lê esse arquivo com pd.read_csv('stroke.csv').

Abra o arquivo Techchallenge_Modelagem_atualizado_20250811.ipynb em seu ambiente Jupyter ou Colab e execute as células na ordem em que aparecem. O notebook começa importando bibliotecas (pandas, numpy, seaborn, matplotlib e módulos do scikit‑learn e imblearn) e define o estilo gráfico do seaborn.

Não há dependências externas além das bibliotecas importadas nas primeiras células; todas as operações de limpeza, visualização e modelagem são executadas no próprio notebook.

A execução completa do notebook gera as tabelas, gráficos e métricas de avaliação descritos nesta documentação.

# 2. Dados gerais
   
Atributos: id, gender, age, hypertension, heart_disease, ever_married, work_type, Residence_type, avg_glucose_level, bmi, smoking_status e a variável alvo stroke.

Tamanho: 5 110 linhas × 12 colunas.

Tipos: variáveis numéricas (idade, glicemia média, IMC), binárias (hipertensão, doença cardíaca), categóricas (gênero, estado civil, profissão, tipo de residência, status de fumante) e a classe binária stroke (0 = ausência de AVC, 1 = presença de AVC).

Desequilíbrio de classe: a maioria dos registros não apresenta AVC (4 861 pacientes), enquanto apenas 249 casos são positivos. Esse desequilíbrio influencia negativamente os modelos preditivos.

Em resumo, o notebook implementa um fluxo completo de análise exploratória, preparação de dados, modelagem e avaliação para o problema de previsão de AVC, identificando fatores de risco relevantes e demonstrando o impacto do desequilíbrio da base na performance dos modelos.
