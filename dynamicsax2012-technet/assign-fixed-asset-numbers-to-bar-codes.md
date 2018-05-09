---
title: Assign fixed asset numbers to bar codes
TOCTitle: Assign fixed asset numbers to bar codes
ms:assetid: 388b604d-2531-42a0-bf3f-49872adc9bc6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa570140(v=AX.60)
ms:contentKeyID: 36056622
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Assign fixed asset numbers to bar codes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can assign bar codes to fixed assets when fixed assets are created, to current fixed assets, or to fixed asset groups.

## Assign bar codes when fixed assets are created

1.  Click **Fixed assets** \> **Setup** \> **Fixed assets parameters**. Click the **Barcode** FastTab.

2.  Select the **Bar code equals fixed asset number** check box. The bar code will be assigned when fixed assets are created.

## Assign bar codes to current fixed assets

1.  Click **Fixed assets** \> **Setup** \> **Fixed assets parameters**. Click the **Barcode** FastTab.

2.  Select the **Bar code equals fixed asset number** check box.

3.  Click **Fixed assets** \> **Periodic** \> **Assign fixed asset number to bar code**.

4.  Process the batch job. This will assign bar codes to the selected assets.

5.  If the bar codes should not be assigned to fixed assets as each fixed asset is created, clear the **Bar code equals fixed asset number** check box in the **Fixed assets parameters** form every time that you process the batch.

## Assign bar codes to fixed asset groups

Instead of using the fixed asset number codes as bar codes, you can assign fixed asset bar code number sequences to specific fixed asset groups.

1.  Click **Fixed assets** \> **Setup** \> **Fixed asset groups**.

2.  For each fixed asset, select the fixed asset group to assign group-specific bar codes to.

3.  Select the **Autonumber bar codes** check box.

4.  Select the appropriate number sequence for the fixed asset group in the **Bar code number sequence** field.

## See also

[About bar codes for fixed assets](about-bar-codes-for-fixed-assets.md)

[Assign fixed asset number to bar code (form)](https://technet.microsoft.com/en-us/library/aa553643\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

