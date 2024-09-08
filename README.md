# CIDA - Consulting Insights With Deep Analysis

## Etapa do projeto

Inicialmente no projeto visionamos um produto que tivesse a capacidade de
processar arquivos e com o uso de duas IAs, uma de resumo e outra de que
geraria insights empresariais com base nesse resumo.

Atualmente já temos a parte das duas IAs funcionando, e com base na ideia
original falta apenas a capacidade de processar arquivos brutos.

## Bibliotecas, modelos e APIs utilizadas

### Bibliotecas

PyTorch

Transformers

Google Gen AI

### Modelos pré-treinados

Phi-3-mini-128k-instruct

Gemini AI (API)

## Uso de cada um

**PyTorch**: Utilizamos o PyTorch para carregar e configurar o modelo Phi-3-Mini.

**Transformers**: Utilizamos o Transformers para o pré-processamento de texto, tokenização, codificação de sequências de palavras e geração do conteúdo.

**Google Gen AI**: Usada para conectar com a API Gemini AI.

**Phi-3-mini-128k-instruct**: Modelo usado para gerar resumos de conteúdo passado, no caso dessa demo é um relatório fictício.

**Gemini AI**: Modelo usado para gerar insights empresariais com base no resumo gerado pelo Phi-3-mini-128k-instruct.

## Conceitos de Machine Learning utilizados

Nesse projeto utilizamos o conceito processamento de linguagem natural (NLP) para gerar resumos e insights empresariais.

## Membros do projeto

Cauã Alencar Rojas Romero - RM98638

Jaci Teixeira Santos - RM99627

Leonardo dos Santos Guerra - RM99738

Maria Eduarda Ferreira da Mata - RM99004
