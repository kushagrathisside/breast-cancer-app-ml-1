<p align="left">
	<img width="300" src="https://drive.google.com/uc?export=view&id=1Q-jMna73t3OcGULw_TAi2M786kinOZNZ" />
	<h2 align="left"> BREAST CANCER PREDICTION MODEL </h2>
	<h4 align="left"> This model is being trained to make predictions about cancer the patient is most likely suffering. This can be used both by medical practitioner and the patient provided data is provided from a proper medical report. The data project predicts whether the patient actually has breast cancer or not from the data provided by the User. <h4>
	
</p>

---
[![DOCS](https://img.shields.io/badge/Documentation-see%20docs-green?style=for-the-badge&logo=appveyor)](INSERT_LINK_FOR_DOCS_HERE) 
  [![UI ](https://img.shields.io/badge/User%20Interface-Link%20to%20UI-orange?style=for-the-badge&logo=appveyor)](INSERT_UI_LINK_HERE)


## Functionalities
- [ ]  Predict if patient's data predicts between 'Benign' and 'Maligant'. <br>      <dl>
	<dt><b>Benign</b></dt><dd>'Benign' cancer is the cancer which doesn't spread and are non cancerous. In most cases, a doctor diagnosing a tumor as benign will most likely be left alone.  Benign tumors are not generally aggressive around the surrounding tissue and in some cases, may continue to grow. If the tumor continues to grow and cause discomfort by pressing against surrounding organs and causing pain, the tumor would be removed.</dd>
	<dt><b>Malignant</b></dt><dd>'Malignant' cancer cells spread across the body making it very dangerous. Malignant tumors are aggressive and cancerous because damage the surrounding tissue and may be removed depending on the cancerous and aggressive on the severity or aggressiveness of the tumor.</dd></dl>
- [ ]  Helps in visualization of the dataset using Maps and graphs and provide a basic idea of the dataset.
	Eg: Heatmap<br><br><br>
	![PLOT3](https://user-images.githubusercontent.com/76547274/139423128-89d21ed4-75f1-4c4b-823a-0b8f209406d5.png)


<br><br>
<h2>DataSet Column/Input required for Predictions:</h2>
ID number(unique per record)<i>Not needed for trained, just for reference</i> 
Diagnosis (M = malignant, B = benign)<i> Testing field</i>
<br>Ten real-valued features are computed for each cell nucleus:
<ol>
<li>Radius(mean of distances from center to points on the perimeter)</li>
<li>Texture (standard deviation of gray-scale values)</li>
<li>Perimeter</li>
<li>Area</li>
<li>Smoothness (local variation in radius lengths)</li>
<li>Compactness (perimeter² / area — 1.0)</li>
<li>Concavity (severity of concave portions of the contour)</li>
<li>Concave points (number of concave portions of the contour)</li>
<li>Symmetry</li>
<li>Fractal dimension</li></ol>
	Each of the 10 values are further given as 3 values in a total of 30 columns, which include mean, standard error and worst values from images taken of the cell.

<h3>Link for Kaggle Database:</h3> You may refer this link, this will also provide you with DataSet.<a href="https://www.kaggle.com/buddhiniw/breast-cancer-prediction/data"> 'breast-cancer-prediction' </a>(You may have to clean dataset to get it in ready to use state as few records contain 0s which may effect the prediction)<br>

## Instructions to run

* Pre-requisites:
	-  Python Language and its libraries including Pandas, Numpy, Matplotlib etc.
	-  Machine Learning Algorithms like....<i>(still working on improving efficiency of model using different algorithms). Few under consideration are mentioned below:</i>            <ul>
	   <li> Decision Trees Algorithm</li>
           <li> Gradient Boosting Algorithm</li> 
           <li> k-Nearest Neighbors Algorithm</li>
           <li> Logistic Regression Algorithm</li>
           <li> Random Forests Algorithm</li>
           <li> Support Vector Machine Algorithm</li>
	</ul>

* Directions to setup/install
```bash
< insert code >
```

* Directions to execute

```bash
< insert code >
```

<br>

## Contributors

* <a href="https://github.com/kushagrathisside">KUSHAGRA SRIVASTAVA</a> 



<br>
<br>

<p align="center">
	Made during 🌙 by DSC KIET
</p>
