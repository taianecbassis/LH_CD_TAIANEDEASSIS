# README - Projeto de Previsão de Preços de Aluguéis da cidade de Nova York

Este projeto implementa modelos de machine learning para prever os preços de aluguéis de imóveis na cidade de Nova York.

## Instalação e Execução do Projeto

1. **Requisitos do Sistema**:
   - Python 3.x
   - Jupyter Notebook ou Google Colab (para executar o código fornecido)

2. **Clonar o Repositório**:
   - Clone este repositório para o seu ambiente local:
     ```
     git clone https://github.com/seu-usuario/nome-do-repositorio.git
     ```
   - Ou baixe o arquivo ZIP e extraia-o em seu computador.

3. **Instalar Dependências**:
   - Abra o Jupyter Notebook ou Google Colab.
   - Execute o código fornecido no notebook para treinar os modelos.

## Arquivos de Requisitos

- O arquivo de requisitos `requirements.txt` contém os pacotes Python necessários para executar o projeto.

## Pacotes Utilizados e Versões

- numpy==1.19.5
- pandas==1.3.3
- scikit-learn==0.24.2
- tensorflow==2.6.0
- keras==2.6.0
- joblib==1.0.1

## Arquivo .pkl

* Como Usar e Implementar um Modelo Salvo em um Arquivo .pkl

Este guia explica como usar e implementar um modelo de machine learning salvo em um arquivo .pkl (pickle) em Python.

* Passos para Implementação

1. Carregar o Modelo Salvo:

Para começar, o usuário precisa carregar o modelo salvo a partir do arquivo .pkl. Isso pode ser feito usando a função `joblib.load()` da biblioteca joblib ou a função `pickle.load()` da biblioteca pickle, dependendo de como o modelo foi salvo.

```python
import joblib

# Carregar o modelo salvo
modelo_carregado = joblib.load('caminho/do/arquivo/modelo.pkl')

2. Preparar os Dados de Entrada:
O usuário deve preparar os dados de entrada de acordo com as características esperadas pelo modelo. Isso pode envolver pré-processamento de dados, transformações e formatação adequada dos dados.

3. Fazer Previsões:
Com o modelo carregado e os dados de entrada preparados, o usuário pode fazer previsões usando o modelo. Isso é feito chamando o método predict() do modelo carregado.

# Prever com o modelo carregado
previsoes = modelo_carregado.predict(dados_de_entrada)

4. Exemplo de implementação
import joblib

# Carregar o modelo salvo
modelo_carregado = joblib.load('caminho/do/arquivo/modelo.pkl')

# Preparar os dados de entrada
dados_de_entrada = ...

# Fazer previsões
previsoes = modelo_carregado.predict(dados_de_entrada)


## Autores

- Taiane C. B. de Assis - [GitHub](https://github.com/taianecbassis)

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE).
