---
title: (IND) Calculate TCS on payments and bills of exchange
TOCTitle: (IND) Calculate TCS on payments and bills of exchange
ms:assetid: f78917d5-ca32-4d3e-b0ff-f8f1aea36bca
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710945(v=AX.60)
ms:contentKeyID: 49386357
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Calculate TCS on payments and bills of exchange 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can use the Tax Collected at Source (TCS) amounts that are automatically calculated or you can adjust them.

For payments made against an invoice, the following conditions apply:

  - TCS will not be calculated if it has already been calculated at the invoice level, if the payment amount and invoice amount are the same.

  - TCS will not be calculated if the invoice amount, including the TCS amount, exceeds the payment amount.

  - TCS will be calculated on the amount that exceeds the invoice amount, if the invoice amount, including the TCS amount, is less than the payment amount.

<!-- end list -->

1.  Click **General ledger** \> **Journals** \> **General journal**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.
    
    –or–
    
    Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.
    
    –or–
    
    Click **Accounts receivable** \> **Journals** \> **Bill of exchange** \> **Draw bill of exchange journal**.
    
    –or–
    
    Click **Accounts receivable** \> **Journals** \> **Bill of exchange** \> **Redraw bill of exchange journal**.
    
    –or–
    
    Click **Accounts receivable** \> **Journals** \> **Bill of exchange** \> **Protest bill of exchange journal**.

2.  Click **Lines**.

3.  Select a customer or a vendor in the **Account** field.

4.  Click **Functions** \> **Settlement**.

5.  In the **Open transaction editing** form, select a specific invoice to settle.
    
    If TCS is already calculated for the invoice, the base amount that TCS is calculated on is displayed in the **Amount origin** field, and the TCS amount calculated for the transaction is displayed in the **TCS** field.
    
    The total payment amount, including the TCS amount, is displayed in the **Amount** field on the **Payment** tab. Close the form.

6.  In the **Journal voucher** form, the default TCS group defined for the customer is displayed in the **TCS group** field and can be changed. The TCS calculated on journal lines is based on the formula defined for the TCS tax codes in the TCS group.
    

    > [!NOTE]
    > <P>TCS is calculated only if the <STRONG>Calculate withholding tax</STRONG> check box is selected for the vendor or customer on the <STRONG>Setup</STRONG> tab of the <STRONG>Vendors</STRONG> form or the <STRONG>Customers</STRONG> form.</P>



7.  Click the **Tax information** tab. The company name is displayed in the **Name** field. You can select a company name and alternate address.

8.  Click **Withholding tax** \> **Withholding tax** to open the **Temporary withholding tax transactions** form, where you can view calculated and adjusted TCS amounts.

9.  Click **Threshold** to open the **Threshold** form, where you can view the threshold limit defined for the TCS tax component that is attached to a specific TCS tax code in this form.

10. Click **Designer** to open the **Formula designer** form, where you can view the formula that is defined for a specific TCS tax code in this form.

11. Close the **Threshold** form, **Formula designer** form, and the **Temporary withholding tax transactions** form to return to the **Journal voucher** form.

12. Validate and post the journal.
    

    > [!NOTE]
    > <P>The TCS amount calculated on payments is posted to the payable account defined for each TCS tax code in the TCS group. The payable accounts for TCS tax codes are defined in the <STRONG>Withholding tax codes</STRONG> form.</P>



13. In the **Journal voucher** form, click **Inquiries** \> **Voucher** to open the **Voucher transactions** form. Click **Posted withholding tax** to open the **Withholding tax transactions** form.
    
    The total percentage used to calculate TCS for the transaction is displayed in the **Value** field.
    
    The fields on the **Overview**, **General**, and **Amount** tabs in the **Withholding tax transactions** form display the TCS information that is calculated for the TCS group attached to the transaction. You can view the TCS calculation information for each TCS tax code that is attached to the TCS group in this form.

## See also

[(IND) Threshold (form)](https://technet.microsoft.com/en-us/library/jj677862\(v=ax.60\))

[(IND) Formula designer (form)](https://technet.microsoft.com/en-us/library/jj677983\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

