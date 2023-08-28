---
title: (FIN) Generate payments by using Generic ISO20022 credit transfers
TOCTitle: (FIN) Generate payments by using Generic ISO20022 credit transfers
ms:assetid: ac27604a-e16b-4d50-bac0-dff41be3f684
ms:mtpsurl: https://technet.microsoft.com/library/Hh500179(v=AX.60)
ms:contentKeyID: 37820242
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Finland
---

# (FIN) Generate payments by using Generic ISO20022 credit transfers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Single European Payment Area (SEPA) is an initiative in the European Union (EU) member states to provide a common electronic banking process for transferring payments within the SEPA region, which is comprised of 32 countries/regions. The SEPA credit transfer is one of the SEPA instruments that allow you to send payments electronically to the creditor’s bank account. In Finland, SEPA credit transfers have been extended and standardized to also support non-SEPA credit transfers called Generic ISO20022 credit transfers. This format is used for payments made in a currency other than euros and for payments that are sent outside the SEPA region.

## Set up a new method of payment for Generic ISO20022-based credit transfers

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Create a new method of payment for Generic ISO20022 credit transfers.

3.  In the **Method of payment** field, enter an appropriate identifier, such as **Generic ISO20022 CredTrans FI**, to make payments by using Generic ISO20022 credit transfers.

4.  Enter other information for the method of payment, as needed.

5.  Click the **File formats** FastTab, and then in the **Export format** field, select **Generic ISO20022 CredTrans FI**.
    

    > [!NOTE]
    > <P>If the <STRONG>Export format</STRONG> field list is empty, click <STRONG>Setup</STRONG>, and then select one of the available formats.</P>



6.  Close the form.

## Create a vendor payment journal to transfer a payment to a bank

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a new journal, and then click **Lines** to open the **Journal voucher** form.

3.  Enter the required details for the journal line. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

4.  In the **Offset account** field, select the offset bank account.

5.  Click the **Bank** tab, and then in the **Account identification** field, select the third-party bank account.

6.  Click **Functions** \> **Generate payments**.

7.  In the **Method of payment** field, select the required method of payment.

8.  In the **Bank account** field, select the offset bank account to filter the vendor transaction lines of payment.

9.  Select the **Show format dialog** check box, and then click **OK** to open the **Microsoft Dynamics AX** payment format dialog box.

10. In the **Processing date** field, enter the date when the bank should initiate the payments.

11. In the **Remittance Information** field, select one of the following options:
    
      - **Structured** – Generate structured remittance information for each payment.
    
      - **Unstructured** – Generate unstructured remittance information for each payment.

12. In the **Amount limit** field, enter the maximum transaction amount allowed per line.

13. In the **File name** field, enter the file path and name of the payment file.

14. Click **OK** to generate a payment file.

15. Close the forms.

## See also

[Methods of payment - vendors (form)](https://technet.microsoft.com/library/aa618565\(v=ax.60\))

  


