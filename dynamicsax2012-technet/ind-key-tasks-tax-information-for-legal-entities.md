---
title: '(IND) Key tasks: Tax information for legal entities'
TOCTitle: '(IND) Key tasks: Tax information for legal entities'
ms:assetid: b89741a5-f117-442c-8c5a-21038822e9f5
ms:mtpsurl: https://technet.microsoft.com/library/JJ664813(v=AX.60)
ms:contentKeyID: 49386145
author: tonyafehr
ms.date: 04/25/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.CustParameters
- Forms.OMLegalEntity
- Forms.LedgerParameters
- Forms.LogisticsPostalAddress
- Forms.TaxInfoManagementIN
audience: Application User
ms.search.region: India
---

# (IND) Key tasks: Tax information for legal entities 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Use the following information to set up tax information for a legal entity in India.


> [!NOTE]
> <P>The procedure for completing this task changed for cumulative update 6 or later for Microsoft Dynamics AX 2012 R2. The updated procedure also applies to AX 2012 R3. For more information, see the section later in this topic.</P>



## What do you want to do?

Select number sequence codes for tax-related documents and tasks

Enter address-specific tax information for a legal entity

Enter the tax registration number for the legal entity

Enter Permanent Account Number (PAN) information for a legal entity

Activate Tax Deduction at Source (TDS) and Tax Collection at Source (TCS) withholding

Enter withholding information for a legal entity

Find form help

Find related tasks

## Select number sequence codes for tax-related documents and tasks

Before you can select number sequences for references, you must set up number sequences. For more information, see [Set up number sequences](set-up-number-sequences.md).

### Select General ledger number sequence codes

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click **Number sequences**.

3.  Select a number sequence code for each of the following references:
    
      - **TDS and TCS adjustments**
    
      - **Withholding tax payment**
    
      - **VAT deferment**
    
      - **TDS and TCS reversal voucher**
    
      - **Tax setoff voucher**

### Select Accounts receivable number sequence codes

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click **Number sequences**.

3.  Select a number sequence code for the **Tax reimbursement document** reference.

Back to top

## Enter address-specific tax information for a legal entity

Some legal entities have multiple addresses associated with them and require different tax information or registration numbers for each address. Enter tax information or tax registration numbers for the address of a legal entity.


> [!NOTE]
> <P>Before you can enter tax registration numbers for a legal entity, you must set them up. For more information, see <A href="ind-set-up-tax-registration-numbers.md">(IND) Set up tax registration numbers</A>.</P>



### Specify a tax registration number for a legal entity

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**. Select a legal entity, and then click **Taxes**.

2.  Select the address that is associated with the tax registration number.

3.  Click **Tax registration**.

4.  Click **Add**.

5.  Select the registration type that is associated with the tax registration number. Tax registration types are maintained in the **Tax registration types** form.

6.  Enter the tax registration number for the selected address.

### Manage tax information records

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**. Select a legal entity, and then click **Taxes**.

2.  Select the location that is associated with the tax registration number.

3.  Click the **Tax information** FastTab.

4.  Click **Add** to open the **Manage tax information** form.

5.  Enter a name or description for the tax.

6.  Select the **Primary** check box if the tax information that you are entering is the primary tax information for the selected address.

7.  Enter or select the tax information in the remaining fields. For more information, see [(IND) Manage tax information (form)](https://technet.microsoft.com/library/jj664802\(v=ax.60\)).

### Specify the large taxpayer unit (LTU) code for a legal entity in Microsoft Dynamics AX 2012 R3 or cumulative update 6 or later for AX 2012 R2

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Select a legal entity.

3.  On the **Addresses** FastTab, select an address, and then click **More options** \> **Advanced**.

4.  In the **Manage addresses** form, on the **Tax information** FastTab, click **Add**.

5.  In the **Manage tax information** form, on the **Excise** FastTab, in the **Large taxpayer unit (LTU) code** field, enter the LTU code for the legal entity. The LTU code is seven alphanumeric characters. The LTU code is displayed on the customer invoices that are generated by the legal entity.

Back to top

## Enter the tax registration number for the legal entity

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Select a legal entity to enter a tax registration number for.

3.  Click **Tax registration**.

4.  Enter the tax registration number for the legal entity.

Back to top

## Enter Permanent Account Number (PAN) information for a legal entity

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Select a legal entity to enter PAN information for.

3.  Click **Tax information** and enter the following information:
    
      - **Status**
    
      - **Permanent account number**
    
      - **Assessing officer number**
    
      - **Circle number**
    
      - **Ward number**
    
    For descriptions of these fields, see [(IND) Legal entities (modified form)](https://technet.microsoft.com/library/jj664569\(v=ax.60\)).

Back to top

## Activate Tax Deduction at Source (TDS) and Tax Collection at Source (TCS) withholding

Before you can specify withholding information for a legal entity, you must enable TDS and TCS withholding functionality.

### Activate TDS

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click **Direct taxes**.

3.  Select the **Activate TDS** check box.

4.  Select the **Invoice** and **Payment** check boxes to enable calculation and collection of TDS for invoices and payments.

### Activate TCS

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click **Direct taxes**.

3.  Select the **Activate TCS** check box.

4.  Select the **Invoice** and **Payment** check boxes to enable calculation and collection of TCS for invoices and payments.

Back to top

## Enter withholding information for a legal entity

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Click **Tax information** and enter the following information:
    
      - **Type of deduction**
    
      - **PAO code**
    
      - **DDO code**
    
      - **PAO registration number**
    
      - **Calculation expression**
    
      - **Ministry details**
    
      - **Ministry code**
    
      - **State code**
    
    For descriptions of these fields, see [(IND) Legal entities (modified form)](https://technet.microsoft.com/library/jj664569\(v=ax.60\)).

Back to top

## Find form help

[(IND) Legal entities (modified form)](https://technet.microsoft.com/library/jj664569\(v=ax.60\))

[(IND) Manage addresses (modified form)](https://technet.microsoft.com/library/jj664593\(v=ax.60\))

[(IND) Manage tax information (form)](https://technet.microsoft.com/library/jj664802\(v=ax.60\))

## Find related tasks

[(IND) Set up tax registration numbers](ind-set-up-tax-registration-numbers.md)

  


