---
title: (RUS) Create a payment proposal for a tax agent invoice
TOCTitle: (RUS) Create a payment proposal for a tax agent invoice
ms:assetid: 84c98b3f-55bb-4b67-a809-d156879bad79
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678437(v=AX.60)
ms:contentKeyID: 49387667
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- payment
- proposal
- (RUS)
- Russia
- tax invoice
---

# (RUS) Create a payment proposal for a tax agent invoice 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Vendor payment proposal** form to create payment proposals that you can use to generate payments to a vendor tax agent. You can also generate payments of value-added tax (VAT) to a tax authority.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Press CTRL+N to create a new journal, and then click **Lines** to open the **Journal voucher** form.

3.  Click the **General** tab, and then, in the **Agreement company** field, select the legal entity that the purchase agreement is created for.

4.  In the **Agreement ID**, select the identification code for the purchase agreement.

5.  Click **Payment proposal** \> **Create payment proposal** to open the **Vendor payment proposal** form.

6.  In the **Proposal type** field, select the type of payment proposal to create. You can create the proposal by due date, cash discount date, or both due date and cash discount date. For more information, see [Vendor payment proposal (class form)](https://technet.microsoft.com/en-us/library/aa554537\(v=ax.60\)).
    

    > [!NOTE]
    > <P>By using payment grouping, you can specify the invoices that must be paid to a specific vendor, and then combine the invoices into one payment. You can periodically settle open customer transactions that include the invoices that belong to different agreement numbers.</P>



7.  Click **Select** to define the criteria for the payment proposal.

8.  Click **OK** to open the **Vendor payment proposal** form. In the upper pane, you can view the open invoice transactions that contribute to the payment proposal line On the **VAT Proposal** tab, you can view the details of the tax transaction for the VAT payment to the tax authorities. The **Account number** field displays the account number of the vendor tax agent.

9.  Click **Transfer** to transfer the proposal lines to the payment journal. In the **Journal voucher** form, two payment lines are displayed for each invoice. One line is for payment to a vendor, and the other line is for tax payment to a tax authority. On the second journal line, the purpose of the VAT payment is displayed in the **Purpose text** field. The second line also displays the account number and address of the tax agent.
    

    > [!NOTE]
    > <P>The vendor account of the tax agent is displayed in the <STRONG>Vendor account</STRONG> field on the <STRONG>Payment</STRONG> tab.</P>



10. In the **VAT operation code** field, view or modify the operation code for the VAT declaration.

11. Click **Functions** \> **Settlement** to open the **Settle open transactions** form.

12. Select open vendor transactions, and mark them for settlement. For more information, see [Settle open transactions - vendor (form)](https://technet.microsoft.com/en-us/library/aa619609\(v=ax.60\)).

13. Close the form.

14. Click **Functions** \> **Generate payments** to open the **Generate payments** form.

15. Select the payment method or the export format, depending on the method of payment on the journal line. Then select the bank account to draw the payment from, and enter the required information. For more information, see [Generate payments - vendor (class form)](https://technet.microsoft.com/en-us/library/aa586980\(v=ax.60\)).

16. Click **OK**.

17. Click **Print** \> **Payment order** to print the payment order report.

18. In the **Journal voucher** form, click **Validate** \> **Validate** to validate the journal line. Then click **Post** \> **Post** to post the journal line. Payments to tax authorities can also be made by using the **Periodic settlement** form.
    

    > [!NOTE]
    > <P>After payments to the vendor tax agent are completed, you can view the settled transactions in the <STRONG>Transactions on settlement</STRONG> form. You can view the posted sales tax transactions in the <STRONG>Sales tax transactions</STRONG> form.</P>



## See also

[(RUS) Periodic reverse (form)](https://technet.microsoft.com/en-us/library/jj678637\(v=ax.60\))

[(RUS) Transactions on settlement (form)](https://technet.microsoft.com/en-us/library/jj678413\(v=ax.60\))

[(RUS) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/en-us/library/jj853227\(v=ax.60\))

[(RUS) Set up the tax agent transactions](rus-set-up-the-tax-agent-transactions.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

