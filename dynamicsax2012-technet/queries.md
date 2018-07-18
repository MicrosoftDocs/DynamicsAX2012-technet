---
title: Queries
TOCTitle: Queries
ms:assetid: 402865ee-7d2e-4f9e-ad06-1fd3507b3975
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496946(v=AX.60)
ms:contentKeyID: 36056714
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- queries
- query
audience: Application User
ms.search.region: Global
---

# Queries 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX **Sales and marketing**, you can create queries to view data for your company in different ways. The query functionality is common throughout Microsoft Dynamics AX. However, in **Sales and marketing**, you can also create queries that are based on workers, items, or the organization.

**Sales and marketing** provides both default data and default queries. You can import the default data but create your own queries, or you can enter your own data but use the default queries. The default values are located in the **Query administration** form. (Click **Sales and marketing** \> **Setup** \> **Sales management** \> **Query administration**.) To import default values so that you can use them in your queries, click **Create default data**. You can use the default data for both the default queries and the queries that you create yourself.

You can import default queries in the **Management statistics** form. (Click **Sales and marketing** \> **Periodic** \> **Sales management** \> **Management statistics**.) To import default queries, click **Functions**, and then select **Import default query**.

By creating queries in the management statistics section in **Sales and marketing**, you can view a plotted graph of both the fields and the methods of many tables in Microsoft Dynamics AX.

Before you can start to create queries in the management statistics section, your system administrator must use the **Query administration** form to enter the tables that you want to include in queries. You can then create queries, if you have the appropriate permissions.

To create a query by using the management statistics function, select the appropriate field or method and the return value in the **Queries** form.

  - You can enter the fields that your administrator has enabled on either the x-axis or the y-axis. However, the y-axis can contain only fields that contain real numbers, whereas the x-axis can contain any field that you select. By default, the name that is used for a field is the name in the Application Object Tree (AOT). However, you can change this name at any time.

  - You can enter the methods that your administrator has enabled only on the y-axis.

  - You can set the return value of the query so that it is displayed as a total, an average, or a count.

In the **Query administration** form, you can define the values for your calculations that are plotted on the x-axis. Click **Sales and marketing** \> **Setup** \> **Sales management** \> **Query administration**. Click **Allowed fields**.

In the **Allowed fields** form, you can select the fields that can be plotted only on the x-axis, only on the y-axis, or on both the x-axis and the y-axis.

Note - Fields that are plotted on the x-axis must be a form of data such as dates, customers and vendors, or employee names. Methods, such as revenue and quotations that have been won, can be plotted only on the y-axis.

  


