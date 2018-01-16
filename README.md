# Identify-best-Classifier-for-dataset-using-Weka

Introduction:

The classification features describing the data related to fine art painting are as follows:
- Name of the Painting
- Artist Name
- Size of the Painting
- Price
- Number of Views
- Number of Favorites
- Date
- Subject
- Medium

New Features added:

We’ve picked five new attributes which are as follows:
- Painting Surface
- Artist Recognition
- Artist country
- Shipment Mode
- Keywords

 1) The aim of our project is to build our own database with all the attributes mentioned above are extracted from the website called as       the "saatchiart.com" (link: http://www.saatchiart.com/paintings/fine-art). Form all the classification features, we will consider price     as decision attribute and discretize it into three intervals in such a way that the resultant classifier should have highest precision.
 2) In order to compare which classifier has highest precision among the chosen classifiers, we’ll import the data into "weka" tool and         process the data for chosen classifiers. The Classifiers we chose are Naive Bayes, Decision Tree, Random Forest, Logistic Regression.
 3) Reasons for choosing new features in this project: 
    We found that by adding the above five new features will improve our model and precision of our model. These five new features are more     important features that describes about painting and artist which helps to build our model. For example: "Artist recognition" is           important because, if highly recognized artist is featured in a collection then chance of his/her paintings having more value/price is     high for that particular paintings.
