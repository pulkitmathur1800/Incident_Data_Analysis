# Incident_Data_Analysis
Use Case: Within a firm there are technical incidents that get reported and later resolved. The problem is to find how many incidents will occur in future, this would help tech support to arrange tech support guys. Also we need to find the major cause for a particular incident

## Dataset
![1stslide](https://user-images.githubusercontent.com/29193001/42799497-b2a995a8-89b5-11e8-931a-bc26a9689162.png)

The dataset includes incidents that have occured from 2016-11-01 to 2017-04-30 

The following graph plots incidents priority wise
<img width="600" height="380" src="https://user-images.githubusercontent.com/29193001/42799906-325b3e04-89b7-11e8-817b-1b46ef64cb47.png">
<img width="250" height="150" align ="right" src="https://user-images.githubusercontent.com/29193001/42799907-32970c40-89b7-11e8-98e1-714c63526049.png">

# Distribution Of Incidents Priority wise from 2016-11-01 to 2017-04-30 

![priority1](https://user-images.githubusercontent.com/29193001/42799386-4b10cea2-89b5-11e8-86d1-e9672e6fbe2c.png)
![priority2](https://user-images.githubusercontent.com/29193001/42799388-4b65d370-89b5-11e8-801c-152fc95e0852.png)
![priority3](https://user-images.githubusercontent.com/29193001/42799389-4bdd4ce8-89b5-11e8-82c7-1426a9d83594.png)
![priority-4](https://user-images.githubusercontent.com/29193001/42799390-4c1f115a-89b5-11e8-9fd6-f6745a7b3f87.png)
![priority-5](https://user-images.githubusercontent.com/29193001/42799392-4c6672a2-89b5-11e8-9e79-1791b9b5411b.png)

### Training Data- 
From 01/11/2016
To      23/04/2017
### Testing Data-
From 24/04/2017
To      30/04/2017

## Model-1.1 
![model1forecast](https://user-images.githubusercontent.com/29193001/42799399-4e81755a-89b5-11e8-9414-a2b364599cb6.png)

<p align="center">
<img src="https://user-images.githubusercontent.com/29193001/42807114-95fb465a-89cd-11e8-99a6-7437595d1d68.png">
</p>

![model1predictiongraph](https://user-images.githubusercontent.com/29193001/42799400-4ecba09e-89b5-11e8-8fce-001a5d3dbc8b.png)

<figure>
<figcaption>Actual</figcaption>
<img src="https://user-images.githubusercontent.com/29193001/42807110-95c1ae0e-89cd-11e8-8482-3cc780cd412a.png">
<figcaption>Predicted</figcaption>
<img src="https://user-images.githubusercontent.com/29193001/42807118-968358ce-89cd-11e8-9b9e-ea261073dd8a.png">
</figure>


## Model-1.2 (Removed Outliers)
![model2forecast](https://user-images.githubusercontent.com/29193001/42799401-4f0e7928-89b5-11e8-89fc-75c59fdc591e.png)

<p align="center">
<img src="https://user-images.githubusercontent.com/29193001/42807116-964121ca-89cd-11e8-874e-10390abf9dac.png">
</p>

![model2predictiongraph](https://user-images.githubusercontent.com/29193001/42817756-b3a82028-89ec-11e8-9bb7-dae936d78e04.png)

<figure>
<figcaption>Actual</figcaption>
<img src="https://user-images.githubusercontent.com/29193001/42807105-94bca9b4-89cd-11e8-87c5-e6d375a23a0a.png">
<figcaption>Predicted</figcaption>
<img src="https://user-images.githubusercontent.com/29193001/42807109-9571db36-89cd-11e8-8dee-22775226c455.png">
</figure>


## Model-1.3 (Removed Trend)
![model3graph](https://user-images.githubusercontent.com/29193001/42816780-8bb952e2-89e9-11e8-8fe6-bd630bfca2bd.png)

<p align="center">
<img src="https://user-images.githubusercontent.com/29193001/42816870-d768d370-89e9-11e8-81dd-d71b96038870.png">
</p>

![model3predictiongraph](https://user-images.githubusercontent.com/29193001/42816779-8b5c4b56-89e9-11e8-935c-ce77fe199ae7.png)

<figure>
<figcaption>Actual</figcaption>
<img src="https://user-images.githubusercontent.com/29193001/42816872-d7ec421e-89e9-11e8-8096-2c74500ad7a9.png">
<figcaption>Predicted</figcaption>
<img src="https://user-images.githubusercontent.com/29193001/42816871-d7a87cbe-89e9-11e8-9dee-11ff2b5fcffa.png">
</figure>




