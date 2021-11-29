---
title: (RUS) Generate a deferrals writing off reversal voucher
TOCTitle: (RUS) Generate a deferrals writing off reversal voucher
ms:assetid: afa631bf-c265-4775-9199-eb7b8c6bddaa
ms:mtpsurl: https://technet.microsoft.com/library/JJ711519(v=AX.60)
ms:contentKeyID: 49387844
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate a deferrals writing off reversal voucher 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.

2.  Press CTRL+N to create a new line, and enter the required details.

3.  In the **Name** field, enter the name of the journal.

4.  In the **Description** field, enter a short description of the journal.

5.  In the **Journal type** field, select **Deferrals**.

6.  In the **Voucher series** field, select the deferral voucher number sequence.

7.  Press CTRL+S or close the form.
    

    > [!NOTE]
    > <P>For more information, see "Journal names setup (form)" in the Applications and Business Processes Help.</P>



8.  Click **General ledger** \> **Journals** \> **Deferrals journal**.

9.  Press CTRL+N to create a new line, and enter the required details.

10. In the **Name** field, select the deferrals journal name.
    

    > [!NOTE]
    > <P>For more information, see "Journal header (form)" in the Applications and Business Processes Help.</P>



11. Click **Lines** to open the **Journal voucher** form.

12. Click **Group operations** \> **Writing off reversal** to open the **Writing off reversal** form to generate transactions writing off reversal for all deferrals.

13. In the **Reversal date** field, select the date for reversal of the transaction.

14. Click **Select** to open the **Inquiry** form, and set up the filter criteria.

15. Click **OK** and return to the **Journal voucher** form.
    

    > [!NOTE]
    > <P>The details of the write-off reversal voucher are displayed in the <STRONG>Journal voucher</STRONG> form that was written off on the specified date.</P>



16. Click **Post** \> **Post** to post the reversal voucher. The deferrals and ledger transactions that are specified in the posting profile are generated.

## See also

[(RUS) Journal voucher (form)](https://technet.microsoft.com/library/jj923409\(v=ax.60\))

[(RUS) Deferrals transactions (form)](https://technet.microsoft.com/library/jj678472\(v=ax.60\))

  


