### PRODIGY_ML_01
#### TASK 1- LİNEAR REGRESSİON

![image](https://github.com/user-attachments/assets/e31a7f26-2839-4790-8196-98c5c1821905)

#### Project Description
In this project, a multiple linear regression model was applied to predict housing prices. The model uses key features such as the number of rooms, number of bathrooms, and square footage (living area).

The dataset is structured to distinguish between basement level and above-ground level features. In the initial phase, a model was built using only the above-ground level data. Later, features related to the basement were also included in the dataset and the model was retrained.

Comparative analysis showed that basement features have a significant impact on housing prices. This finding highlights the importance of including basement-related data when performing housing valuation and resulted in improved model performance.

###### First Model: Used only above-ground features:
"GrLivArea", "BedroomAbvGr", "FullBath", "HalfBath", and the target variable "SalePrice".

##### Second Model: Included both above-ground and basement features:
"GrLivArea", "BedroomAbvGr", "FullBath", "HalfBath", "TotalBsmtSF", "BsmtFullBath", "BsmtHalfBath", and "SalePrice".


#### What is Linear Regression?
Linear regression is a statistical technique used to model the relationship between a dependent variable and one or more independent variables using a linear equation.

##### 𝑦=𝑏0+𝑏1𝑥+𝜀

###### y : Dependent variable

###### x:  Independent variable

###### 𝑏0 : Intercept

###### 𝑏1 : Slope

###### ε : Error term

#### When is it Used?
* When there is a linear relationship between variables
* When you want to predict future values
* When you want to understand cause-effect relationships
* When data is limited but interpretability is important

#### Use Cases:
Economics: House price prediction

Healthcare: Relationship between age and blood pressure

Education: Exam score analysis

Marketing: Ad budget vs sales

#### Simple vs Multiple Regression:
Simple regression: One independent variable

Multiple regression: More than one independent variable


##### Dataset:
* SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict.
* MSSubClass: The building class
* MSZoning: The general zoning classification
* LotFrontage: Linear feet of street connected to property
* LotArea: Lot size in square feet
* Street: Type of road access
* Alley: Type of alley access
* LotShape: General shape of property
* LandContour: Flatness of the property
* Utilities: Type of utilities available
* LotConfig: Lot configuration
* LandSlope: Slope of property
* Neighborhood: Physical locations within Ames city limits
* Condition1: Proximity to main road or railroad
* Condition2: Proximity to main road or railroad (if a second is present)
* BldgType: Type of dwelling
* HouseStyle: Style of dwelling
* OverallQual: Overall material and finish quality
* OverallCond: Overall condition rating
* YearBuilt: Original construction date
* YearRemodAdd: Remodel date
* RoofStyle: Type of roof
* RoofMatl: Roof material
* Exterior1st: Exterior covering on house
* Exterior2nd: Exterior covering on house (if more than one material)
* MasVnrType: Masonry veneer type
* MasVnrArea: Masonry veneer area in square feet
* ExterQual: Exterior material quality
* ExterCond: Present condition of the material on the exterior
* Foundation: Type of foundation
* BsmtQual: Height of the basement
* BsmtCond: General condition of the basement
* BsmtExposure: Walkout or garden level basement walls
* BsmtFinType1: Quality of basement finished area
* BsmtFinSF1: Type 1 finished square feet
* BsmtFinType2: Quality of second finished area (if present)
* BsmtFinSF2: Type 2 finished square feet
* BsmtUnfSF: Unfinished square feet of basement area
* TotalBsmtSF: Total square feet of basement area
* Heating: Type of heating
* HeatingQC: Heating quality and condition
* CentralAir: Central air conditioning
* Electrical: Electrical system
* 1stFlrSF: First Floor square feet
* 2ndFlrSF: Second floor square feet
* LowQualFinSF: Low quality finished square feet (all floors)
* GrLivArea: Above grade (ground) living area square feet
* BsmtFullBath: Basement full bathrooms
* BsmtHalfBath: Basement half bathrooms
* FullBath: Full bathrooms above grade
* HalfBath: Half baths above grade
* Bedroom: Number of bedrooms above basement level
* Kitchen: Number of kitchens
* KitchenQual: Kitchen quality
* TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)
* Functional: Home functionality rating
* Fireplaces: Number of fireplaces
* FireplaceQu: Fireplace quality
* GarageType: Garage location
* GarageYrBlt: Year garage was built
* GarageFinish: Interior finish of the garage
* GarageCars: Size of garage in car capacity
* GarageArea: Size of garage in square feet
* GarageQual: Garage quality
* GarageCond: Garage condition
* PavedDrive: Paved driveway
* WoodDeckSF: Wood deck area in square feet
* OpenPorchSF: Open porch area in square feet
* EnclosedPorch: Enclosed porch area in square feet
* 3SsnPorch: Three season porch area in square feet
* ScreenPorch: Screen porch area in square feet
* PoolArea: Pool area in square feet
* PoolQC: Pool quality
* Fence: Fence quality
* MiscFeature: Miscellaneous feature not covered in other categories
* MiscVal: $Value of miscellaneous feature
* MoSold: Month Sold
* YrSold: Year Sold
* SaleType: Type of sale
* SaleCondition: Condition of sale

Dataset Link : https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data





































































