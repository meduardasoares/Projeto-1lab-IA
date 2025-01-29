# Projeto-1lab-IA
# **Projeto-1lab-IA**

Classificação automatizada de dados com Azure AutoML.  
Este projeto utiliza o **Azure Machine Learning (AutoML)** para treinar um modelo de **classificação**, categorizando informações com base em diferentes atributos relevantes ao contexto analisado.  

## **Tecnologias Utilizadas**  
- **Azure Machine Learning (AutoML)**  
- **Python**  
- **GitHub**  

## **Descrição do Projeto**  
O objetivo deste projeto é construir um modelo de **aprendizado de máquina automatizado** para **classificação de dados**, utilizando **Azure AutoML**.  
O modelo foi treinado a partir de um conjunto de dados contendo informações detalhadas e relevantes ao problema de classificação, permitindo uma categorização precisa de novas informações.  

## **Conjunto de Dados**  
Os dados utilizados no treinamento incluem as seguintes colunas:  

- **Atributo 1** → Exemplo de um atributo relevante para classificação.  
- **Atributo 2** → Outro fator importante na categorização.  
- **Atributo 3** → Informação adicional que influencia os resultados.  
- **Atributo 4** → Outros detalhes que impactam a classificação.  
- **Classe (variável alvo)** → Categoria final prevista pelo modelo.  

## **Passo a Passo**  

### **1. Configuração do AutoML no Azure ML Studio**  
   - Criado um **experimento do tipo Classificação**.  
   - Carregado o dataset de dados categorizados.  

### **2. Treinamento do Modelo**  
   - O **Azure AutoML** testou vários modelos automaticamente.  
   - O melhor modelo foi escolhido com base na métrica **Acurácia**.  

### **3. Implantação e Testes**  
   - O modelo foi implantado como um **endpoint na nuvem**.  
   - Foram realizados testes para validar a precisão das previsões. 

## **Resultados**  
- O modelo alcançou uma **acurácia de XX%** (substitua pelo seu resultado).  
- Foi possível classificar os dados corretamente em **XX% dos casos**.  

## **Como Executar o Projeto**  

1. Clone este repositório:  
   ```bash
    git clone https://github.com/meduardasoares/Projeto-1lab-IA
