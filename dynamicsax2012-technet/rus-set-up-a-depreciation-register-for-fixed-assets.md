---
title: (RUS) Set up a depreciation register for fixed assets
TOCTitle: (RUS) Set up a depreciation register for fixed assets
ms:assetid: f5192940-04c8-42dd-be82-a792adad63c5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678606(v=AX.60)
ms:contentKeyID: 49388088
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a depreciation register for fixed assets 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The **FA depreciation** register defines accrued depreciation for tangible assets for a specific tax period. This register supports formulation of direct and simple expenses for tax purposes.

The register is created on the basis of depreciation transactions according to the tax model, in accordance with the RF tax code. Register records are created monthly as actual depreciation accrues, with totals accumulated for each depreciated fixed asset. Reporting data is produced by totaling the indicators from the beginning of the reporting period to the reporting date. Registers should be maintained so that information can be grouped separately by amortization amounts per fixed asset, in the form of direct and simple expenses.

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Press CTRL+N to create a new line.

3.  In the **Register type** field, select **FA depreciation**.

4.  In the **Register code** field, enter an identification code for the register.

5.  In the **Register name** field, modify the name of the register, if necessary.

6.  In the **Period type** field, select the type of time period for which the register is created.

7.  Click the **Hide** tab, and move any fields that you want to hide in the register from **Available fields** to **Selected fields**.

8.  In **Selected fields**, select the check box for the register fields to be hidden.

9.  Press CTRL+S or close the form.

10. Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**. Click **Parameters** to set up additional parameters for the register.

11. In the **Register name** field, select **FA depreciation**.

12. In the **Parameter name** field, select the parameter.

13. In the **Value** field, select the fixed asset group by the tax account type and asset type that are to be used to create the register. If you specify more than one value, separate the values with commas.
    

    > [!NOTE]
    > <P>If you do not specify parameter values, the register will contain all fixed assets.</P>



14. Click **Specific** to open the **Expense code setup** form, and then set up expense and revenue codes for the register.

15. Click the **General** tab, and in the **Fixed assets type** field, select the type of the fixed asset.

16. Press CTRL+S or close the form.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

[(RUS) Expense code setup (form)](https://technet.microsoft.com/en-us/library/jj839690\(v=ax.60\))

[(RUS) Calculate the fixed asset depreciation register](rus-calculate-the-fixed-asset-depreciation-register.md)

  


