---
title: (IND) Set up parameters to define a depreciation threshold
TOCTitle: (IND) Set up parameters to define a depreciation threshold
ms:assetid: 08830920-1a85-4dad-97b3-cd4b8c3c5978
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664457(v=AX.60)
ms:contentKeyID: 49385536
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up parameters to define a depreciation threshold 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up parameters to define the depreciation threshold and determine the percentage of depreciation on a fixed asset. If a fixed asset was purchased and used for fewer than 180 days during the previous financial year, only 50 percent of the rate of depreciation is calculated for the asset. For example, if the rate of depreciation is 10 percent, only 5 percent depreciation is calculated on the asset.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Fixed assets** \> **Setup** \> **Fixed assets parameters**.

2.  Select the **Income tax Act depreciation** check box.

3.  Enter the threshold number of days up to which proportionate depreciation can be applied on a fixed asset in the **Asset group depreciation threshold** field.
    

    > [!NOTE]
    > <P>Normal depreciation will be applied for a fixed asset that is used for a period that exceeds or is equal to the threshold period.</P>



4.  Enter the proportionate percentage that must be applied on a fixed asset that is used for a period that is less than or equal to the threshold in the **Depreciation threshold percentage** field.
    

    > [!NOTE]
    > <P>The depreciation threshold percentage will be applied to the normal depreciation percentage of the fixed asset only if the fixed asset has been put to use for less than or equal to the number of days defined in the <STRONG>Asset group depreciation threshold</STRONG> field in the year of purchase.</P>



5.  Press CTRL+S or close the form.

## See also

[(IND) General ledger parameters (modified form)](https://technet.microsoft.com/en-us/library/jj677901\(v=ax.60\))

  


