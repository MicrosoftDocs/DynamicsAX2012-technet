---
title: (RUS) Register realty as a fixed asset
TOCTitle: (RUS) Register realty as a fixed asset
ms:assetid: be56e27a-2063-4d61-8030-eb89311f1b08
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711568(v=AX.60)
ms:contentKeyID: 49387892
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Register realty as a fixed asset 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you put a realty fixed asset into use and calculate depreciation, you need to register the fixed asset in the assessed tax registers. Use the **Fixed assets** form to register a fixed asset of the **Realty** type.

1.  Click **Fixed assets (Russia)** \> **Common** \> **Fixed assets**.

2.  Click **Fixed asset** to create a fixed asset, and then enter the required details. For more information, see [(RUS) Create fixed assets](rus-create-fixed-assets.md).

3.  On the **General** FastTab, in the **Type** field, select **Realty**.

4.  Click the **Technical information** FastTab, and then, in the **Date of the registration** field, select the registration date for the fixed asset.
    

    > [!NOTE]
    > <P>If you selected <STRONG>Date of the registration</STRONG> in the <STRONG>Depreciation start date</STRONG> field in the <STRONG>Depreciation groups</STRONG> form, you must specify the registration date for the fixed asset. Otherwise, the depreciation transactions are not created. If you modify the registration date, the starting date for depreciation is updated.</P>



5.  In the **Removal from the register date** field, select the date when the asset is scheduled for removal from the tax register.
    

    > [!NOTE]
    > <P>The <STRONG>Date of the registration</STRONG> and <STRONG>Removal from the register date</STRONG> fields are available only if you selected <STRONG>Realty</STRONG> or <STRONG>Vehicle</STRONG> in the <STRONG>Type</STRONG> field on the <STRONG>General</STRONG> tab.</P>



6.  Click the **Tax reporting** FastTab.

7.  In the **Assessed tax** field group, in the **Asset kind** field, select the type of asset.
    

    > [!NOTE]
    > <P>The <STRONG>Assessed tax</STRONG> field group is not available if you selected <STRONG>Vehicle</STRONG> or <STRONG>Ground area</STRONG> in the <STRONG>Type</STRONG> field on the <STRONG>General</STRONG> FastTab.</P>



8.  In the **Sales tax code** and **Exemption from tax** fields, select the sales tax code for the assessed tax and the tax benefit code for the transport tax.
    

    > [!NOTE]
    > <P>The <STRONG>Sales tax code</STRONG> field is available only if you selected <STRONG>1</STRONG> or <STRONG>3</STRONG> in the <STRONG>Asset kind</STRONG> field.</P>



## See also

[(RUS) Register a vehicle as a fixed asset](rus-register-a-vehicle-as-a-fixed-asset.md)

  


