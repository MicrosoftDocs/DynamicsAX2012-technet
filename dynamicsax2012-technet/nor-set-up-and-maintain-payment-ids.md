---
title: (NOR) Set up and maintain payment IDs
TOCTitle: (NOR) Set up and maintain payment IDs
ms:assetid: 3397b283-32c8-4cf1-95be-306e27acfffb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231083(v=AX.60)
ms:contentKeyID: 36056542
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (NOR) Set up and maintain payment IDs 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A payment identification (ID) is a unique identifier for customer payments that are settled electronically. It can be divided into different parts, such as the customer account number, invoice number, prefix, suffix, and external reference. When you receive a payment from a customer, the payment ID identifies the payment transaction for a sales invoice that is received from a bank.

## Set up payment IDs

1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Payment ID**.

2.  Press CTRL+N to create a new payment ID.

3.  In the **Payment ID type** field, enter a code for the payment ID, and then in the **Name** field, enter a descriptive name for the payment ID.

4.  In the **Payment ID length** field, enter the length of the payment ID.

5.  In the **Modulo** field, select the modulo check method to calculate the check number. The last digit of a payment ID is reserved for the check number to verify that the payment ID is valid. The following options are available:
    
      - **Modulo 10** – The total length of the payment ID is divided by 10. The remainder is the check number.
    
      - **Modulo 11** – The total length of the payment ID is divided by 11. The remainder is the check number.
    
      - **(None)** – No check number is calculated.

6.  In the **Account from position** field, enter the starting position for the customer or vendor account number in the payment ID.

7.  In the **Account to position** field, enter the ending position for the customer or vendor account number in the payment ID.

8.  In the **Invoice from position** field, enter the starting position for the invoice number in the payment ID.

9.  In the **Invoice to position** field, enter the ending position for the invoice number in the payment ID.

10. Click the **General** tab, and then in the **Prefix** field group, specify the prefix information for the payment ID.

11. In the **Suffix** field group, specify the suffix information for the payment ID.
    

    > [!NOTE]
    > <P>Prefix and suffix text values are not included when the check number is calculated.</P>



12. In the **External reference** field group, enter the starting and ending positions for the external reference of the payment ID. The external reference is the account number of a vendor who is also a customer.

13. In the **Text** field group, specify the prefix text value and suffix text value for the payment ID.

14. Click the **Setup** tab, and then select the **Blank payment ID** check box to issue a payment slip without the payment ID.
    

    > [!NOTE]
    > <P>You can preview the selected payment ID in the <STRONG>Payment ID test</STRONG> field.</P>



## Attach the payment ID at various levels

You can attach the payment ID at various levels. Use the following order of priority when you assign a payment ID to a transaction:

1.  **Customers** form. Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Click the **Payment defaults** FastTab \> **Payment ID type**.

2.  **Methods of payment - customers** form. Click **Accounts receivable** \> **Setup** \> **Payment** \> **Methods of payment**. Click the **Payment control** FastTab \> **Payment ID type**.

3.  **Customer groups** form. Click **Accounts receivable** \> **Setup** \> **Customers** \> **Customer groups**.

4.  **Number sequences** form. Click **Organization administration** \> **Common** \> **Number sequences** \> **Number sequences**.

5.  **eGiro parameters** form. Click **Accounts receivable** \> **Setup** \> **Payment** \> **eGiro** \> **eGiro parameters**.

## Update the payment ID for invoices

1.  Click **Accounts receivable** \> **Periodic** \> **Update invoice payment ID**.

2.  In the **Update payment ID** field group, the following check boxes are displayed:
    
      - **Update invoice payment ID** – Select this check box to update the payment ID for all sales invoices that do not have a value in the **Payment ID** field.
    
      - **Update interest note payment ID** – Select this check box to update the payment ID for interest notes.
    
      - **Update collection letter payment ID** – Select this check box to update the payment ID for collection letters.
    
      - **Update project invoice payment ID** – Select this check box to update the payment ID for project invoices.
    

    > [!NOTE]
    > <P>Select the <STRONG>Delete payment ID</STRONG> check box to delete the payment ID information from all forms.</P>



## View the payment ID for transactions

You can view the payment ID for a transaction in the following locations:

  - Click **Accounts receivable** \> **Setup** \> **Payment** \> **Payment ID**.

  - Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**. Double-click an invoice, and then in the action pane, click **Header view**, and then click **Invoice journal**.

  - **Navigation Path Not Found**

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

