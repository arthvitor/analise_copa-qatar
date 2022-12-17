# Análise de Conteúdo - Copa no Catar
O projeto desse repositório é um algoritmo para extrair e aplicar análise de conteúdo (polaridade) em tweets da cobertur jornalística da copa no Catar, nos veículos Globo Esporte, Lance, Uol Esportes e ESPM. Nesse projeto, foi utilizado pela equipe os algortimos de aprendizado de máquina supervisionado ```NaiveBayesClassifier```, ```MaxentClassifier``` e ```SklearnClassifier```. 

## Como começar?
1. Abrindo o notebook ```Trabalho_Mineração.ipynb``` para executar a extração dos tweets (sem necessidade de conta de desenvolvedor do Twitter);
2. Executar os códigos de tratamento e amostragem dos tweets de treino (caso queira replicar o resultado, insira os arquivos de treino ```.data``` dispostos de coleta na pasta ```data```;
3. Executar os códigos dos algoritmos de aprendizagem de máquina (para replicar, insira os arquivos da coleta de cada veículo)

## Sobre a coleta:
As coletas foram realizadas pela biblioteca Twint com as queries: "Catar", "Qatar" e "Copa", gerando 3 arquivos por veículo.

## Sobre os arquivos:

### ```[palavra-chave]_[veículo].csv```:
Arquivos com tweets extraindos através do twint, para cada palavra-chave utilizada para cada veículo;

### ```treino_[sentimento].csv```:
Arquivos de treino ```.data``` para treinar os algoritmos de machine learning, para cada sentimento analisado: positivo, negativo e neutro.

### ```mineração_arquivo_classificado.csv```:
Arquivo com os tweets já classificados com cada algoritmo de classificação automática.

## Equipe
Ananda Ridart, Gabriel Ronan, Géssica Brandino e Vitor Arthur

## Finalidade do projeto
Trabalho realizado como projeto final da disciplina Mineração de Dados Não Estruturados, do Master em Jornalismo de Dados, Automação e Data Storytelling do Insper.
