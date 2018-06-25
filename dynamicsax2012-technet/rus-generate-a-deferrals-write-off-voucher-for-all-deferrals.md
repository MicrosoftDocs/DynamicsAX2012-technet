---
title: (RUS) Generate a deferrals write-off voucher for all deferrals
TOCTitle: (RUS) Generate a deferrals write-off voucher for all deferrals
ms:assetid: b5cccceb-98f0-40bb-971e-7c13694c9753
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711540(v=AX.60)
ms:contentKeyID: 49387864
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Generate a deferrals write-off voucher for all deferrals [AX 2012]


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

8.  Click **General ledger** \> **Journals** \> **Deferrals journal**.

9.  Press CTRL+N to create a new line, and enter the required details.

10. In the **Name** field, select the new deferrals journal name.
    

    > [!NOTE]
    > <P>For more information, see "Journal header (form)" in the Applications and Business Processes Help.</P>



11. Click **Lines** to open the **Journal voucher** form.

12. Click **Group operations** \> **Writing off** to open the **Deferrals writing off** form.

13. In the **Transaction date** field, select the write-off date of the transaction.

14. Click **Select** to open the **Inquiry** form to set up the selection criteria.

15. Click **OK** to return to the **Journal voucher** form.
    

    > [!NOTE]
    > <P>Details for deferrals write-off vouchers with an <STRONG>In Process</STRONG> status are displayed in the <STRONG>Journal voucher</STRONG> form based on the filter parameters that you set up in the <STRONG>Inquiry</STRONG> form.</P>



16. Click **Functions** \> **Edit line** to edit the deferrals journal before posting.

17. Click **Post** \> **Post** to post the deferrals write-off voucher details.
    

    > [!NOTE]
    > <P>To view the transactions, click <STRONG>General ledger</STRONG> &gt; <STRONG>Common Forms</STRONG> &gt; <STRONG>Deferrals</STRONG> &gt; <STRONG>Deferral models</STRONG> &gt; <STRONG>Writing off transactions</STRONG>.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

