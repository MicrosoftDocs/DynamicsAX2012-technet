---
title: Set up fixed asset groups
TOCTitle: Set up fixed asset groups
ms:assetid: 7ee1a476-08af-48d1-8057-861ea5d1e43b
ms:mtpsurl: https://technet.microsoft.com/library/Aa571539(v=AX.60)
ms:contentKeyID: 36058325
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up fixed asset groups 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Fixed asset groups simplify the setup of fixed assets. These groups also help classify information for reporting and decision-making about assets.

1.  Click **Fixed assets** \> **Setup** \> **Fixed asset groups**.

2.  Click **New** to create a fixed asset group. Enter a unique identifier and name.

3.  Click **Value models** and create the value models that will apply to all the fixed assets that are assigned to the fixed asset group.
    

    > [!NOTE]
    > <P>You must enter a value in the <STRONG>Fixed asset group</STRONG> field when you create a fixed asset. Default values for other fields for the fixed asset are inherited from the fixed asset group. These include the value model and its posting layers and depreciation profiles. In the <STRONG>Fixed asset group/value model</STRONG> form, you can view the posting layer of the value model that is created for the fixed asset group.</P>



4.  Close the **Fixed asset group/value model** form.

5.  Click **Depreciation books** and create the depreciation books that will apply to all fixed assets that are assigned to the fixed asset group.

6.  On the **General** tab in the **Fixed asset groups** form, select values in the **Number sequence code** fields, as necessary.
    
      - If you set up number sequences for the automatic numbering of fixed assets, select the **Autonumber fixed assets** check box, and select the number sequence for the fixed asset group in the **Number sequence code** field.
    
      - If you set up number sequences for the automatic numbering of bar codes, select the **Autonumber bar codes** check box, and select the number sequence for bar codes in the **Bar code number sequence** field.


> [!TIP]
> <P>If the system is set up to post acquisition transactions from Accounts payable, you can set up a capitalization threshold so that assets are depreciated by default if they meet a minimum acquisition amount, and if they were acquired from an Accounts payable invoice. For more information, see <A href="about-assets-acquired-through-procurement.md">About assets acquired through procurement</A>.</P>



## See also

[Basic setup of Fixed assets](basic-setup-of-fixed-assets.md)

[Set up number sequences for Fixed assets](set-up-number-sequences-for-fixed-assets.md)

[Set up value models](set-up-value-models.md)

[Set up asset depreciation books](set-up-asset-depreciation-books.md)

  


