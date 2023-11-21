# Hipparcos-Star-Classification

This code uses the Hipparcos Star Catalogue in order to build a classification model using Random Forests, to predict the spectral types of stars. The catalogue contains data of 118,200 stars, and was a product of a combination of measurements of i) radial velocity, through astrometry; ii) instrinsic brightness, proper motion, and parallax of stars, through the observations of Hipparcos (HIgh Precision PARallax COllecting Satellite), of the European Space Agency, which operated between 1989 and 1993, and was the first satellite to enable high precision measurements of these quantities (within ~0.002 arcseconds for RA, Dec and PM). It was published in 1997.

## 1. Data analysis
- Hertzprung-Russel diagram
<img src="https://github.com/21sult/Hipparcos-Star-Classification/hrdiag.PNG" width="200" />
- Distributions of stellar parallax, magnitude and spectral types
<img src="https://github.com/21sult/Hipparcos-Star-Classification/sptypes.PNG" width="200" />
- Maps of right ascension vs. declination, and proper motion
- Relationships between distance, magnitude and errors in parallax, right ascension, declination and proper motion
- Preprocessing for the classification model.

## 2. Classification Model (Random Forests)
The typical AUC obtained was about 0.89, and the model is able to make accurate predictions on stellar types and subtypes.

 <img src="https://github.com/21sult/Hipparcos-Star-Classification/roc.PNG" width="200" />

