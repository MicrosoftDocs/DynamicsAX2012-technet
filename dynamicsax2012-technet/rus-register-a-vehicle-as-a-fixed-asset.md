---
title: (RUS) Register a vehicle as a fixed asset
TOCTitle: (RUS) Register a vehicle as a fixed asset
ms:assetid: 95d5ea6e-d8d0-4fd8-87c6-616e9c64f9c4
ms:mtpsurl: https://technet.microsoft.com/library/JJ678505(v=AX.60)
ms:contentKeyID: 49387734
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- transport
- fixed asset
- vehicle
audience: Application User
ms.search.region: Russia
---

# (RUS) Register a vehicle as a fixed asset 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you put a vehicle fixed asset to use and calculate depreciation, you must register the fixed asset of type **Vehicle** in the assessed tax registers. After you register the fixed asset, you must then select the appropriate sales tax code, tax exemption, and value model information to register the fixed asset in the tax register. You can use the **Fixed assets** form to register a fixed asset of type **Vehicle**, and to select appropriate sales tax and value model information.

Use the following procedures to register a vehicle as a fixed asset, and then enter tax registration information for the registered vehicle:

## Register the vehicle fixed asset

1.  Click **Fixed assets (Russia)** \> **Common** \> **Fixed assets**.

2.  Create a line to register the fixed asset, and then enter the required details.

3.  Click the **General** tab, and then in the **Type** field, select **Vehicle**.

4.  Click the **Technical information** tab, and then in the **Vehicle type** and **Model** fields, select the identification for the vehicle type and vehicle model.

5.  In the **Registration number** field, enter the registration number for the vehicle.

6.  In the **Date of the registration** field, select the registration date for the vehicle.
    

    > [!NOTE]
    > <P>You must specify the registration date for the fixed asset, if you selected <STRONG>Date of the registration</STRONG> in the <STRONG>Depreciation start date</STRONG> field in the <STRONG>Depreciation groups</STRONG> form; otherwise, depreciation transactions are not created. If you modify the registration date, the depreciation starting date is updated.</P>



7.  In the **Removal from the register date** field, select the date when the realty is scheduled to be removed from the tax register.
    

    > [!NOTE]
    > <P>The <STRONG>Date of the registration</STRONG> and <STRONG>Removal from the register date</STRONG> fields are available only if you selected <STRONG>Realty</STRONG> or <STRONG>Vehicle</STRONG> in the <STRONG>Type</STRONG> field on the <STRONG>General</STRONG> tab.</P>



## Enter the tax registration information for the vehicle fixed asset

1.  In the **Fixed assets** form, click the **Tax reporting** tab.

2.  Under the **Assessed tax** field group, in the **Asset kind** field, select the asset type.

3.  In the **Sales tax code** and **Exemption from tax** fields, select the sales tax code for the assessed tax, and the tax benefit code for the transport tax.
    

    > [!NOTE]
    > <P>The <STRONG>Sales tax code</STRONG> field is available only if you selected <STRONG>1</STRONG> or <STRONG>3</STRONG> in the <STRONG>Asset kind</STRONG> field.</P>



4.  Under the **Transport tax** field group, in the **Sales tax code** field, select the sales tax code for the transport tax.
    

    > [!NOTE]
    > <P>The fields under the <STRONG>Transport tax</STRONG> field group are available only if you selected <STRONG>Vehicle</STRONG> in the <STRONG>Type</STRONG> field on the <STRONG>General</STRONG> tab.</P>



5.  In the **Tax base** field, enter the tax base amount of fixed asset, which is based on the engine power (horsepower or kilowatt), jet traction (kilogram-force or kg F), gross tonnage (tons), or other technical characteristics.

6.  In the **Transport tax** and **Unit** fields, select the tax benefit code for the transport tax and the measurement unit for the tax base.

7.  Click **Value models** to open the **FA value models** form.

8.  Create a value model, and then enter the required details.

9.  In the **Depreciation group** field, select the depreciation group within the value model that the fixed asset belongs to.

## See also

[(RUS) Set up the depreciation starting date for vehicles and realty](rus-set-up-the-depreciation-starting-date-for-vehicles-and-realty.md)

[(RUS) Depreciate a fixed asset by using a fixed asset journal](rus-depreciate-a-fixed-asset-by-using-a-fixed-asset-journal.md)

  


