# Quality Control Categorization
To Create a Quality Categorization of different products based on its Doorstep Rejection,Repairs,Replacements etc...
The Categorization is as follows:

A+ Category - The products under this category has the highest quality standard and requires only source inspection and is delivered directly to Customer(tend to get least issues)

A Category - The Products under this category requires source inspection and 10% of the skus are checked in the inbound warehouse

B Category - The Products under this category requires source inspection and 50% of the skus are checked in the inbound warehouse

C Category - The Products under this category requires source inspection and 100% of the skus are checked in the inbound warehouse(tend to get highest issues)

The Categories of the products changes time to time based on the number of rejections,replacements,repairs etc..

We have automated this using python code and made a model using **Decision Tree Classifer** which gave me an accuracy of 99.6%

**RESULT**

![image](https://github.com/sorunair/QC-Categorization/assets/167282796/924023da-c814-4352-a8d0-c6eafcbf4322)


**CONFUSION MATRIX**

![image](https://github.com/sorunair/QC-Categorization/assets/167282796/932c4e4a-5ce3-412c-980c-fbe2c04c33e5)
