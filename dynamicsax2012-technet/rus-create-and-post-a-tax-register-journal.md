---
title: (RUS) Create and post a tax register journal
TOCTitle: (RUS) Create and post a tax register journal
ms:assetid: 1c7005cc-05f0-48ab-b7b4-7669ec068c78
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ856110(v=AX.60)
ms:contentKeyID: 50406409
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create and post a tax register journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to create and post a tax register journal. After you create and post a tax register journal for advances, you can use the **Journal** form to view the new journal line that contains the exchange adjustment amount for tax accounting. The exchange adjustment amount is based on the setup in the **Advance adjustment parameters** form. For more information, see [(RUS) Set up advance adjustment parameters for advance holders](rus-set-up-advance-adjustment-parameters-for-advance-holders.md).

1.  Click **General ledger** \> **Journals** \> **Tax register journal**.

2.  Press CTRL+N to create a new tax register journal.

3.  Click **Lines** to open the **Register journal lines** form.

4.  Click **Register lines** to open the **Exchange adjustment in tax accounting** form, where you can modify the register lines.
    

    > [!NOTE]
    > <P>You must select the <STRONG>Exchange adjustment in tax accounting</STRONG> register in the <STRONG>Tax registers</STRONG> form.</P>



5.  Close the form.

6.  In the **Register journal lines** form, select the **Approved** check box to approve the register calculation.

7.  In the **Worker** field, select the identification number of the employee who approved the register calculation.

8.  Close the form.

9.  In the **Tax register journal** form, click **Ledger journal** \> **Foreign currency revaluation** to open the **Journal** form.

10. To create an exchange adjustment journal, click **Create** \> **Create journal** to open the **Journal voucher** form.

11. Click **Lines** to view the new journal line that shows the calculated amount in the **Exchange adjustment in tax accounting** register and general ledger accounts. The amount that is calculated is based on the setup in the **Advance adjustment parameters** form.

12. Click **Post** to post the journal.

## See also

[(RUS) Create and post a payment journal line for an advance holder](rus-create-and-post-a-payment-journal-line-for-an-advance-holder.md)

  


