---
title: 'How to: Create a Date Dimension for a Cube'
TOCTitle: 'How to: Create a Date Dimension for a Cube'
ms:assetid: 81508890-2f55-40d4-9894-53118a598f1d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg724055(v=AX.60)
ms:contentKeyID: 35133412
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# How to: Create a Date Dimension for a Cube 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX provides a default calendar definition called the Date dimension. You can modify this calendar definition, but changes you make to the Date dimension will affect all cubes that use the Date dimension. Instead you may want to create a new date dimension.

### To create a date dimension

1.  Open the **Date dimensions** form. For more information, see [Date dimensions (form)](https://technet.microsoft.com/en-us/library/hh580649\(v=ax.60\)).

2.  Click **New**.

3.  In the **Calendar properties** pane, type a name and label for the calendar.

4.  Specify calendar properties.

5.  Click **Hierarchies**. Select the date dimension hierarchies to include.

6.  Click **Close**.

### To add the new date dimension to an Analysis Services project

1.  Click **Tools** \> **Business Intelligence (BI) tools** \> **Analysis Services project wizard**.

2.  Click **Next**. Click **Update** and then click **Next** again.

3.  Select the project to which you want to add a Date dimension and then click **Next**. After the Analysis Services project is verified, click **Next** again.

4.  Select the perspectives that correspond to the cubes to which you want to add a date dimension.

5.  Click **Next** two times.

6.  Select the dimension you created and move it to the **Selected** pane.

7.  Complete the **Analysis Services project wizard**. For more information, see [Working with Analysis Services Projects](working-with-analysis-services-projects.md).

You cannot remove a date dimension by using the **Analysis Services project wizard**. You must delete it by using Microsoft SQL Server Business Intelligence Development Studio (BIDS).

  


