---
title: (BRA) Process electronic payment remittances
TOCTitle: (BRA) Process electronic payment remittances
ms:assetid: b6dfc0bc-f391-4dc7-beb8-d056bdb3da9d
ms:mtpsurl: https://technet.microsoft.com/library/JJ730976(v=AX.60)
ms:contentKeyID: 49675206
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- remittance file
- export file
- BR - 00008
audience: Application User
ms.search.region: Brazil
---

# (BRA) Process electronic payment remittances 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can make electronic payments by transferring files between a legal entity and a bank:

  - You can generate and send an electronic remittance file to a bank. The export file contains information about invoices that must be received or paid, requests for return invoices, or changes to customer or vendor addresses.

  - You can import a return file from a bank. The return file contains information about the acceptance of an invoice together with the payment number that is provided by the bank. Alternatively, the return file contains information about the payments that are received from a customer or paid to a vendor. For more information, see [(BRA) Process electronic payment returns](bra-process-electronic-payment-returns.md).

Use this procedure to generate an export file for a customer or vendor payment. After you generate the export file, the payment status in the **Payment status** field on the **Overview** tab in the **Journal voucher** form is updated to **Sent**.

You can use a simple or complex file structure to generate a remittance file. If you use a complex file structure to generate the remittance file, you must specify the payment type, payment way, and segments for the complex file structure. For more information, see [(BRA) Set up an electronic payment process for a complex file structure](bra-set-up-an-electronic-payment-process-for-a-complex-file-structure.md).

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Select or create a payment journal, and then click **Lines**. In the **Journal voucher** form, create payment journal lines. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  On the **Payment** tab, in the **Method of payment** field, select an electronic method of payment for the customer or vendor.
    

    > [!NOTE]
    > <P>You must select an electronic method of payment that uses the format for the configurable layout file. For more information, see <A href="bra-set-up-an-electronic-method-of-payment.md">(BRA) Set up an electronic method of payment</A>.</P>



4.  In the **Payment specification** field, select the payment specification that is attached to the method of payment.
    

    > [!NOTE]
    > <P>If the electronic payment uses complex file layouts, the <STRONG>Payment type</STRONG> and <STRONG>Payment way</STRONG> fields are updated with the payment type and payment way that you specified in the <STRONG>Payment specification</STRONG> form for the method of payment.</P>



5.  In the **Document type**, **Instruction 1**, **Instruction 2**, and **Bank folder** fields, select the identification codes of the document type, instruction 1, instruction 2, and bank folder for the layout group.
    

    > [!NOTE]
    > <P>These fields are available only if the electronic method of payment that you selected in the <STRONG>Method of payment</STRONG> field uses the configurable layout file.</P>



6.  Click **Functions** \> **Generate payments** to open the **Generate payments** form.

7.  In the **Method of payment** field, select the electronic method of payment to generate payments for.

8.  In the **Bank account** field, select a bank account to use to make or receive the payment.

9.  Select the **Show format dialog** check box to open the **Export options** form before the payment is generated.

10. Click **OK** to open the **Export options** form.

11. In the **File name** field, enter a path and a file name for the remittance file.

12. Click **OK** to generate the remittance file.

## See also

[Key tasks: Customer payments and settlements](key-tasks-customer-payments-and-settlements.md)

[Key tasks: Vendor payments and settlements](key-tasks-vendor-payments-and-settlements.md)

  


