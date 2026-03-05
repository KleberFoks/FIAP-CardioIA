<img src="https://raw.githubusercontent.com/lfusca/templateFiap/main/assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=30% height=30%>

# AI Project Document - Módulo 1 - FIAP

## CardioIA - A Nova Era da Cardiologia Inteligente

#### Kleber Hendrik Sargaceira Foks de Oliveira - RM562225
#### Turma: 2TIAOA
#### Curso: Tecnologia em Inteligência Artificial (On-Line)

---

## 1. Introdução

O CardioIA surge como uma solução para o desafio global das doenças cardiovasculares, integrando as disciplinas de IA avançada em um ecossistema de saúde preditivo.

### 1.1. Escopo do Projeto

O projeto visa desenvolver uma plataforma que utilize dados de IoT para monitoramento em tempo real, NLP para análise de prontuários e Visão Computacional para diagnóstico por imagem.

---

## 2. Visão Geral do Projeto (Fase 1: Dados)

### 2.1. Objetivos do Projeto
O objetivo desta fase é consolidar as bases de dados para treinamento de modelos futuros.

### 2.2. Tecnologias Utilizadas
- Python (Manipulação de dados)
- GitHub (Controle de versão)
- Cloud Storage (Armazenamento de datasets)

---

## 3. Detalhamento da Coleta de Dados

> **IMPORTANTE:** Para atender ao critério de "Dados Preparados e Organizados", todos os datasets foram consolidados e hospedados no link abaixo:
> **[Link do Google Drive - CardioIA_Dados_Completos](https://drive.google.com/drive/folders/1YTkKYtUxb6NjjepvW2x25JMAHj_KshUR?usp=sharing)**

### 3.1. Dados Numéricos (IoT)
- **Dataset:** [UCI Heart Disease Dataset (Official)](https://archive.ics.uci.edu/dataset/45/heart+disease)
- **Justificativa:** Essencial para treinar algoritmos de triagem precoce baseados em variáveis fisiológicas capturadas por sensores.

### 3.2. Dados Textuais (NLP)
- **Arquivos:** `artigo_01_iam.txt` e `artigo_02_iot.txt` (localizados em `/document`).
- **Justificativa:** Permitir que o sistema compreenda diagnósticos subjetivos e notas médicas para enriquecer o prontuário eletrônico.

### 3.3. Dados Visuais (Visão Computacional)
- **Datasets:** [PTB-XL ECG (PhysioNet Official)](https://physionet.org/content/ptb-xl/1.0.3/) e [NIH Chest X-ray (Kaggle)](https://www.kaggle.com/datasets/nih-chest-xrays/sample).
- **Justificativa:** Treinamento de redes neurais convolucionais (CNNs) para detecção de anomalias em exames de imagem.

---

## 4. Referências
1. SciELO - Arquivos Brasileiros de Cardiologia.
2. PubMed Central.
3. Kaggle Datasets.
