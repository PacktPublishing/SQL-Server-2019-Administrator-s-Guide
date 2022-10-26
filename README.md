# SQL Server 2019 Administrator's Guide

<a href="https://www.packtpub.com/product/sql-server-2019-administrator-s-guide-second-edition/9781789954326"><img src="https://static.packt-cdn.com/products/9781789954326/cover/smaller" alt="SQL Server 2019 Administrator's Guide" height="256px" align="right"></a>

This is the code repository for [SQL Server 2019 Administrator's Guide](https://www.packtpub.com/product/sql-server-2019-administrator-s-guide-second-edition/9781789954326), published by Packt.

**A definitive guide for DBAs to implement, monitor, and maintain enterprise database solutions**

## What is this book about?
SQL Server is one of the most popular relational database management systems developed by Microsoft. This second edition of the SQL Server Administrator's Guide will not only teach you how to administer an enterprise database, but also help you become proficient at managing and keeping the database available, secure, and stable.

This book covers the following exciting features: 

* Discover SQL Server 2019’s new features and how to implement them
* Fix performance issues by optimizing queries and making use of indexes
* Design and use an optimal database management strategy
* Combine SQL Server 2019 with Azure and manage your solution using various automation techniques
* Implement efficient backup and recovery techniques in line with security policies

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1789954320) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
use [AdventureWorks] 
exec sp_replicationdboption @dbname = N'AdventureWorks',    
     @optname = N'publish',   
     @value = N'true' GO
```

**Following is what you need for this book:**
This book is for database administrators, database developers, and anyone who wants to administer large and multiple databases single-handedly using Microsoft's SQL Server 2019. Basic awareness of database concepts and experience with previous SQL Server versions is required.

With the following software and hardware list you can run all code files present in the book (Chapter 1-15).

### Software and Hardware List

| Chapter  | Software required                   | OS required                        |
| -------- | ------------------------------------| -----------------------------------|
| 1        | SQL Server 2019                    | Windows, Mac OS X, and Linux (Any) |


We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://static.packt-cdn.com/downloads/9781789954326_ColorImages.pdf).

### Related products 
* Introducing Microsoft SQL Server 2019 [[Packt]](https://www.packtpub.com/product/introducing-microsoft-sql-server-2019/9781838826215) [[Amazon]](https://www.amazon.com/dp/1838826211)
* Mastering Azure Machine Learning [[Packt]](https://www.packtpub.com/product/mastering-azure-machine-learning/9781789807554) [[Amazon]](https://www.amazon.com/dp/1789807557)

## Get to Know the Authors
**Marek Chmel**
is a senior cloud solutions architect at Microsoft for data and artificial intelligence, a speaker, and a trainer with more than 15 years' experience. He's a frequent conference speaker, focusing on SQL Server, Azure, and security topics. He has been a Data Platform MVP since 2012. He has earned numerous certifications, including MCSE: Data Management and Analytics, Azure Architect, Data Engineer and Data Scientist Associate, EC Council Certified Ethical Hacker, and several eLearnSecurity certifications. Marek earned his MSc degree in Business and Informatics from Nottingham Trent University. He started his career as a trainer for Microsoft courses and later worked as principal sharepoint administrator and principal database administrator.

**Vladimír Mužný**
has been a freelance developer and consultant since 1997. He has been a Data Platform MVP since 2017, and he has earned certifications such as MCSE: Data Management and Analytics and MCT. His first steps with SQL Server were done on version 6.5, and from that time on, he has worked with all following versions of SQL Server. Now Vladimir teaches Microsoft database courses, participates in SQL Server adoption at various companies, and collaborates on projects for production tracking and migrations.


## Other books by the authors
* [Hands-On Data Science with SQL Server 2017](https://www.packtpub.com/product/hands-on-data-science-with-sql-server-2017/9781788996341)
* [SQL Server 2017 Administrator's Guide](https://www.packtpub.com/product/sql-server-2017-administrator-s-guide/9781786462541)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSdy7dATC6QmEL81FIUuymZ0Wy9vH1jHkvpY57OiMeKGqib_Ow/viewform) if you have any feedback or suggestions.

### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781789954326">https://packt.link/free-ebook/9781789954326 </a> </p>