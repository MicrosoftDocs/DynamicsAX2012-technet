---
title: (POL) Create a proposal of compensation transaction from a vendor account
TOCTitle: (POL) Create a proposal of compensation transaction from a vendor account
ms:assetid: 02a7a0a0-3d29-43c9-a63c-d47244821908
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678115(v=AX.60)
ms:contentKeyID: 49386839
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (POL) Create a proposal of compensation transaction from a vendor account [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Vendors** form to create a proposal of compensation transaction from a vendor account in order to automate settlements between the vendor account and a customer account. A proposed settlement report is automatically generated, and you can accept the proposal or modify it. When the settlement is done, you can post the proposed settlements in the general journal.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Select a vendor. On the **Action Pane**, in the **Maintain** group, click **Edit**.

2.  On the **Miscellaneous details** tab, in the **Customer account** field, select the customer account that is to be compensated.

3.  On the **Action Pane** in the **Transactions** group, click **Transactions**. **Vendor transactions** form, and then select one or more transactions to compensate.

4.  On the **Vendor transactions** form, select one or more transactions to compensate.
    

    > [!NOTE]
    > <P>Use the &lt;CTRL&gt; or &lt;SHIFT&gt; key to select more than one transaction.</P>



5.  Click **Compensation** to open the **Compensation of customer/vendor transactions** form.

6.  In the lower pane, on the **Overview** tab, select the **Voucher** checkbox the customer transactions that are to be compensated by the vendor transaction.

7.  Click **Create compensation**.

8.  On the **Create compensation journal lines** form, **Journal** field, select the ledger journal in which the compensation transactions will be created.

9.  In the **Journal batch number** field, select the ledger journal batch number.

10. In the **Transaction date** field, select the date for the compensation transaction.

11. Select the **Print compensation report** check box to print the compensation report.

12. Click **OK** to generate a **Proposal of compensation transaction** report.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

