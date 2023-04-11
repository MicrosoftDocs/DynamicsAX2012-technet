---
title: (RUS) Set up an object information register for intangible assets
TOCTitle: (RUS) Set up an object information register for intangible assets
ms:assetid: 9f1fc320-a711-4313-8ed9-8c0e8fd678ad
ms:mtpsurl: https://technet.microsoft.com/library/JJ678543(v=AX.60)
ms:contentKeyID: 49387771
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up an object information register for intangible assets 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The **IA – object information** register collects information about the availability and movement of all company property that is designated as a depreciating intangible asset for tax purposes. The register addresses depreciable property classified as Intangible, Financial, or Goodwill in the Fixed assets module.

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Press CTRL+N to create a new line.

3.  In the **Register type** field, select **IA – object information**.

4.  In the **Register code** field, enter an identification code for the register.

5.  In the **Register name** field, modify the name of the register, if necessary.

6.  In the **Period types** field, select the type of time period for which the register is created.

7.  Click the **Hide** tab, and move any fields that you want to hide in the register from **Available fields** to **Selected fields**.

8.  In **Selected fields**, select the check box for the register fields to be hidden.

9.  Click the **Parameters** tab to set up additional parameters for the register.

10. In the **Parameter name** field, select the parameter.

11. In the **Value** field, select the intangible assets group by the tax account type and asset type to be used to create the register. If you specify more than one value, separate the values with commas.
    

    > [!NOTE]
    > <P>If you do not specify parameter values, the register will contain all intangible assets.</P>



12. Press CTRL+S or close the form.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/library/jj853195\(v=ax.60\))

[(RUS) Calculate the intangible asset object information register](rus-calculate-the-intangible-asset-object-information-register.md)

  


