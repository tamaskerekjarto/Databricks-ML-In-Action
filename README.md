# Databricks ML in Action

<a href="https://www.packtpub.com/product/databricks-ml-in-action/9781800564893"><img src="https://content.packt.com/_/image/original/B16865/cover_image_large.jpg" alt="no-image" height="256px" align="right"></a>

This is the code repository for [Databricks ML in Action](https://github.com/PacktPublishing/Databricks-ML-In-Action), published by Packt.

**Learn how Databricks supports the entire ML lifecycle end to end from data ingestion to the model deployment**

## What is this book about?
Discover what makes the Databricks Data Intelligence Platform the go-to choice for top-tier machine learning solutions. Databricks ML in Action presents cloud-agnostic, end-to-end examples with hands-on illustrations of executing data science, machine learning, and generative AI projects on the Databricks Platform.

This book covers the following exciting features:
* Set up a workspace for a data team planning to perform data science
* Monitor data quality and detect drift
* Use autogenerated code for ML modeling and data exploration
* Operationalize ML with feature engineering client, AutoML, VectorSearch, Delta Live Tables, AutoLoader, and Workflows
* Integrate open-source and third-party applications, such as OpenAI’s ChatGPT, into your AI projects
* Communicate insights through Databricks SQL dashboards and Delta Sharing
* Explore data and models through the Databricks marketplace

If you feel this book is for you, get your [copy](https://www.amazon.com/Databricks-Lakehouse-Platform-practices-technical/dp/1800564899/ref=sr_1_1?crid=34I1H5XARUVL8&dib=eyJ2IjoiMSJ9.Go-xj3oJRxBPs8w9dtd1z5x4kAEbbckf5Xo9NIoZNeDGjHj071QN20LucGBJIEps.YWzvVP9t1Wc2K2EGMF1C06gRs5CM4ktvhahomit_49U&dib_tag=se&keywords=databricks+ml+in+action&qid=1715842156&sprefix=Databricks+ML+%2Caps%2C639&sr=8-1) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
import opendatasets as od

od.download("https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data",raw_data_path)

dbutils.fs.ls(raw_data_path + "/store-sales-time-series-forecasting/")

```

**Following is what you need for this book:**
This book is for machine learning engineers, data scientists, and technical managers seeking hands-on expertise in implementing and leveraging the Databricks Data Intelligence Platform and its Lakehouse architecture to create data products.
With the following software and hardware list you can run all code files present in the book (Chapter 2-10).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 2-10 | Databricks | Windows, macOS, or Linux |
| 2-10 | Python and its associated libraries |  Windows, macOS, or Linux |


### Related products
* Data Lakehouse in Action [[Packt]](https://www.packtpub.com/product/data-lakehouse-in-action/9781801815932) [[Amazon]](https://www.amazon.com/Data-Lakehouse-Action-Architecting-analytics/dp/1801815933/ref=tmm_pap_swatch_0?_encoding=UTF8&dib_tag=se&dib=eyJ2IjoiMSJ9.yz66rMtOCxguHwitp23lnhBtDs148VXyJ3cgH007q9TH7IGHLFU56Oa2rp57PfsdGCEB2-U_O4rZWheiVJQrujBTx6oCehsC7oWhBAkK8CJv54n04MwOj0o6SL8pfl5KZcF3aSJ4zPI_0yYFdLBbOPFXFzcvG7H4nLHBiuxR_jYwsun5uaWVxSVjfYxNjtaM.0jWHkHMCa3wTdwUbCi_bgMnYNBB82zifcqfcQb_765E&qid=1715847719&sr=8-1)

* Azure Databricks Cookbook [[Packt]](https://www.packtpub.com/product/azure-databricks-cookbook/9781789809718) [[Amazon]](https://www.amazon.com/Azure-Databricks-Cookbook-Jonathan-Wood/dp/1789809711/ref=sr_1_1?crid=DAO5N0478CL8&dib=eyJ2IjoiMSJ9.8Yj0ckOU2azgH43c9yfnPaJVaEt_P4K3gVUkWp2veRZRey1BsSdevxAdMVfmwbaUuaXSsiOTCLp5BjHJjELxGmob9QQhlnuNut-mOPNotN3JxYMzw7mXK99wwk0aWOANE7rTVl0GhSMb61dnUHAbmppLoXeNbIIb4HqS1z8LybNIzOveW_255SrKKd2NFaVvF9rw-7-49EWPZn_4eV8sLtLQIvo_bcUmhHudRYMutVk.Fukw3DVrduCUJJjOuHUvHGBxbpD29rhMJLotH-EyA4Q&dib_tag=se&keywords=Azure+Databricks+Cookbook&qid=1715847860&sprefix=azure+databricks+cookbook%2Caps%2C462&sr=8-1)
## Code Samples and Chapter Links

Each chapter folder contains code examples shared in the book using one of our data sources, and the links shared in the README file:

* [Chapter 1 - Getting Started](Chapter%201%3A%20Getting%20Started)
* [Chapter 2 - Designing Databricks Day One](Chapter%202%3A%20Designing%20Databricks%20Day%20One)
* [Chapter 3 - Building the Bronze Layer](Chapter%203%3A%20Building%20Our%20Bronze%20Layer)
* [Chapter 4 - Getting to Know Your Data](Chapter%204%3A%20Getting%20to%20Know%20Your%20Data)
* [Chapter 5 - Feature Engineering on the Lakehouse](Chapter%205%3A%20Feature%20Engineering%20on%20Databricks)
* [Chapter 6 - Tools for Model Training and Experimenting](Chapter%206%3A%20Tools%20for%20Model%20Training%20and%20Experimenting)
* [Chapter 7 - Productionizing Machine Learning](Chapter%207%3A%20Productionizing%20ML%20on%20Databricks)
* [Chapter 8 - Monitoring, Evaluating, and More](Chapter%208%3A%20Monitoring%2C%20Evaluating%2C%20and%20More) 

### What do you need to run the examples?

You will need a Databricks environment and permissions to run a cluster in order to follow along. There is a [Databricks community Edition](https://docs.databricks.com/en/getting-started/community-edition.html) that you can use to run the provided notebooks and code. However, we do use Unity Catalog which is available only on paid versions so some features will not work.


### Disclaimer

The authors will do its best to keep the code and examples provided as up-to-date as possible, but we understand that you may encounter outdated snippets or other issues. Please post your enquiries in the [issues page](https://github.com/PacktPublishing/Databricks-Lakehouse-ML-In-Action/issues) should you require further assistance.

## About the authors

[Stephanie Rivera](https://www.linkedin.com/in/stephanieamrivera/) has worked in big data and machine learning since 2011. She collaborates with teams and companies as they design their data intelligence platform as a Sr. Solutions Architect for Databricks.

Previously Stephanie was the VP, Data Intelligence for a global company, ingesting in 20+ terabytes of data daily. She led the data science, data engineering, and business intelligence teams.

Her data career has also included contributing to and leading a team in creating software that teaches people to explore fictional planets using data science algorithms. Stephanie authored numerous sections of Booz Allen Hamilton’s publication, The Field Guide to Data Science.

<i>I want to thank my loving partner, Rami Alba Lucio, Databricks coworkers, family, and friends for their unwavering support.</i>

[Mandy Baker](https://www.linkedin.com/in/amanda-baker-2b089831/) began her career in data 8 years ago. She loves leveraging her skills as a data scientist to orchestrate transformative journeys for companies across diverse industries as a Solutions Architect for Databricks. Her experiences have brought her from large corporations to small startups and everything in between. Mandy is a graduate of Carnegie Mellon University and the University of Washington.  

<i>Thank you to my partner Emmanuel, my parents, sisters, and friends for their enduring love and support. </i>

[Hayley Horn](https://www.linkedin.com/in/hayleyhorn/) started her data career 15 years ago as a data quality consultant on enterprise data integration projects. As a data scientist, she specialized in customer insights and strategy, and presented at Data Science and AI conferences in the US and Europe. She is currently a Sr. Solutions Architect for Databricks, with expertise in data science and technology modernization. 

A graduate of the MS Data Science program at Southern Methodist University in Dallas, Texas, USA, she is now a capstone advisor to students in their final semesters of the program.  

<i>I’d like to thank my husband, Kevin, and my sons Dyson and Dalton for their encouragement and enthusiastic support.</i>  

[Anastasia Prokaieva](https://www.linkedin.com/in/anastasiia-prokaieva/) began her career 9 years ago, as a research scientist at CEA (France), focusing on large data analysis and satellite data assimilation, treating terabytes of data. She has been working within the big data analysis and machine learning domain since then. In 2021, she joined Databricks and became the regional AI subject matter expert. <br>
On a daily basis, Anastasia consults Databricks users on best practices implementation of AI projects end-to-end, she delivers trainings, workshops to democratize AI. Anastasia holds two MSc degrees in theoretical physics and energy science.

<i>I would like to thank my partner, Julien, and my family for their tremendous support. My gratitude to my talented teammates all around the globe, as you inspire me every day!</i>


### Thanks for purchasing the book!

Hope you enjoy it!
