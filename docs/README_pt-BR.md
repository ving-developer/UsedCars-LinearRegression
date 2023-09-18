<p align="center"></p>
<p align="center">
  <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🡇</span>
  <br>
  <a href="../README.md">English 🇬🇧</a>
  ·
  <a href="#">Português  🇧🇷</a>
</p>

# <div align="center"> Used Cars - Regressão Linear </div>

<div style="display: inline_block" align="center">
  <img src="https://img.shields.io/github/last-commit/ving-developer/UsedCars-LinearRegression?style=flat&logo=github"/>
  <img src="https://img.shields.io/github/stars/ving-developer?logo=github&color=yellow"/>
  <a href="https://www.linkedin.com/in/henrique-barros-7b1812209/">
    <img src="https://img.shields.io/badge/Linkedin-Henrique%20Barros-blue?style=flat&logo=linkedin"/>
  </a>
</div>

### <div align="center"> 〞Previsão de preços para carros usados〝</div>
<div align="center">
  <img width="400" src="..\assets\dataset-thumbnail.jpg" alt="Used Cars" href ="https://www.kaggle.com/datasets/thedevastator/uncovering-factors-that-affect-used-car-prices"/>
  <br>
  <br>
</div>

> *[Used Cars](https://www.kaggle.com/datasets/thedevastator/uncovering-factors-that-affect-used-car-prices)*, é um Dataset alemão com **371825** *instâncias*, contendo **20** *atributos* sobre anúncios de carros usados espalhados pela internet. O objetivo aqui será realizar previsões de preços de carros usados com base nos atributos oferecidos neste Dataset.
>
> Para isso, está sendo utilizado *[Used Cars](https://www.kaggle.com/datasets/thedevastator/uncovering-factors-that-affect-used-car-prices)* para treinar algoritmos de **Machine Learning**, sendo eles principalmente **Regressão Linear** e **Gradiente Descendente**. Após o treinamento, é utilizado 20% dos dados do próprio Dataset para conferir a performance utilizando **Mean Squared Error (MSE)** e **Coeficiente de Determinação (R2)**.

<br>

## Descrição do Dataset

| Nome da Coluna        | Descrição                                                               |
|-------------------|----------------------------------------------------------------------------|
| dateCrawled       | Data em que o carro foi anunciado (Date)                                           |
| name              | Nome do carro (String)                                                  |
| seller            | Tipo de anuncio (particular ou revendedor) (String)                               |
| offerType         | Tipo de oferta (particular, reparo). (String)                         |
| price             | Preço do carro. (Integer)                                              |
| abtest            | Tipo de test-drive (String)                                 |
| vehicleType       | Tipo  do veículo (SUV, sedan, Hatch ...) (String)                         |
| yearOfRegistration| Ano de registro do carro (Integer)                                     |
| gearbox           | Tipo do cambio - manual ou automatico (String)                           |
| powerPS           | Potencia do motor - cavalos de potencia. (Integer)                                          |
| model             | Modelo do carro (String)                                                 |
| kilometer         | Kilometros rodados (Integer)                              |
| monthOfRegistration | Mes que o carro foi registrado (Integer)                                   |
| fuelType          | Tipo do combustível (String)                        |
| brand             | Marca do carro (String)                                                 |
| notRepairedDamage | Se o carro apresenta ou não algum dano que não foi reparado (String) |
| dateCreated       | Data que o carro foi criado (Date)                                           |
| nrOfPictures      | Número de fotos do carro (Integer)                                   |
| postalCode        | Código postal do carro (Integer)                                          |
| lastSeen          | Data em que o carro foi vistoriado pela última vez (Date)                                         |

## Uso

Após clonar o repositório, execute o [Jupyter Notebook](https://jupyter.org/) na sua máquina, procure pelo local aonde o repositório foi clonado e abra o arquivo `Notebook.ipynb`.

Caso dê problema em alguma importação de pacotes, tente adicionar uma célula de código e executar. Após a execução esta célula pode ser removida.

```python
# Install a pip package in the current Jupyter kernel
import sys
!{sys.executable} -m pip install numpy
 ```

 ## Dependências
 
 Bibliotecas utilizadas:
 * [Scikit Learn](https://scikit-learn.org/stable/supervised_learning.html#supervised-learning)
 * [XGBoost](https://xgboost.readthedocs.io/en/stable/)
 * [Numpy](https://numpy.org/doc/stable/user/absolute_beginners.html)
 * [Pandas](https://pandas.pydata.org/docs/getting_started/index.html#getting-started)
 * [Plotly](https://plotly.com/python-api-reference/)
 * [Seaborn](https://seaborn.pydata.org/api.html)
 * [Matplotlib](https://matplotlib.org/stable/index.html)