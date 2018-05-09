---
title: (BRA) Set up adjustment codes to use to adjust ICMS amounts
TOCTitle: (BRA) Set up adjustment codes to use to adjust ICMS amounts
ms:assetid: d274cace-0e98-41c3-bd93-732eacbc8747
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn305885(v=AX.60)
ms:contentKeyID: 54912990
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.FBGeneralAdjustmentCodeICMS_BR
- MsDynAx060.Forms.FBGeneralAdjustmentCodeICMS_BR
---

# (BRA) Set up adjustment codes to use to adjust ICMS amounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In a Sistema Publico de Escrituração Digital (SPED) fiscal text file, record E111 includes information about adjustments of Imposto sobre Circulação de Mercadorias e Serviços (ICMS) taxes that have been applied in the period that is covered by the SPED fiscal text file. Before you can adjust ICMS taxes, you must specify the adjustment codes that are determined by the Brazilian government depending on the adjustment criteria. This topic explains how to set up adjustment codes to be applied for ICMS and ICMS tributary substitution (ICMS-ST) taxes. You do this by using the **ICMS and ICMS-ST adjustment codes table** form. For information about how to enter ICMS and ICMS-ST tax adjustment transactions, see [(BRA) Assess, pay, declare, and adjust ICMS and ICMS-ST taxes](bra-assess-pay-declare-and-adjust-icms-and-icms-st-taxes.md).


> [!NOTE]
> <P>The procedure for completing this task has changed for Microsoft Dynamics AX 2012 R3. For information that is specific to Microsoft Dynamics AX 2012 R3, see the section later in this topic.</P>



## Set up adjustment codes for ICMS tax

1.  Click **Fiscal books** \> **Setup** \> **Tax adjustment codes** \> **ICMS and ICMS-ST adjustment codes table**.

2.  In the **ICMS and ICMS-ST adjustment codes table** form, enter an adjustment code in the **Identification** field and a description of the adjustment code.

3.  Select a state.

4.  Select a tax type from the following options:
    
      - **ICMS** – The adjustment code is used for federal ICMS tax.
    
      - **ICMS-ST** – The adjustment code is used for federal ICMS-ST tax.

5.  Select a classification from the following options:
    
      - **0: Other debits**
    
      - **1: Credits reversal**
    
      - **2: Other credits**
    
      - **3: Debits reversal**
    
      - **4: Deductions of tax balance**
    
      - **5: Specials debits**
    
      - **9: Information**

6.  Enter an occurrence code.
    
    The **Adjustment code** field is filled in automatically, based on the entries in the other fields in this form.

7.  In the **Valid from** and **Valid to** fields, enter the first and last dates that the adjustment codes are applicable for.

8.  In the **GIA** field group, select an occurrence code.

9.  On the **Payment** FastTab, select the **Other debit** check box if you want to create an additional tax adjustment payment that is not included in the periodic payment.

10. On the **Posting** FastTab, in the **Company accounts** field, select the legal entity where the tax adjustment transactions will be posted.

11. In the **Sales tax code** field, select the tax code that will be used to select the accounts receivable or accounts payable account. The account that is selected depends on whether the tax adjustment is a debit or credit. For more information, see [Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md).

12. Select the main account that will be used to post the revenue or expense part of the adjustment transaction.

13. To create another adjustment code, click **New**, and then repeat steps 2 through 12.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

