---
title: Reimburse for an expense report
TOCTitle: Reimburse for an expense report
ms:assetid: a658136f-8379-46f5-a2f2-14ebd6b35bfb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243046(v=AX.60)
ms:contentKeyID: 36058871
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- expenses
- reimbursement
- reimbursements
- expense
audience: Application User
ms.search.region: Global
---

# Reimburse for an expense report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can reimburse an employee for an expense report by using the **Vendor details** form in **Procurement and sourcing**. However, before you can reimburse an employee, you must create a vendor group for employees and a vendor record for the employee whom you are reimbursing.

## Set up an employee vendor group

1.  Click **Accounts payable** \> **Setup** \> **Vendors** \> **Vendor groups**.

2.  In the **Vendor group** field, enter a unique identifier for the vendor group.

3.  Optional: In the **Description** field, enter a short description of the vendor group.

4.  Optional: In the **Terms of payment** field, select the terms of payment that apply to the employees who are assigned the vendor group. Although this field is not mandatory, terms of payment is part of managing all vendor accounts and is strongly recommended.

5.  Optional: In the **Settle period** field, select the standard interval between the due date for payments to the employees in the vendor group, which is defined by the **Terms of payment**, and the date on which the payments are drawn from your bank account. Although this field is not mandatory, it is important for liquidity calculations that are based on the cash-flow forecast.

6.  Select a tax group for the employee vendor group.

## Create a vendor account for an employee

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Click the **Vendor** button in the **New** group to create a new vendor record.

3.  In the **Name** field, enter the name of the employee.

4.  In the **Group** field, select the vendor group that applies to the vendor.

5.  Enter values in the other fields as appropriate.

6.  If you will pay the employee using checks, you can click **Setup** \> **Address** and set up an alternative address that has an address type of **Remit-to**.

## Map a vendor account to an employee

1.  Click **Human resources** \> **Common** \> **Workers** \> **Employees**.

2.  Select the employee whom you want to add to a vendor account, and then click **Map worker to vendor** on the **Expense management** tab.

3.  In the **Account type** field, select a vendor account type, and then in the **Account** field, select the vendor account number that you have created for the employee.

4.  Enter the per diem amount for the employee.

## Reimburse an employee

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a journal and then click **Lines** to open the **Journal voucher** form for payment journal lines. For more information about how to create journals, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  In the **Account** field, enter the employee vendor account to which the payment will be issued.

4.  Click **Functions** \> **Settlement**.

5.  In the **Settle open transactions** form, select the **Mark** check box on the line for each employee vendor invoice that you want to pay.
    

    > [!NOTE]
    > <P>To make a partial payment, you can enter the amount to pay in the <STRONG>Amount to settle</STRONG> field.</P>



6.  Close the **Settle open transactions** form.
    
    The payment line with information from the invoice now appears in the **Journal voucher** form. The amount on the payment line contains the amount from the vendor invoice that the company can pay the employee. The cash discount that applies to this payment, if any, is included.

7.  Click **Functions** \> **Generate payments**.

8.  Depending on the method of payment on the journal line, select either the payment method or the export format, and then select the bank account from which the payment is drawn.
    

    > [!NOTE]
    > <P>Click <STRONG>Inquiries</STRONG> &gt; <STRONG>Balance control</STRONG> to verify that the bank account contains adequate funds for the payment.</P>



9.  Click **Dialog**, fill in the fields, and then click **Document** to print the check.

10. Click **Validate** to validate the payment line, and then click **Post**.

If you want to pay the employee electronically, see [Create an electronic payment file for vendors](create-an-electronic-payment-file-for-vendors.md).

  


