# AW-Internet-Sales
Este tutorial se basa en Adventure Works Cycles, una compañía ficticia. Adventure Works es una gran empresa multinacional de fabricación que produce y distribuye bicicletas, piezas y accesorios para mercados comerciales de Norteamérica, Europa y Asia. La empresa tiene 500 trabajadores. Además, Adventure Works emplea varios equipos de ventas regionales en su base comercial. Su proyecto es crear un modelo tabular para que los usuarios de ventas y marketing analicen los datos de la venta por Internet de la base de datos AdventureWorksDW.
# Adventure Works Internet Sales tutorial (1500)

This tutorial provides lessons on how to create and deploy a tabular model at the 1500 compatibility level. If you're new to Analysis Services and tabular modeling, completing this tutorial is the quickest way to learn how to create and deploy a basic tabular model by using Visual Studio with Analysis Services projects. Once you have the prerequisites in-place, it should take two to three hours to complete.

If you intend to deploy to SQL Server 2017 Analysis Services, you can still complete this tutorial. Select the 1400 compatibility level when creating a new project in Lesson 1.

What you learn
How to create a new tabular model project at the 1500 compatibility level in Visual Studio.

How to import data from a relational database into a tabular model project workspace database.

How to create and manage relationships between tables in the model.

How to create calculated columns, measures, and Key Performance Indicators that help users analyze critical business metrics.

How to create and manage perspectives and hierarchies that help users more easily browse model data by providing business and application-specific viewpoints.

How to create partitions that divide table data into smaller logical parts that can be processed independent from other partitions.

How to secure model objects and data by creating roles with user members.

How to deploy a tabular model by using Visual Studio.

Prerequisites
To complete lessons 1-12, you need:

An Azure subscription. If you don't already have a subscription, create a free account.

An Azure Synapse Analytics (SQL Data Warehouse) named AdventureWorksDW with the sample AdventureWorksDW database. If using a paid subscription, after completing this tutorial, you can pause or delete this resource in the portal to prevent unwanted charges.

The latest version of Visual Studio. Any edition, including the free Community edition work fine.

The latest Microsoft Analysis Services Projects (VSIX) package installed in Visual Studio.

Microsoft Excel.

To complete lesson 13 - Deploy, you need one of the following:

An Azure Analysis Services server (recommended). See create a server.

SQL Server 2019 Analysis Services server in Tabular mode. Download a free SQL Server 2019 Developer Edition.

Power BI Premium workspace assigned to a capacity with the Datasets workload XMLA Endpoint property set to read-write. To learn more, see Dataset connectivity with the XMLA endpoint.

Lessons in this tutorial do not use the following, but they're good to install for connecting to a deployed model.

SQL Server Management Studio (SSMS).

Power BI Desktop.

Scenario
This tutorial is based on Adventure Works Cycles, a fictitious company. Adventure Works is a large, multinational manufacturing company that produces and distributes bicycles, parts, and accessories for commercial markets in North America, Europe, and Asia. The company employs 500 workers. Additionally, Adventure Works employs several regional sales teams throughout its market base. Your project is to create a tabular model for sales and marketing users to analyze Internet sales data in the AdventureWorksDW database.

To complete the tutorial, you must complete various lessons. In each lesson, there are tasks. Completing each task in order is necessary for completing the lesson. While in a particular lesson there may be several tasks that accomplish a similar outcome, but how you complete each task is slightly different. This method shows there is often more than one way to complete a task, and to challenge you by using skills you've learned in previous lessons and tasks.

The purpose of the lessons is to guide you through authoring a basic tabular model by using many of the features included in Visual Studio with Analysis Services projects. Because each lesson builds upon the previous lesson, you should complete the lessons in order.

Lessons
This tutorial includes the following lessons:

LESSONS
Lesson	Estimated time to complete
1 - Create a new tabular model project	10 minutes
2 - Get data	10 minutes
3 - Mark as Date Table	3 minutes
4 - Create relationships	10 minutes
5 - Create calculated columns	15 minutes
6 - Create measures	30 minutes
7 - Create Key Performance Indicators (KPI)	10 minutes
8 - Create perspectives	5 minutes
9 - Create hierarchies	20 minutes
10 - Create partitions	15 minutes
11 - Create roles	15 minutes
12 - Analyze in Excel	5 minutes
13 - Deploy	5 minutes
Supplemental lessons
These lessons are not required to complete the tutorial, but can be helpful in better understanding advanced tabular model authoring features.

SUPPLEMENTAL LESSONS
Lesson	Estimated time to complete
Detail Rows	10 minutes
Dynamic security	30 minutes
Ragged hierarchies	20 minutes
Next steps
To get started, see Lesson 1: Create a new tabular model project.
