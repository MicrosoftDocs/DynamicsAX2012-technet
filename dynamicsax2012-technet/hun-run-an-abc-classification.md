---
title: (HUN) Run an ABC classification
TOCTitle: (HUN) Run an ABC classification
ms:assetid: a9ed1818-1ed2-4c15-9b90-f67c8a1b3592
ms:mtpsurl: https://technet.microsoft.com/library/JJ664350(v=AX.60)
ms:contentKeyID: 49385438
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Run an ABC classification 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can group counted items on the **Inventory statement report** based on an ABC classification.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Inventory management** \> **Periodic** \> **ABC classification**.
    

    > [!NOTE]
    > <P>For more information, see "ABC classification (form)" in the Applications and Business Processes Help.</P>



2.  In the **From date** field, select the starting date for the grouping.

3.  In the **To date** field, select the ending date for the grouping.

4.  In the **Internal interest in %** field, enter the internal interest as a percentage.

5.  Select the category in the **A: Highest**, **B: Middle**, and **C: Lowest** fields.
    

    > [!NOTE]
    > <P>The sum of A+B+C must equal 100.</P>



6.  In the **ABC model** field, select the model based on how the counted items are grouped. The options are:
    
      - **Revenue** – Group items in the journal by revenue factor.
    
      - **Margin** – Group items in the journal by margin factor.
    
      - **Value** – Group items in the journal by value factor.
    
      - **Carrying cost** – Group items in the journal by carrying cost factor.

7.  Click **Select** to open the **Invent Table** form, and then select the criteria to use to group the items on the **Inventory statement** report.

8.  Click **OK** to close the **Invent Table** form.

9.  Click **OK** to run the ABC classification.

  


