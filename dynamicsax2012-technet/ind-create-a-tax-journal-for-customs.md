---
title: (IND) Create a tax journal for customs
TOCTitle: (IND) Create a tax journal for customs
ms:assetid: 7ddc9f42-5f75-404a-a863-f27b31d9793d
ms:mtpsurl: https://technet.microsoft.com/library/JJ677974(v=AX.60)
ms:contentKeyID: 49385937
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Create a tax journal for customs 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create tax journals to transfer the opening balances to ledger accounts or post adjustment entries between a specific tax component and any other tax component.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Create a new journal, and then click the **Lines** button to open the **Journal voucher** form.

3.  Enter the required details and click **Functions** \> **Create tax journal** to open the **Tax journal** form.

4.  Select **Customs** in the **Tax type** field.

5.  Select the tax ledger posting group for customs in the **Tax ledger posting group** field.

6.  Select the IEC number for the tax ledger posting group in the **Tax registration number** field.

7.  Enter the posting date for the journal in the **To date** field.

8.  Press CTRL+N and select the tax component for the tax registration number and the tax ledger posting group in the **Tax component** field.

9.  Select the ledger account to post the balance amount in the **Account** field.

10. Enter the tax balance amount in the **Amount** field.

11. Select the tax code in the **Tax code** field to update the tax amount.

12. Click **Transfer** to transfer the tax journal record to the **Journal voucher** form.

13. In the **Journal voucher** form, you can view the details of the tax journal line that was transferred.

14. Select the offset ledger account that the transaction is posted to in the **Offset account** field.

15. Post the journal.

  


