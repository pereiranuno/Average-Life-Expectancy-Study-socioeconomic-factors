
# Life Expectancy and Socioeconomic Factors

## Introdução
Este projeto explora fatores socioeconômicos e sua influência na expectativa de vida de diversas regiões ao redor do mundo.

## Objetivo
Este notebook Python realiza uma análise dos fatores socioeconômicos que afetam a expectativa de vida, utilizando um conjunto de dados público. O objetivo é identificar relações importantes e desenvolver insights sobre como diferentes variáveis, como PIB e escolaridade, podem afetar a saúde da população.

## Conteúdo

1. **Importação de Bibliotecas**:  
   O notebook utiliza as seguintes bibliotecas:
   ```python
   import matplotlib.pyplot as plt
import pandas as pd
import numpy as np
import seaborn as sns
from sklearn.linear_model import LinearRegression
from scipy import stats
   ```

2. **Carregamento de Dados**:  
   # **Importação de Bibliotecas e dataset**


---


Nesta secção, são importadas as bibliotecas utilizadas no projeto, assim como realizada a ingestão de um ficheiro CSV com o conteúdo de análise do projeto, carregado para um DataFrame utilizando a biblioteca Pandas.


3. **Pré-processamento dos Dados**:  
   Nesta secção, os dados são limpos e preparados para análise. Inclui tratamento de valores ausentes e normalização de variáveis.

4. **Análise Exploratória**:  
   São gerados gráficos e estatísticas descritivas para explorar as relações entre variáveis socioeconômicas e expectativa de vida.

5. **Modelagem (Opcional)**:  
   Nesta secção, um modelo de Machine Learning pode ser desenvolvido para prever a expectativa de vida com base nos fatores disponíveis.

6. **Conclusões**:  
   Principais insights são apresentados, destacando como certos fatores como renda e educação estão relacionados à expectativa de vida.

## Requisitos

Certifica-te de que tens os seguintes pacotes instalados para executar o notebook corretamente:

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

Podes instalar todos os pacotes necessários utilizando o ficheiro `requirements.txt` com o comando:

```bash
pip install -r requirements.txt
```

## Como Utilizar

1. **Clone este repositório**:
   ```bash
   git clone https://github.com/teu-usuario/life-expectancy-analysis.git
   ```
2. **Navega até a pasta do projeto**:
   ```bash
   cd life-expectancy-analysis
   ```
3. **Instala os requisitos**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Abre o Jupyter Notebook**:
   ```bash
   jupyter notebook Life_Expectancy_and_Socioeconomic_Factors.ipynb
   ```

## Estrutura do Repositório

- `Life_Expectancy_and_Socioeconomic_Factors.ipynb`: O ficheiro principal contendo o código Python e a análise.
- `data/`: Pasta que contém o(s) ficheiro(s) de dados necessários para o notebook.
- `requirements.txt`: Lista de pacotes Python necessários.

## Contribuições

Contribuições são sempre bem-vindas! Se desejares contribuir, por favor segue os passos:

1. Cria um *fork* do repositório.
2. Cria uma *branch* para a tua funcionalidade (`git checkout -b feature/NomeFuncionalidade`).
3. Faz o *commit* das tuas alterações (`git commit -m 'Adicionada nova funcionalidade'`).
4. Faz *push* para a *branch* (`git push origin feature/NomeFuncionalidade`).
5. Abre um *Pull Request*.

## Licença

Este projeto está sob a licença [Nome da Licença]. Sente-te à vontade para usar, modificar e distribuir o conteúdo deste repositório de acordo com os termos da licença.

## Contacto

Para dúvidas ou sugestões, podes entrar em contacto através de [teu-email@exemplo.com] ou abrir uma *issue* aqui no GitHub.
