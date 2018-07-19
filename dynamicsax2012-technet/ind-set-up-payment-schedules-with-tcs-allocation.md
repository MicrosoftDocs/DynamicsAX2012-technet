---
title: (IND) Set up payment schedules with TCS allocation
TOCTitle: (IND) Set up payment schedules with TCS allocation
ms:assetid: 3c359be5-3c7a-4643-87c8-baa833e3a8cd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664636(v=AX.60)
ms:contentKeyID: 49385713
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up payment schedules with TCS allocation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Payment schedules**.

2.  Press CTRL+N to create a payment schedule on the **Overview** tab. Enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Payment schedules (form)" in the Applications and Business Processes Help.</P>



3.  Click the **General** tab and select the allocation payment method for the payment schedule in the **Allocation** field from the following options:
    
      - If you select the **Total** option in the **Allocation** field, the TCS allocation method for the payment schedule is displayed as **Total** in the **Withholding tax allocation** field.
    
      - If you select the **Fixed amount**, **Fixed quantity**, or **Specified** option in the **Allocation** field, the TCS allocation method for the payment schedule is displayed automatically as **Proportionally** in the **Withholding tax allocation** field.
    

    > [!NOTE]
    > <P>If the <STRONG>Withholding tax allocation</STRONG> field is displayed as <STRONG>Total</STRONG>, the payment installments are calculated, based on the total invoice amount including the TCS amount. If the <STRONG>Withholding tax allocation</STRONG> field is displayed as <STRONG>Proportionally</STRONG>, the payment installment amount lines are calculated, based on the total invoice amount, which is the invoice amount plus the TCS amount. For example, if the invoice amount is 100000 and the TCS amount is 20000, the installments are calculated, based on 120000 (100000+20000).</P>



4.  The fields that are available depend on the selection in the **Allocation** field. If you select the **Fixed amount** or **Fixed quantity** option in the **Allocation** field, you can enter the number of period intervals between due dates of each installment in the **Change** field.

5.  Enter the other required details.

  


