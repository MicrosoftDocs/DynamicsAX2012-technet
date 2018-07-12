---
title: (RUS) Set up a depreciation register (nonlinear method) for intangible assets
TOCTitle: (RUS) Set up a depreciation register (nonlinear method) for intangible assets
ms:assetid: c03fb9e1-8d93-4783-860a-3f249e46ed38
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711572(v=AX.60)
ms:contentKeyID: 49387896
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a depreciation register (nonlinear method) for intangible assets 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The **FA depreciation (nonlinear method)** register records information about intangible assets that are depreciated using the tax non-linear method.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Press CTRL+N to create a new line.

3.  In the **Register type** field, select **IA depreciation (nonlinear method)**.

4.  In the **Register code** field, enter an identification code for the register.

5.  In the **Register name** field, modify the name of the register, if necessary.

6.  In the **Period types** field, select the type of time period for which the register is created.

7.  Click the **Hide** tab, and move any fields that you want to hide in the register from **Available fields** to **Selected fields**.

8.  In **Selected fields**, select the check box for the register fields to be hidden.

9.  Click the **Parameters** tab to set up additional parameters for the register.

10. In the **Parameter name** field, select the parameter.

11. In the **Value** field, select the depreciation group and the intangible asset type that are to be used to create the register. If you specify more than one value, separate the values with commas.
    

    > [!NOTE]
    > <P>If you do not specify parameter values, the register will contain all intangible assets.</P>



12. Press CTRL+S or close the form.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

[(RUS) Expense code setup (form)](https://technet.microsoft.com/en-us/library/jj839690\(v=ax.60\))

[(RUS) Calculate the intangible assets depreciation (nonlinear method) register](rus-calculate-the-intangible-assets-depreciation-nonlinear-method-register.md)

  


