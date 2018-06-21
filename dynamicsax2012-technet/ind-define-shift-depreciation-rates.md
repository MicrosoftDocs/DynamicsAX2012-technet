---
title: (IND) Define shift depreciation rates
TOCTitle: (IND) Define shift depreciation rates
ms:assetid: e8c1329b-a17e-41e5-9dc8-d98cc9135a73
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710897(v=AX.60)
ms:contentKeyID: 49386309
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Define shift depreciation rates [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can define rates for single shift, double shift, and triple shift to calculate depreciation using Straight line percentage method or Reducing balance method.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Fixed assets** \> **Setup** \> **Depreciation** \> **Depreciation profiles**.

2.  Press CTRL+N to create a new depreciation profile for the Straight line percentage method or the Reducing balance method.

3.  Select one of the following options in the **Method** field:
    
      - Select **Straight line percentage** for the depreciation profile that follows the Straight line percentage method.
    
      - Select **Reducing balance** for the depreciation profile that follows the Reducing balance method.

4.  Enter the percentage for the Straight line percentage method or the Reducing balance method in the **Percentage** field.

5.  Click **Shift depreciation** to define rates that are used to calculate the shift depreciation for the Straight line percentage method or the Reducing balance method.

6.  Press CTRL+N to create a new line.

7.  Enter the date to begin applying the shift depreciation rates in the **From date** field.

8.  Enter the ending date for the shift depreciation rates in the **To date** field.

9.  Enter the rates for shift depreciation in the following fields:
    
      - **Single shift percentage** – Enter the percentage to calculate depreciation for a single shift. The single shift percentage is the same as the percentage of depreciation that is specified in the **Percentage** field.
        

        > [!NOTE]
        > <P>If you create more than one record to define different rates for a single shift, the rate that is within the period of the system date is displayed in the <STRONG>Percentage</STRONG> field.</P>

    
      - **Double shift percentage** – Enter the percentage to calculate depreciation for a double shift.
    
      - **Triple shift percentage** – Enter the percentage to calculate depreciation for a triple shift.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

