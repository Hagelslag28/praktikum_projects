# Gold recovery rate estimate

## Task
An international company develops solutions for the efficient operation of industrial enterprises, and it has an order from a gold mining plant.

The model in question should predict the recovery rate of gold from gold ore. The modelshould be able to help optimize production so as not to launch an enterprise with unprofitable characteristics.

The metric requested by the client is custom and is called [sMAPE](https://pictures.s3.yandex.net/resources/smape_1576239058.jpg). The final sMAPE equals to 25% of rougher concentrate sMAPE and 75% of final concentrate sMAPE.

## Data
We have data with extraction and cleaning parameters at our disposal. The data is highly technical and hardly interpretable, but the technological process is described as follows:
- initial ore undergoes
    * flotation
- rougher concentrate is obtained. then it undergoes:
     * first cleaning phase
    * second cleaning phase
- final concentrate is obtained.

## Libraries
- pandas
- sklearn
- matplotlib
- numpy
- seaborn
- optuna
- catboost
