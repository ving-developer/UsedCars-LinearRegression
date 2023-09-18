<p align="center"></p>
<p align="center">
  <span>🡇&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
  <br>
  <a href="#">English 🇬🇧</a>
  ·
  <a href="/docs/readme_pt-BR.md">Português  🇧🇷</a>
</p>

# <div align="center"> Used Cars - Linear Regression </div>

<div style="display: inline_block" align="center">
  <img src="https://img.shields.io/github/last-commit/ving-developer/UsedCars-LinearRegression?style=flat&logo=github"/>
  <img src="https://img.shields.io/github/stars/ving-developer?logo=github&color=yellow"/>
  <a href="https://www.linkedin.com/in/henrique-barros-7b1812209/">
    <img src="https://img.shields.io/badge/Linkedin-Henrique%20Barros-blue?style=flat&logo=linkedin"/>
  </a>
</div>

### <div align="center"> 〞Used Car Price Prediction〝</div>
<div align="center">
  <img width="400" src=".\assets\dataset-thumbnail.jpg" alt="Used Cars" href ="https://www.kaggle.com/datasets/thedevastator/uncovering-factors-that-affect-used-car-prices"/>
  <br>
  <br>
</div>

> *[Used Cars](https://www.kaggle.com/datasets/thedevastator/uncovering-factors-that-affect-used-car-prices)*, is a German Dataset with **371825** *instances* , containing **20** *attributes* about used car advertisements spread across the internet. The objective here will be to make used car price predictions based on the attributes offered in this Dataset.
>
> For this, *[Used Cars](https://www.kaggle.com/datasets/thedevastator/uncovering-factors-that-affect-used-car-prices)* is being used to train **Machine Learning algorithms **, mainly **Linear Regression** and **Gradient Descent**. After training, 20% of the data from the Dataset itself is used to check performance using **Mean Squared Error (MSE)** and **Coefficient of Determination (R2)**.

<br>

## Dataset Describe

| Nome da Coluna        | Descrição                                                               |
|-------------------|----------------------------------------------------------------------------|
| dateCrawled | Date the car was announced (Date) |
| name | Car name (String) |
| seller | Type of advertisement (private or reseller) (String) |
| offerType | Type of offer (private, repair). (String) |
| price | Car price. (Integer) |
| abstest | Test drive type (String) |
| vehicleType | Vehicle Type (SUV, Sedan, Hatch...) (String) |
| yearOfRegistration| Car registration year (Integer) |
| gearbox | Type of transmission - manual or automatic (String) |
| powerPS | Engine power - horsepower. (Integer) |
| model | Car Model (String) |
| kilometer | Kilometers traveled (Integer) |
| monthOfRegistration | Month the car was registered (Integer) |
| fuelType | Fuel type (String) |
| brand | Car brand (String) |
| notRepairedDamage | Whether or not the car has any damage that has not been repaired (String) |
| dateCreated | Date the car was created (Date) |
| nrOfPictures | Number of car photos (Integer) |
| postalCode | Car zip code (Integer) |
| lastSeen | Date the car was last inspected (Date) |

## Usage

After cloning the repository, run [Jupyter Notebook](https://jupyter.org/) on your machine, look for the location where the repository was cloned and open the `Notebook.ipynb` file.

If there is a problem with any package import, try adding a code cell and executing it. After execution this cell can be removed.

```python
# Install a pip package in the current Jupyter kernel
import sys
!{sys.executable} -m pip install numpy
  ```

  ## Dependencies
 
  Libraries used:
 * [Scikit Learn](https://scikit-learn.org/stable/supervised_learning.html#supervised-learning)
 * [XGBoost](https://xgboost.readthedocs.io/en/stable/)
 * [Numpy](https://numpy.org/doc/stable/user/absolute_beginners.html)
 * [Pandas](https://pandas.pydata.org/docs/getting_started/index.html#getting-started)
 * [Plotly](https://plotly.com/python-api-reference/)
 * [Seaborn](https://seaborn.pydata.org/api.html)
 * [Matplotlib](https://matplotlib.org/stable/index.html)