---
title: Create various kinds of sales tax codes
TOCTitle: Create various kinds of sales tax codes
ms:assetid: ac8bec09-b20f-4b28-8569-88d82793a326
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498564(v=AX.60)
ms:contentKeyID: 36058918
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- packing duty sales tax code
- purchase duty sales tax code
- sales tax codes
---

# Create various kinds of sales tax codes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

## Create a sales tax code

Use the **Sales tax codes** form to create sales tax codes.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Click **New** to create a sales tax code.

3.  In the **Sales tax code** field, enter a unique identifier for the sales tax code.

4.  In the **Name** field, enter a name for the sales tax code.

5.  Select values for the following required fields:
    
      - **Currency**
    
      - **Settlement period**
    
      - **Ledger posting group**

6.  Click the **Calculation** FastTab and select values for the **Origin**, **Marginal base**, and **Calculation method** fields.

7.  To define percentages or amounts and rate intervals for the sales tax calculation in specific periods, click **Values**. Close the form when you are finished.

8.  To define minimum and maximum sales tax amounts in specific periods, click **Limits**.

## Create a sales tax code as a packing duty

You can create a sales tax code to be used as a packing duty.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Click **New** to create a sales tax code.

3.  In the **Sales tax code** field, enter a unique identifier for the sales tax code.

4.  In the **Name** field, enter a name for the sales tax code.

5.  Select values for the following required fields:
    
      - **Currency**
    
      - **Settlement period**
    
      - **Ledger posting group**

6.  Click the **Calculation** FastTab. In the **Origin** field, select **Amount per unit**.

7.  In the **Unit** field, select the unit that the packing duty tax is calculated for. This is also the unit that is used in the amount-per-unit calculation.

8.  Select the **Packing duty** check box.

9.  To define the sales tax amount per unit, click **Values**.

## Create a sales tax code as a purchase duty

You can create a sales tax code to be used as a purchase duty.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Click **New** to create a sales tax code.

3.  In the **Sales tax code** field, enter a unique identifier for the sales tax code.

4.  In the **Name** field, enter a name for the sales tax code.

5.  Select values for the following required fields:
    
      - **Currency**
    
      - **Settlement period**
    
      - **Ledger posting group**

6.  Click the **Calculation** FastTab. In the **Origin** field, select **Amount per unit**.

7.  In the **Unit** field, select the unit that the purchase duty tax is calculated for. This is also the unit that is used in the amount-per-unit calculation.

8.  (AUT) If your legal entity’s primary address is in Austria, click the **General** FastTab and select the **Purchase duty** check box.

9.  To define the sales tax amount per unit, click **Values**.

## See also

[Sales tax codes (form)](https://technet.microsoft.com/en-us/library/aa553257\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

