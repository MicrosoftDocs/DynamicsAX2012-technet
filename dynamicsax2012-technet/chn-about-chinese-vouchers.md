---
title: (CHN) About Chinese vouchers
TOCTitle: (CHN) About Chinese vouchers
ms:assetid: 2a671285-89fb-4f82-a24d-cf26a09887c1
ms:mtpsurl: https://technet.microsoft.com/library/JJ664018(v=AX.60)
ms:contentKeyID: 49384602
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- voucher
- Chinese
- (CHN)
- China
- CN - 00009
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) About Chinese vouchers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must create a voucher document for every posted journal. You can print a paper voucher and a posted journal. Based on your requirements, you can use the **Voucher type setup wizard** to set up the commonly used **Get**, **Pay** and **Transfer** voucher types, or you can create new voucher types in the **Voucher type setup** form. For more information, see [(CHN) Voucher type setup wizard (form)](https://technet.microsoft.com/library/jj664054\(v=ax.60\)). You can use booking vouchers to enter and group transactions into the **Receipt voucher**, **Payment voucher**, or **Transfer voucher**. A continuous number sequence beginning from the first day of every monthly period should be assigned to each voucher type. You can define a Chinese voucher type for ledger accounts only.

You can assign the voucher types to specific ledger accounts, and then define validation rules in the **Voucher type setup** form for posting voucher transactions to the specified ledger accounts. During voucher posting, a validity check is run based on the rules that are specified in the **Voucher type setup** form. A message appears if the voucher type that is selected for the chosen ledger account is incorrect. For example, if you select a ledger account of credit type for the voucher type **Get**, for which you have defined the validation rule that the ledger account must be a debit account, then a message appears that states that the Chinese voucher type is not valid. You can make changes accordingly, and can post the voucher again.

You can create voucher transactions using the **Simple** or **Advanced** method in the **General journal** form. You can create journal vouchers with a single voucher type by using the **Simple** method. When you use the **Simple** method, the voucher type that is selected on all of the journal lines should be the same. The **Advanced** method allows you to create multiple journal lines with different voucher types.

The Chinese voucher number should be sequential with no gaps in the fiscal period. You can run a batch process to verify whether there are any gaps in the Chinese voucher numbers. The batch process verifies the transaction dates, and then renumbers the vouchers for continuity. For tracking purposes, you can generate the **Chinese voucher continuity check report**. This report displays the history of renumbered Chinese vouchers. For more information, see [(CHN) Generate and print a Chinese voucher](chn-generate-and-print-a-chinese-voucher.md) and [(CHN) Voucher continuity check log (form)](https://technet.microsoft.com/library/jj664113\(v=ax.60\)).

You can print a Chinese voucher before or after posting the voucher. The printed voucher displays the information, such as the history of renumbered Chinese vouchers and tax information before or after posting the voucher. You can compare the printed information to verify that it is the same information before and after posting, and that the information is correct. For example, if you select sales tax in a journal voucher, the final voucher information includes the sales tax, which could be different from what was part of the journal. Therefore, it is required that the print result be accurate and the same as the result that is generated after the final posting. Therefore, you can print a Chinese voucher with the correct information from both the journal voucher and the voucher transactions. You can also print Chinese vouchers in a batch after filtering the information by Chinese voucher type and by fiscal period.

## See also

[(CHN) Copy and reverse a voucher](chn-copy-and-reverse-a-voucher.md)

[(CHN) Simple voucher (form)](https://technet.microsoft.com/library/jj664134\(v=ax.60\))

[(CHN) Chinese vouchers (form)](https://technet.microsoft.com/library/jj664151\(v=ax.60\))

[(CHN) Set up a Chinese voucher system](chn-set-up-a-chinese-voucher-system.md)

[(CHN) Voucher transactions (modified form)](https://technet.microsoft.com/library/jj664127\(v=ax.60\))

  


