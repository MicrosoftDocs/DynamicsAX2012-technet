---
title: (IND) Set up withholding tax components for TDS tax types
TOCTitle: (IND) Set up withholding tax components for TDS tax types
ms:assetid: 8890a0fa-6987-4dbc-931c-5bcd4df0fab8
ms:mtpsurl: https://technet.microsoft.com/library/JJ678021(v=AX.60)
ms:contentKeyID: 49385982
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up withholding tax components for TDS tax types 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You must set up withholding tax components for the Tax Deducted at Source (TDS) tax type and define the threshold to calculate TDS for each TDS component. The different TDS components are TDS, surcharge, E-cess, and SHE Cess. You also can define an exception threshold to calculate TDS for each TDS component.

## Set up the withholding tax components

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **India** \> **Withholding tax components**.

2.  Select **TDS** in the **Tax type** field.

3.  Press CTRL+N to create a new line.

4.  Enter the TDS component name in the **Withholding tax component** field and a description in the **Description** field.

5.  In the **Withholding tax component group** field, select the TDS withholding tax component group to attach the TDS component to.

## Define the threshold limit

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **India** \> **Withholding tax components**. Click **Threshold**.

2.  Select the period range that the threshold limit is applied for in the date fields.

3.  Enter the threshold amount limit to calculate TDS for the TDS component in the **Threshold** field. The tax is deducted at source only when the cumulative invoice amount has crossed the threshold limit.
    
    For example, if the threshold limit is 10000, the TDS is calculated after the cumulative invoice amount is 10001 or above.

4.  Enter the exception threshold amount limit in the **Exception threshold** field. The tax is deducted at source on an invoice line if the amount has crossed the exception threshold limit.
    
    For example, if the exception threshold limit is 5000, the TDS is calculated on a specific invoice line if the invoice line amount is 5001 or greater.
    

    > [!NOTE]
    > <P>The exception threshold amount must be less than or equal to the threshold amount. The TDS is deducted for a transaction if the transaction amount crosses the exception threshold limit, even if the cumulative invoice amount does not cross the threshold limit specified in the <STRONG>Threshold</STRONG> field.</P>



5.  Press CTRL+S or close the form.

## Copy TDS components to another TDS component group

Use this procedure to copy the TDS components that are set up for a TDS component group to another TDS component group.

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **India** \> **Withholding tax components**. Click **Copy**.

2.  Select the TDS component group to copy the TDS components from in the **From** field.

3.  Select the withholding tax component group to copy the TDS components to in the **To** field.
    

    > [!NOTE]
    > <P>The common TDS components that are attached to both the TDS component groups are not copied.</P>



4.  Click **OK** to copy and create TDS components for the other TDS component group in the **Withholding tax components** form.

5.  Press CTRL+S or close the form.

## See also

[(IND) Withholding tax components (form)](https://technet.microsoft.com/library/jj664790\(v=ax.60\))

[(IND) Withholding tax component groups (form)](https://technet.microsoft.com/library/jj678017\(v=ax.60\))

[(IND) Withholding tax groups (modified form)](https://technet.microsoft.com/library/jj677874\(v=ax.60\))

  


