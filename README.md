# House Rent Price Prediction with Image Classification

This project aims to predict house rent prices using a combination of traditional features scraped from real estate listings and image classification models. Leveraging data from bina.az, a leading real estate platform, we've developed a comprehensive solution that incorporates both numerical features and visual data to improve the accuracy of rent price predictions.

# Key Components:
## Traditional Feature Extraction: 
We scraped various features from bina.az, including location, number of rooms, square footage, amenities, and more, to build a robust dataset for training our predictive models.

## Image Classification with ResNet18:
We employed state-of-the-art deep learning techniques, utilizing the ResNet18 architecture, to classify house images. We trained two image classification models:

## Binary Model:
This model determines whether a house is suitable for rent based on the presence of interior images. If there are no interior images, the house is deemed unsuitable; otherwise, it is classified as suitable.
## Multi-class Model: 
This model evaluates the condition of the house interior across four classes: 'Excellent', 'Good', 'Average', and 'Poor', providing a more nuanced understanding of the property's condition.
## Vision Score Calculation: 
In addition to classifying the interior condition, we calculate a vision score for each house based on the image analysis results. This score provides an intuitive metric for assessing the overall visual appeal of the property, which can influence its rental value
