# Customer-Analytics
## Mini Project about Customer Analysis

> **Segmentation data**

`#ID`  `numerical`  : Shows  a unique identificator of a customer.

`Sex`  `category`   : Biological sex (gender) of a customer. In this dataset there are only 2 different options. 
- **0 - male** 
- **1 - female**

`Marital status` `category` : Marital status of a customer.
+ **0 - single**
+ **1 - non-single (divorced / separated / married / widowed)**


`Age` `numerical`  :The age of the customer in years, calculated as current year minus the year of birth of the customer at the time of creation of the dataset
* **18 - Min value (the lowest age observed in the dataset)**
* **76 - Max value (the highest age observed in the dataset)**

`Education` `categorical` : Level of education of the customer
* **0 - other / unknown**
* **1	- high school**
* **2	- university**
* **3	- graduate school**

`Income`	`numerical` : Self-reported annual income in US dollars of the customer.
* **35832	- Min value (the lowest income observed in the dataset)**
* **309364	- Max value (the highest income observed in the dataset)**

`Occupation`	`categorical` :		Category of occupation of the customer.
* **0	- unemployed / unskilled**
*  **1 - skilled employee / official**
*  **2	- management / self-employed / highly qualified employee / officer**

`Settlement size`	`categorical` : The size of the city that the customer lives in.
* **0 - small city**
* **1 - mid-sized city**
* **2 - big city**

> **Purchase data**

_The dataset consists of information about the purchases of chocolate candy bars of 500 individuals from a given area when entering a physical ‘FMCG’ store in the period of 2 years. All data has been collected through the loyalty cards they use at checkout. The data has been preprocessed and there are no missing values. In addition, the volume of the dataset has been restricted and anonymised to protect the privacy of the customers._

`#ID`  `numerical`  : Shows  a unique identificator of a customer.

`Day`	`numerical` : 	Day when the customer has visited the store 

`Incidence`	`categorical` : 	Purchase Incidence
* **0 - The customer has not purchased an item from the category of interest**
*  **1 - The customer has purchased an item from the category of interest**

`Brand` `categorical` : Shows which brand the customer has purchased
* **0 - No brand was purchased**
* **1,2,3,4,5 - Brand ID**

`Quantity` `numerical` : 	Number of items bought by the customer from the product category of interest

`Last_Inc_Brand` `categorical` : Shows which brand the customer has purchased on their previous store visit
* **0 - No brand was purchased**
* **1,2,3,4,5 - Brand ID**

`Last_Inc_Quantity` `numerical` : Number of items bought by the customer from the product category of interest during their previous store visit

`Price_1` `numerical` :Price of an item from Brand 1 on a particular day

`Price_2` `numerical` :Price of an item from Brand 2 on a particular day

`Price_3` `numerical` :Price of an item from Brand 3 on a particular day

`Price_4` `numerical` :Price of an item from Brand 4 on a particular day

`Price_5` `numerical` :Price of an item from Brand 5 on a particular day

`Promotion_1` `categorical` :Indicator whether Brand 1 was on promotion or not on a particular day
* **0 - There is no promotion**
* **1 - There is promotion**

`Promotion_2` `categorical` :Indicator whether Brand 2 was on promotion or not on a particular day
* **0 - There is no promotion**
* **1 - There is promotion**

`Promotion_3` `categorical` :Indicator whether Brand 3 was on promotion or not on a particular day
* **0 - There is no promotion**
* **1 - There is promotion**

`Promotion_4` `categorical` :Indicator whether Brand 4 was on promotion or not on a particular day
* **0 - There is no promotion**
* **1 - There is promotion**

`Promotion_5` `categorical` :Indicator whether Brand 5 was on promotion or not on a particular day
* **0 - There is no promotion**
* **1 - There is promotion**

`Sex`  `category`   : Biological sex (gender) of a customer. In this dataset there are only 2 different options. 
- **0 - male** 
- **1 - female**

`Marital status` `category` : Marital status of a customer.
+ **0 - single**
+ **1 - non-single (divorced / separated / married / widowed)**


`Age` `numerical`  :The age of the customer in years, calculated as current year minus the year of birth of the customer at the time of creation of the dataset
* **18 - Min value (the lowest age observed in the dataset)**
* **75 - Max value (the highest age observed in the dataset)**

`Education` `categorical` : Level of education of the customer
* **0 - other / unknown**
* **1	- high school**
* **2	- university**
* **3	- graduate school**

`Income`	`numerical` : Self-reported annual income in US dollars of the customer.
* **38247	- Min value (the lowest income observed in the dataset)**
* **309364	- Max value (the highest income observed in the dataset)**

`Occupation`	`categorical` :		Category of occupation of the customer.
* **0	- unemployed / unskilled**
*  **1 - skilled employee / official**
*  **2	- management / self-employed / highly qualified employee / officer**

`Settlement size`	`categorical` : The size of the city that the customer lives in.
* **0 - small city**
* **1 - mid-sized city**
* **2 - big city**
