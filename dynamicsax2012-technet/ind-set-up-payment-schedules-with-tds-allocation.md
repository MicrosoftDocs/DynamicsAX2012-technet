---
title: (IND) Set up payment schedules with TDS allocation
TOCTitle: (IND) Set up payment schedules with TDS allocation
ms:assetid: a7bf91e8-7ba3-43f0-848f-164ff860b0eb
ms:mtpsurl: https://technet.microsoft.com/library/JJ664771(v=AX.60)
ms:contentKeyID: 49386118
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up payment schedules with TDS allocation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Payment schedules**.

2.  Press CTRL+N to create a payment schedule on the **Overview** tab. Enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Payment schedules (form)" in the Applications and Business Processes Help.</P>



3.  Click the **General** tab and select the allocation payment method for the payment schedule in the **Allocation** field.
    
      - If you select the **Total** option in the **Allocation** field, the TDS allocation method for the payment schedule is displayed as **Total** in the **Withholding tax allocation** field.
    
      - If you select the **Fixed amount**, **Fixed quantity**, or **Specified** option in the **Allocation** field, the TDS allocation method for the payment schedule is displayed automatically as **Proportionally** in the **Withholding tax allocation** field.
    

    > [!NOTE]
    > <P>If the <STRONG>Withholding tax allocation</STRONG> field is displayed as <STRONG>Total</STRONG>, the payment installments are calculated, based on the gross amount including the TDS amount. If the <STRONG>Withholding tax allocation</STRONG> field is displayed as <STRONG>Proportionally</STRONG>, the payment installments are calculated, based on the net invoice amount after deducting the TDS amount.</P>



4.  The fields that are available depend on the selection in the **Allocation** field. If you select the **Fixed amount** or **Fixed quantity** option in the **Allocation** field, you can enter the number of period intervals between due dates of each installment in the **Change** field.

5.  Enter the other required details.

6.  Press CTRL+S or close the form.

  


