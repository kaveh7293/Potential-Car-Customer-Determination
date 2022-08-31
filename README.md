# Potential-Car-Customer-Determination
<h2> Overview of the Project</h2>
<p> In this project, I developed a <a href='https://car-customers.herokuapp.com/'><strong>web application</strong> </a> that helps the salespersons to identify the potential customers. In this project, we can assume tha the informations can be obtained from a previous survay. So, the salespersons have so many data but they do not know to which customer they should contact. I developed this web application to help them. To develop this web application, I have done the following steps:<br>
<ol>
<li>Train a classification model using data from <a href='https://www.kaggle.com/datasets/gabrielsantello/cars-purchase-decision-dataset'> here </a>. This is a very simple dataset, yet result in very powerful classification model which is able to predict  with an accuracy of 0.90. I used a randomized search method to find simultaneouosly the best model and the best values for hyperparameters. You can find the notebook for this computations <a href='https://github.com/kaveh7293/Potential-Car-Customer-Determination/blob/main/Untitled55.ipynb'>here</a></li>
<li>Pickle the trained model and use it in a web app. Our web app is created using flask. The front end of this web application is created using a combination of html and css. Note that, in order to create this pickled web application, I created a pipeline so that the it returns the output by receiving the raw values of the inputs prior to preprocessing.</li></ol>
<br>
This web app provide a user-friendly tool for the salespersons so that they can readily use a trained machine learning model for their marketing purposes.




</p>
