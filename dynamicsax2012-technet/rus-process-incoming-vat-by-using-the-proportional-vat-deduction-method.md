---
title: (RUS) Process incoming VAT by using the Proportional VAT deduction method
TOCTitle: (RUS) Process incoming VAT by using the Proportional VAT deduction method
ms:assetid: a2c4724f-6135-4b4d-aa40-1849e1ee5eb5
ms:mtpsurl: https://technet.microsoft.com/library/JJ678561(v=AX.60)
ms:contentKeyID: 49387789
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Process incoming VAT by using the Proportional VAT deduction method 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to process the incoming VAT amount using the proportional VAT refund method. At the end of each tax period, you must process the following incoming VAT transactions:

  - Factures posted for purchased items and services.

  - Write-offs or deferral disposals.

When you select the factures for processing VAT, the blocked and unblocked amounts are calculated for each facture based on the write-off and disposal transactions that are posted for the deferrals. The VAT rate is calculated based on the percentage specified in the **Sales tax codes** form.

1.  Click **Accounts payable** \> **Periodic** \> **Purchase book** \> **Incoming VAT processing**.

2.  Click **Select...** to open the **Incoming VAT processing** **-** **Select data for period** form.

3.  In the **From date** and **To date** fields, enter the starting and ending date of the VAT processing period.

4.  Click **OK**. Details that are related to the posted factures and write-offs or deferral disposals are displayed in the **Purchase book** (**Incoming VAT processing**) form.
    
    The facture details are displayed on the **Overview** tab. In the lower pane, the facture amount is split in proportion to the written-off deferrals amount, and is displayed on the **Operations** tab on a separate line.
    

    > [!NOTE]
    > <P>The blocked and unblocked VAT amounts are calculated and displayed for each facture in the lower pane. The written-off deferral amount is not locked, and can be posted. However, the remainder of the facture amount is locked, and its posting is postponed. The <STRONG>Lock</STRONG> check box is selected for these lines.</P>



5.  Select the **Marked** check box to select the facture for processing.

6.  Click **Post** to process the incoming VAT.

  


