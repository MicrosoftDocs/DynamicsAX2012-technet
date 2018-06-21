---
title: (IND) Updating taxes in a posted corrected invoice
TOCTitle: (IND) Updating taxes in a posted corrected invoice
ms:assetid: ca10206a-75af-43ea-bf70-7097ef8449b3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664910(v=AX.60)
ms:contentKeyID: 49386239
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- India
- corrective invoice
- posted corrective invoice
- update taxes
---

# (IND) Updating taxes in a posted corrected invoice [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to correct a free text invoice and the related taxes that have been posted. When you correct an invoice that has been posted, a corrected invoice is generated, and you can modify the invoice and post it with the new values. When you post the corrected invoice, a canceling invoice is generated, which brings the combined balance of the original invoice and the canceling invoice to a zero amount.


> [!NOTE]
> <P>This feature is available only if the <STRONG>Free text invoice correction</STRONG> configuration key is selected.</P>



## Post a free text invoice correction

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Select a posted invoice.

3.  On the **Action Pane**, click **Correct invoice**, and then enter the following information:
    
      - **Reason code** – Enter or select the reason code for the correction.
    
      - **Comments** – Enter any additional details about the invoice cancellation.
    
      - **Canceling invoice date** – Enter or select the invoice date to assign to the canceling invoice.

4.  Click **Create corrected invoice** to generate a corrected invoice.

5.  Click **Edit**, and then make any necessary changes to the invoice.

6.  If required by your organization, submit the corrected invoice for workflow review. When the corrected invoice has been approved, continue to the next step.

7.  In the **Free text invoice** form, on the **Action Pane**, click **Post**, and then click **OK**. The corrected invoice is posted, and a canceling invoice is automatically generated. India indirect taxes, VAT, India sales tax, Excise, Service tax and Customs taxes, as well as Tax deducted at source (TDS recoverable) and Tax collected at sources (TCS recoverable) taxes are reversed when the canceling invoice is posted. The corrected India taxes are posted when the corrected invoice is posted.
    
    When the canceled invoice is posted, the respective Excise registers are updated with the applicable excise tax amounts. The Excise registers are also updated with the reverse quantity that was posted on the associated original invoice. For example, if the original invoice quantity was 100 pieces, - 100 pieces will be updated on the Excise register when the canceling invoice is posted.

8.  Optional: In the **Free text invoice** list page in the **Cancel** group, click **View**, and then click **Invoice corrections** to view the invoice correction details. These details include the related invoices:
    
      - **Original invoice** – The invoice that includes the information that you are correcting.
    
      - **Corrected invoice** – The invoice that contains the corrected invoice information.
    
      - **Canceling invoice** – The credit invoice that was generated to cancel the invoice that was most recently corrected. This invoice is created when the corrected invoice is posted.

A **Correction** column is displayed on the **All free text invoices** list page so that you can easily identify which invoices have been canceled and corrected.


> [!IMPORTANT]
> <P>If you are correcting a free text invoice that has been posted with a TCS amount and the tax settlement process has been completed from the <STRONG>Withholding tax payments</STRONG> form for the relevant period, then:</P>
> <UL>
> <LI>
> <P>The TCS amount on the canceling invoice is not reversed when the corrected invoice is posted.</P>
> <LI>
> <P>The TCS amount on the corrected invoice is posted based on the TCS group attached to the corrected invoice line.</P></LI></UL>



**Example:**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <td colspan="2"> <p> <strong>Original Invoice</strong> </p> </td>
    <td colspan="2"> <p> <strong>Corrected Invoice</strong> </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Amount
  </p> </td>
    <td> <p>
   
	 10000.00
  </p> </td>
    <td> <p>
   
	 Amount
  </p> </td>
    <td> <p>
   
	 10000.00
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Tax at 10%
  </p> </td>
    <td> <p>
   
	 1000.00
  </p> </td>
    <td> <p>
   
	 Tax at 20%
  </p> </td>
    <td> <p>
   
	 2000.00
  </p> </td>
  </tr>
</table>


<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <td colspan="3"> <p> <strong>Original Invoice</strong> </p> </td>
  </tr>
  <tr>
    <td colspan="3"> <p> <strong>Accounting entries</strong> </p> </td>
  </tr>
  <tr>
    <td> <p></p> </td>
    <td> <p> <strong>Debit</strong> </p> </td>
    <td> <p> <strong>Credit</strong> </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Trade receivables
  </p> </td>
    <td> <p>
   
	 11000.00
  </p> </td>
    <td> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Sales
  </p> </td>
    <td> <p></p> </td>
    <td> <p>
   
	 10000.00
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 TCS Payable
  </p> </td>
    <td> <p></p> </td>
    <td> <p>
   
	 1000.00
  </p> </td>
  </tr>
</table>


<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <td colspan="3"> <p> <strong>Canceling Invoice</strong> </p> </td>
  </tr>
  <tr>
    <td colspan="3"> <p> <strong>Accounting entries</strong> </p> </td>
  </tr>
  <tr>
    <td> <p></p> </td>
    <td> <p> <strong>Debit</strong> </p> </td>
    <td> <p> <strong>Credit</strong> </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Sales
  </p> </td>
    <td> <p>
   
	 10000.00
  </p> </td>
    <td> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Trade receivables
  </p> </td>
    <td> <p></p> </td>
    <td> <p>
   
	 10000.00
  </p> </td>
  </tr>
</table>


<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <td colspan="3"> <p> <strong>Corrected Invoice</strong> </p> </td>
  </tr>
  <tr>
    <td colspan="3"> <p> <strong>Accounting entries</strong> </p> </td>
  </tr>
  <tr>
    <td> <p></p> </td>
    <td> <p> <strong>Debit</strong> </p> </td>
    <td> <p> <strong>Credit</strong> </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Trade receivables
  </p> </td>
    <td> <p>
   
	 12000.00
  </p> </td>
    <td> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Sales
  </p> </td>
    <td> <p></p> </td>
    <td> <p>
   
	 10000.00
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 TCS Payable
  </p> </td>
    <td> <p></p> </td>
    <td> <p>
   
	 2000.00
  </p> </td>
  </tr>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

