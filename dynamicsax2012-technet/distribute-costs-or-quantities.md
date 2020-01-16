---
title: Distribute costs or quantities
TOCTitle: Distribute costs or quantities
ms:assetid: b0a5b3c6-c288-41df-a059-2ec6939f3a49
ms:mtpsurl: https://technet.microsoft.com/library/Aa498641(v=AX.60)
ms:contentKeyID: 36058964
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Distribute costs or quantities 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You use distributions to distribute posted cost amounts or service quantities to other dimensions. The posted cost amounts or service quantities might or might not have a dimension. The distribution is performed on the same cost category as the original posting.

Before you can distribute costs or quantities, you must create a calculation version.

1.  Click **Cost accounting** \> **Setup** \> **Calculation** \> **Calculation versions**.

2.  Select a calculation version, and then click **Cost distribution**.
    

    > [!NOTE]
    > <P>To distribute the posted service quantities, click <STRONG>Service distribution</STRONG>.</P>



3.  In the **Cost line** form, on the **Overview** tab, press CTRL+N to create a new line.

4.  In the **Distribution level** field, select a distribution level. If you select **Cost line**, specify the distribution structure.

5.  In the **Distribution reference** field, select either a cost category or a cost line, depending on the distribution level.

6.  In the **Calculation method** field, select a calculation method.
    
    The calculation method that you select determines how distributions are calculated. You can select from the following methods of calculation:
    
      - **Fixed percentage** – Posted amounts are distributed to other dimensions according to the selections that you made on the **Dimension** tab.
    
      - **Cost category** – Posted amounts are distributed to the dimensions that are posted on the cost category in this field, and they are distributed in the posted proportion. When you use this calculation method, it is appropriate to select all dimensions on the **Dimension** tab.
    
      - **Service category** – Posted amounts are distributed to the dimensions that are posted on the service category in this field, and they are distributed in the posted proportion. When you use this calculation method, it is appropriate to select all dimensions on the **Dimension** tab.
    
      - **Cost line** – Posted amounts are distributed to the dimensions that are posted on the cost line in this field, and they are distributed in the posted proportion. When you use this calculation method, it is appropriate to select all dimensions on the **Dimension** tab.
    
      - **Reference table** – Posted amounts are distributed to other dimensions in the proportion that is set up on the selected reference table. The dimensions of the reference table are automatically updated on the **Dimension** tab.
    
      - **Reference specification** – Posted amounts are distributed to other dimensions according to the selected reference quantity, and they are distributed in the proportion that is specified on the **Dimension** tab.
    
      - **Fixed amount** – On the **Dimension** tab, a specified amount is distributed to the dimension.

7.  On the **General** tab, select the appropriate check boxes under **Cost share** and **Offset transaction dimension**.

8.  Specify the calculation method by using the fields under **Offset transaction calculation**.

9.  Click the **Dimension** tab, and then enter the dimensions.


> [!NOTE]
> <P>The cost distributions and service distributions are calculated in the manner shown on the <STRONG>Overview</STRONG> tab in the <STRONG>Cost distribution</STRONG> or <STRONG>Service distribution</STRONG> form. The finishing order of the calculations is necessary for the result. You can change the order by using the <STRONG>Up</STRONG> and <STRONG>Down</STRONG> buttons.</P>


  


