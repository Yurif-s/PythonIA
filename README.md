<p align="center"><a href="https://www.crewai.com/" target="_blank"><img src="https://docs.crewai.com/crew_only_logo.png" width="340" alt="CrewAI Logo"></a></p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

# IA para Avaliação de Stock

Este projeto inclui a construção de Inteligência Artificial utilizando o modelo LLM do GPT, Python e CrewAI(Framework) com três Agentes

## O que é LLM (Large Language Models)?

- Modelos de gerais treinados com uma vasta quantidade de dados.
- Capaz de aprender padrões linguísticos e realizar tarefas.

## LLM do GPT

- Para a utilização do LLM do GPT, deve-se possuir uma conta na [OpenAI](https://openai.com/) e a criação de uma API Key pelo site https://platform.openai.com/api-keys (A permissão da utilização da API KEY do OpenAI não é gratuita, ou seja, se deve ter saldo na conta. Acesse: https://platform.openai.com/usage) 

## Como funciona a Avaliação de Stock?
São feitas: 
- Análise do preço histórico da ação;
- Análise das notícias da empresa;
- Avaliação da ação;
- Cada uma dessas acima são reponsáveis por um Agente.

# Tecnologias do projeto

- [Python](https://www.python.org/): Linguagem de Programação
- [CrewAI](https://www.crewai.com/): Framework Python para Desenvolvimento IA

# Pré-requisitos

Copie o arquivo requirements.txt e execute o seguinte comando no cmd para a instalação das devidas bibliotecas e do CrewAI
```
  pip install -r requirements.txt
```

Agora você pode executar as células do crewai-stock.ipynb (Lembrando que só será possível se você colocar a sua própria API Key, estando paga.)

## Para a execução do arquivo crewai_stock.py, deve-se o uso da biblioteca Streamlit
<p align="center"><a  href="https://streamlit.io/" target="_blank"><img src="https://user-images.githubusercontent.com/7164864/217935870-c0bc60a3-6fc0-4047-b011-7b4c59488c91.png" width="100" alt="Streamlit Logo"></p>

## **Streamlit**: Lib Python, uma maneira mais rápida de criar e compartilhar aplicativos de dados
