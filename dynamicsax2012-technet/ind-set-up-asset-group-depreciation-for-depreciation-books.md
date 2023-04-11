---
title: (IND) Set up asset group depreciation for depreciation books
TOCTitle: (IND) Set up asset group depreciation for depreciation books
ms:assetid: 9ce7b204-d548-4b04-bd99-0ef59c624376
ms:mtpsurl: https://technet.microsoft.com/library/JJ664704(v=AX.60)
ms:contentKeyID: 49386035
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up asset group depreciation for depreciation books 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can use asset group depreciation for assets that are similar in nature and for those assets that have the same number of years of life. Asset group depreciation method is opposite to other methods of depreciation where assets are depreciated individually or where dissimilar assets are grouped together. You can use depreciation books for reporting asset information for tax and other non-financial reporting as opposed to value models which are used for accounting depreciation, tax depreciation, revaluation, and disposal.

You also can define the asset group depreciation for depreciation books by using the **Fixed asset group/depreciation book** form.

1.  Click **Fixed assets** \> **Setup** \> **Depreciation** \> **Depreciation books**.

2.  Create or select a depreciation book record.

3.  Click the **General** tab.

4.  Select the **Asset group depreciation** check box to calculate depreciation for a fixed asset group that is attached to the depreciation book.

5.  Select the **Allow net book value higher than the acquisition cost** check box and the **Allow negative net book value** check box, if required. The term net book value refers to the net book value of the whole fixed asset group.

6.  Click **Fixed asset groups** to open the **Fixed asset group/depreciation book** form.

7.  Press CTRL+N to create a new record. Select the fixed asset group to attach to the depreciation book in the **Fixed asset group** field.

8.  Select the **Asset group depreciation** check box to apply asset group depreciation for the fixed asset group.
    

    > [!NOTE]
    > <P>If this check box is selected for the depreciation book, the <STRONG>Asset group depreciation</STRONG> check box in the <STRONG>Depreciation books</STRONG> form is selected automatically for the fixed asset group that is attached to the depreciation book.</P>



## See also

[(IND) Asset depreciation book (modified form)](https://technet.microsoft.com/library/jj677835\(v=ax.60\))

[(IND) Depreciation books (modified form)](https://technet.microsoft.com/library/jj677965\(v=ax.60\))

  


