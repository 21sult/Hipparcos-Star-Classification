# Hipparcos-Star-Classification

This code uses the Hipparcos Star Catalogue in order to build a classification model using Random Forests, to predict the spectral types of stars. The catalogue contains data of 118,200 stars, and was a product of a combination of measurements of i) radial velocity, through astrometry; ii) instrinsic brightness, proper motion, and parallax of stars, through the observations of Hipparcos (HIgh Precision PARallax COllecting Satellite), of the European Space Agency, which operated between 1989 and 1993, and was the first satellite to enable high precision measurements of these quantities (within ~0.002 arcseconds for RA, Dec and PM). It was published in 1997.

## 1. Data analysis
- Hertzprung-Russel diagram
- Distributions of stellar parallax, magnitude and spectral types
- Maps of right ascension vs. declination, and proper motion
- Relationships between distance, magnitude and errors in parallax, right ascension, declination and proper motion
- Preprocessing for the classification model.

 ![image](https://github.com/21sult/Hipparcos-Star-Classification/assets/145617965/c6b69c93-bec9-4eb4-bc72-39170cf0a47b)
 <img src="https://user-images.githubusercontent.com/link-to-your-image.png](https://github.com/21sult/Hipparcos-Star-Classification/assets/145617965/c6b69c93-bec9-4eb4-bc72-39170cf0a47b" width="200" />

## 2. Classification Model (Random Forests)
The typical AUC obtained was about 0.89, and the model is able to make accurate predictions on stellar types and subtypes.

![image](https://github.com/21sult/Hipparcos-Star-Classification/assets/145617965/757a3c9c-ed33-44b4-9752-8469a8a0ec9a)

