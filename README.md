# Hackathon - Popular CBBC product 


<b>Problem</b>

We need to find the factors responsible for popular CBBC product based on net sales from issuer perspective based on the historical data. We need to use AWS for this purpose. The data_description file contains the data info that will be available for the problem.

<b>Solution</b> 

We used AWS DeepAR forecast model to create a model for the CBBC product sales calculation. Using it we were able to incorporate the time series factors as well as static product factors for the net sales calculation.
The featuresToBeUsed.txt file contains the features that we planned to use to create the model although we finally used on static product features in the interest of time.
The modelloss.png file contains the model loss.
