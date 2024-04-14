# Car_Insurance_Classification
  =========================================
## About :
    This is a dataset from one bank in the United States. Besides usual services, this bank also provides car insurance services. The bank organizes regular campaigns to attract new clients. The bank has potential customers’ data, and bank’s employees call them for advertising available car insurance options. We are provided with general information about clients (age, job, etc.) as well as more specific information about the current insurance sell campaign (communication, last contact day) and previous campaigns (attributes like previous attempts, outcome). 
## Context:

    > The task is to predict for 1000 customers who were contacted during the current campaign, whether they will buy car insurance or not.
## Content:

> The data contains the following information:

      * Id : Unique ID number. Predictions file should contain this feature.
      * Age :Age of the client
      * Job : Job of the client. : "admin.", "blue-collar", etc.
      * Marital : Marital status of the client : "divorced", "married", "single"
      * Education : Education level of the client : "primary", "secondary", etc.
      * Default : Has credit in default? : "yes" - 1,"no" - 0
      * Balance : Average yearly balance, in USD
      * HHInsurance : Is household insured : "yes" - 1,"no" - 0
      * CarLoan : Has the client a car loan : "yes" - 1,"no" - 0
      * Communication : Contact communication type "cellular", "telephone", “NA”
      * LastContactMonth: Month of the last contact "jan", "feb", etc.
      * LastContactDay : Day of the last contact
      * CallStart :Start time of the last call (HH:MM:SS) 12:43:15
      * CallEnd : End time of the last call (HH:MM:SS) 12:43:15
      * NoOfContacts : Number of contacts performed during this campaign for this client
      * DaysPassed : Number of days that passed by after the client was last contacted from a previous campaign (numeric; -1 means client was not previously 
        contacted)
      * PrevAttempts : Number of contacts performed before this campaign and for this client
      * Outcome : Outcome of the previous marketing campaign : "failure", "other", "success", “NA”
      * CarInsurance : Has the client subscribed a CarInsurance? :"yes" - 1,"no" - 0

# Shipping_classification
 =====================================

## Context:
    An international e-commerce company based wants to discover key insights from their customer database. They want to use some of the most advanced machine learning techniques to study their customers. The company sells electronic products.

## Content:

> The dataset used for model building contained 10999 observations of 12 variables.
> The data contains the following information:

    * ID: ID Number of Customers.
    * Warehouse block: The Company have big Warehouse which is divided in to block such as A,B,C,D,E.
    * Mode of shipment:The Company Ships the products in multiple way such as Ship, Flight and Road.
    * Customer care calls: The number of calls made from enquiry for enquiry of the shipment.
    * Customer rating: The company has rated from every customer. 1 is the lowest (Worst), 5 is the highest (Best).
    * Cost of the product: Cost of the Product in US Dollars.
    * Prior purchases: The Number of Prior Purchase.
    * Product importance: The company has categorized the product in the various parameter such as low, medium, high.
    * Gender: Male and Female.
    * Discount offered: Discount offered on that specific product.
    * Weight in gms: It is the weight in grams.
    * Reached on time: It is the target variable, where 1 Indicates that the product has NOT reached on time and 0 indicates it has reached on time.


# Water Quality Dataset
=================================
> This dataset contains information about water quality features and potability. It consists of 3276 entries with 10 columns:

      * pH: pH of the water (measured in pH units).
      * Hardness: Hardness of the water (measured in mg/L).
      * Solids: Total dissolved solids in the water (measured in ppm).
      * Chloramines: Amount of chloramines in the water (measured in ppm).
      * Sulfate: Amount of sulfate in the water (measured in mg/L).
      * Conductivity: Conductivity of the water (measured in μS/cm).
      * Organic_carbon: Amount of organic carbon in the water (measured in ppm).
      * Trihalomethanes: Amount of trihalomethanes in the water (measured in μg/L).
      * Turbidity: Turbidity of the water (measured in NTU).
      * Potability: Potability of the water (1 indicates potable, 0 indicates non-potable).
> Summary Statistics:

     * The dataset contains 3276 entries.
     * The columns "pH", "Sulfate", and "Trihalomethanes" have missing values.
     * The data types of the columns are float64 for features and int64 for the target variable (Potability).
> Usage:

    * This dataset can be used for various tasks, including:
         1. Exploratory data analysis (EDA) to understand the distributions and relationships between features.
         2. Predictive modeling to predict water potability based on its features.
         3. Feature engineering to create new features or handle missing values.
         4.  Model evaluation to assess the performance of machine learning models in predicting water potability.
