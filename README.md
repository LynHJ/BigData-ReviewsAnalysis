# BigData-ReviewsAnalysis


![](https://img.shields.io/badge/findspark-2.0.1-informational?style=plastic&logo=appveyor)
![](https://img.shields.io/badge/pyspark-3.3.1-informational?style=plastic&logo=appveyor)
![](https://img.shields.io/badge/pandas-1.3.5-informational?style=plastic&logo=appveyor)

![alt text]()


## Background



## ETL-AWS-COLAB
  

### Sub-Summary:

When I designed the first model, I was trying to simplify the data and apply a shallow deep learning model. For each non-numeric-data column, I categorized them into two categories, a category which has the highest count numbers and the other. After I had executed the whole process, I realized that the way I binned data might confuse the model as the organization did not simply use dichotomy to assess each applicant. 


## Vine Program Aanlysis


### Summary:



## Content:
```
Project
├── Image
│   ├──  kitchen_review_info.png
│   ├── kitchen_customers.png
│   ├── kitchen_products.png
│   ├── kitchen_vine_info.png
│   ├── tools_customers.png
│   ├── tools_products.png
│   ├── tools_review_info.png
│   └── tools_vine_info.png
├── README.md
├── requirements.txt
├── reviews_us_Kitchen.ipynb
├── reviews_us_Tools.ipynb
├── vine_analysis.ipynb
└── vine_schema.sql
```

## Prerequisites

1. A Colab account - Colab Notebooks  
2. An AWS account - S3 and RDS service  
*Remember to closely monitor any AWS resources that you choose to use. It’s crucial that you clean up and stop, or shut down any AWS resources to avoid accruing additional costs.  
3. S3 bucket permission setting:  
```
{
    "Version": "2012-10-17",  
    "Statement": [  
        {  
            "Sid": "getobject",  
            "Effect": "Allow",  
            "Principal": "*",  
            "Action": "s3:GetObject",  
            "Resource": "<bucket codes>/*"  
        }
    ]
}
```

## References
1. https://medium.com/geekculture/create-mysql-database-with-amazon-rds-4a6581e8dfaa














