---
title: (RUS) Set up a depreciation register (nonlinear method) for fixed assets
TOCTitle: (RUS) Set up a depreciation register (nonlinear method) for fixed assets
ms:assetid: d77c1b56-46b0-45b4-8e69-fce6a5d3a55b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711667(v=AX.60)
ms:contentKeyID: 49387990
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up a depreciation register (nonlinear method) for fixed assets [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The **FA depreciation (nonlinear method)** register displays the assets that are depreciated using the tax non-linear method, and the fixed assets are grouped by depreciation group and subgroup.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Press CTRL+N to create a new line.

3.  In the **Register type** field, select **FA depreciation (nonlinear method)**.

4.  In the **Register code** field, enter an identification code for the register.

5.  In the **Register name** field, modify the name of the register, if necessary.

6.  In the **Period type** field, select the type of time period for which the register is created.

7.  Click the **Hide** tab, and move any fields that you want to hide in the register from **Available fields** to **Selected fields**.

8.  In **Selected fields**, select the check box for the register fields to be hidden.

9.  Press CTRL+S or close the form.

10. Click **General ledger** \> **Setup** \> **Profit tax** \> **Register parameters** to set up additional parameters for the register.

11. In the **Register name** field, select **FA depreciation (nonlinear method)**.

12. In the **Parameter name** field, select the parameter.

13. In the **Value** field, select the depreciation group and the fixed asset type that are to be used to create the register. If you specify more than one value, separate the values with commas.
    

    > [!NOTE]
    > <P>If you do not specify parameter values, the register will contain all fixed assets.</P>



14. Click **Specific** to open the **Expense code setup** form, and then set up expense and revenue codes for the register.

15. Click the **General** tab, and in the **Fixed assets type** field, select the type of the fixed asset.

16. Press CTRL+S or close the form.

## See also

[(RUS) Calculate the fixed assets depreciation (nonlinear method) register](rus-calculate-the-fixed-assets-depreciation-nonlinear-method-register.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

