
# King County Home Sales Analysis
The objective of this project is to create a model that will provide useful information for stakeholders about the home prices in King County, WA.

### Dataset
The dataset includes the following features:

* **id** - unique identified for a house
* **dateDate** - house was sold
* **pricePrice** -  is prediction target
* **bedroomsNumber** -  of Bedrooms/House
* **bathroomsNumber** -  of bathrooms/bedrooms
* **sqft_livingsquare** -  footage of the home
* **sqft_lotsquare** -  footage of the lot
* **floorsTotal** -  floors (levels) in house
* **waterfront** - House which has a view to a waterfront
* **view** - Has been viewed
* **condition** - How good the condition is (overall)
* **grade** - overall grade given to the housing unit, based on King County grading system
* **sqft_above** - square footage of house apart from basement
* **sqft_basement** - square footage of the basement
* **yr_built** - Built Year
* **yr_renovated** - Year when house was renovated
* **zipcode** - zip
* **lat** - Latitude coordinate
* **long** - Longitude coordinate
* **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
* **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors


### Through the OSEMiN framework, we will explore the dataset in an interative process.
<img src='https://github.com/learn-co-students/dsc-1-12-022-data-science-processes-online-ds-sp-000/blob/master/osemn.jpg'>

The framework portrays the entire project lifecycle that a data scientist should consider.

**O** - Obtain - This is the process of gathering the data and importing it as a dataframe for manipulation and analysis.

**S** - Scrub - The majority of a data scientist's job will be in scrubbing and exploring the data. clean data is essential for an accurate model.

**E** - Explore - As we explore each feature in the data, we should consider whether a feature is useful and make sure it is a normalized distribution before modeling.

**M** - Model - We create a model with predictive value.

**iN** - iNterpret - We should interpret the results and give a confidence interval.

### Model
A linear regression model was created that captured 88.6% of the variance in price.

