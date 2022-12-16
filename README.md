
### Get this product for $5

<i>Packt is having its biggest sale of the year. Get this eBook or any other book, video, or course that you like just for $5 each</i>


<b><p align='center'>[Buy now](https://packt.link/9781800562936)</p></b>


<b><p align='center'>[Buy similar titles for just $5](https://subscription.packtpub.com/search)</p></b>


# Cloud Scale Analytics with Azure Data Services

<a href="https://www.packtpub.com/product/cloud-scale-analytics-with-azure-data-services/9781800562936?utm_source=github&utm_medium=repository&utm_campaign=9781800562936"><img src="https://static.packt-cdn.com/products/9781800562936/cover/smaller" alt="Cloud Scale Analytics with Azure Data Services" height="256px" align="right"></a>

This is the code repository for [Cloud Scale Analytics with Azure Data Services](https://www.packtpub.com/product/cloud-scale-analytics-with-azure-data-services/9781800562936?utm_source=github&utm_medium=repository&utm_campaign=9781800562936), published by Packt.

**Build modern data warehouses on Microsoft Azure**

## What is this book about?
Azure Data Lake, the modern data warehouse architecture, and related data services on Azure enable organizations to build their own customized analytical platform to fit any analytical requirements in terms of volume, speed, and quality.

This book is your guide to learning all the features and capabilities of Azure data services for storing, processing, and analyzing data (structured, unstructured, and semi-structured) of any size. You will explore key techniques for ingesting and storing data and perform batch, streaming, and interactive analytics. The book also shows you how to overcome various challenges and complexities relating to productivity and scaling. Next, you will be able to develop and run massive data workloads to perform different actions. Using a cloud-based big data-modern data warehouse-analytics setup, you will also be able to build secure, scalable data estates for enterprises. Finally, you will not only learn how to develop a data warehouse but also understand how to create enterprise-grade security and auditing big data programs.

By the end of this Azure book, you will have learned how to develop a powerful and efficient analytical platform to meet enterprise needs.

This book covers the following exciting features: 
* Implement data governance with Azure services
* Use integrated monitoring in the Azure Portal and integrate Azure Data Lake Storage into the Azure Monitor
* Explore the serverless feature for ad-hoc data discovery, logical data warehousing, and data wrangling
* Implement networking with Synapse Analytics and Spark pools
* Create and run Spark jobs with Databricks clusters
* Implement streaming using Azure Functions, a serverless runtime environment on Azure
* Explore the predefined ML services in Azure and use them in your app

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1800562934) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```
SELECT
  t1.Cartype,
  SUM(t2.mgNOx/60) as SumNOx
FROM
  Cartraffic as t1 TIMESTAMPED BY ObservedT
JOIN
  CarStats as t2
ON
  t1.Cartype = t2.Cartype
GROUP BY
  t1.Cartype,
  TUMBLINGWINDOW(minute, 10)

```

**Following is what you need for this book:**
This book is for data architects, ETL developers, or anyone who wants to get well-versed in Azure data services to implement an analytical data estate for their enterprise. The book will also appeal to data scientists and data analysts who want to explore all the capabilities of Azure data services, which can be used to store, process, and analyze any kind of data. A beginner-level understanding of data analysis and streaming will be required. You will need a system with a good internet connection and an Azure account.

**Please note: all the services that you might use during the exercises of this book will cause cost within your Azure subscription. Try to always scale down the services where possible or even delete them after you have finished going through the exercises.**

With the following software and hardware list you can run all code files present in the book.

### Software and Hardware List

| Chapter  | Software required                                                                    | OS required                        |
| -------- | -------------------------------------------------------------------------------------| -----------------------------------|
| 3 - 14   |   Azure subscription                                                                 | Windows, Mac OS X, and Linux (Any) |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://static.packt-cdn.com/downloads/9781800562936_ColorImages.pdf).


### Related products <Other books you may enjoy>
* Azure Data Engineering Cookbook [[Packt]](https://www.packtpub.com/product/azure-data-engineering-cookbook/9781800206557?utm_source=github&utm_medium=repository&utm_campaign=9781800206557) [[Amazon]](https://www.amazon.com/dp/1800206550)

* Distributed Data Systems with Azure Databricks [[Packt]](https://www.packtpub.com/product/distributed-data-systems-with-azure-databricks/9781838647216?utm_source=github&utm_medium=repository&utm_campaign=9781838647216) [[Amazon]](https://www.amazon.com/dp/183864721X)

## Get to Know the Author
**Patrik Borosch** is a Cloud Solution Architect for Data and AI at Microsoft Switzerland GmbH. He has more than 25 years of BI and analytics development, engineering, and architecture experience and is a Microsoft Certified Data Engineer and a Microsoft Certified AI Engineer. Patrik has worked on numerous significant international Data Warehouses, Data Integration, and Big Data projects. There, he has built and extended his experience in all facets from requirement engineering over data modelling and ETL all the way to reporting and dashboarding. At Microsoft Switzerland, he supports customers in their journey into the analytical world of Azure Cloud.
  
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781800562936">https://packt.link/free-ebook/9781800562936 </a> </p>