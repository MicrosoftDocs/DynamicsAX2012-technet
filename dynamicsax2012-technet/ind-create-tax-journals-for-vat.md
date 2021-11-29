---
title: (IND) Create tax journals for VAT
TOCTitle: (IND) Create tax journals for VAT
ms:assetid: 7cc96857-f2a5-4235-9163-1cda540fb296
ms:mtpsurl: https://technet.microsoft.com/library/JJ677962(v=AX.60)
ms:contentKeyID: 49385924
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Create tax journals for VAT 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can create tax journals to transfer the opening balances to ledger accounts or post adjustment entries between a specific tax component and any other tax component.

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Create a new journal and click the **Lines** button to open the **Journal voucher** form.

3.  Enter the required details and click **Functions** \> **Create tax journal** to open the **Tax journal** form.

4.  Select **VAT** in the **Tax type** field.

5.  Select the tax ledger posting group for VAT in the **Tax ledger posting group** field.

6.  Select the Tax Identification Number (TIN) for the tax ledger posting group in the **Tax registration number** field.

7.  Enter the posting date for the journal in the **To date** field.

8.  Press CTRL+N and select the tax component for the tax registration number and the tax ledger posting group in the **Tax component** field.

9.  Select the ledger account to post the balance amount to in the **Account** field.

10. Enter the tax balance amount in the **Amount** field.

11. Select the tax code in the **Tax code** field to update the tax amount.

12. Click **Transfer** to transfer the tax journal record to the **Journal voucher** form.

13. In the **Journal voucher** form, you can view the details of the tax journal line that was transferred.

14. Select the offset ledger account that the transaction is posted to in the **Offset account** field.

15. Validate and post the journal.

## See also

[(IND) Create a tax journal for service tax](ind-create-a-tax-journal-for-service-tax.md)

[(IND) Tax journal ( form)](https://technet.microsoft.com/library/jj664732\(v=ax.60\))

[(IND) Journal voucher - General journal (modified form)](https://technet.microsoft.com/library/jj678053\(v=ax.60\))

  


