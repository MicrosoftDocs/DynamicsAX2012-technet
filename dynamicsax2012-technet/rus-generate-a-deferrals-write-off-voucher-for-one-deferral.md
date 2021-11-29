---
title: (RUS) Generate a deferrals write-off voucher for one deferral
TOCTitle: (RUS) Generate a deferrals write-off voucher for one deferral
ms:assetid: 4a7af4c6-6700-4e52-a13f-23a1ddeb6285
ms:mtpsurl: https://technet.microsoft.com/library/JJ665351(v=AX.60)
ms:contentKeyID: 49387439
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate a deferrals write-off voucher for one deferral 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.

2.  Press CTRL+N to create a new line, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Journal names setup (form)" in the Applications and Business Processes Help.</P>



3.  In the **Name** field, enter the name of the journal.

4.  In the **Description** field, enter a short description of the journal.

5.  In the **Journal type** field, select **Deferrals**.

6.  In the **Voucher series** field, select the number sequence that is used for voucher numbering.

7.  Press CTRL+S or close the form.

8.  Click **General ledger** \> **Journals** \> **Deferrals journal**. to open the **Deferrals journal** form.

9.  Press CTRL+N to create a new line, and enter the required details.

10. In the **Name** field, select the new deferrals journal name.
    

    > [!NOTE]
    > <P>For more information, see "Journal header (form)" in the Applications and Business Processes Help.</P>



11. Click **Lines** to open the **Journal voucher** form.

12. Press CTRL+N to open the **Create new line** form.

13. In the **Transaction date** field, select the write-off date of the transaction.

14. In the **Transactions type** field, select **Writing off**.

15. In the **Deferral ID** field, select the deferral code.

16. In the **Model number** field, select the deferrals model number.

17. Click **OK** to return to the **Journal voucher** form.
    

    > [!NOTE]
    > <P>Details for the deferrals write-off voucher with an <STRONG>In Process</STRONG> status are displayed in the <STRONG>Journal voucher</STRONG> form based on the transaction date that you entered.</P>



18. Click **Functions** \> **Edit line** to edit the deferrals journal before posting.

19. Click **Post** \> **Post** to post the deferrals journal.
    

    > [!NOTE]
    > <P>To view the transactions, click Click <STRONG>General ledger</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Deferrals</STRONG>.click<STRONG>Deferrals models</STRONG> &gt; <STRONG>Writing off transactions</STRONG>.</P>



## See also

[(RUS) Create new line (form)](https://technet.microsoft.com/library/jj678398\(v=ax.60\))

  


