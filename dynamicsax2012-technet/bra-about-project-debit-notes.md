---
title: (BRA) About project debit notes
TOCTitle: (BRA) About project debit notes
ms:assetid: ac518118-9c26-424a-b278-dfd4cd11c00f
ms:mtpsurl: https://technet.microsoft.com/library/JJ916624(v=AX.60)
ms:contentKeyID: 50934015
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- project debit note
- debit note
- BR - 00025
audience: Application User
ms.search.region: Brazil
---

# (BRA) About project debit notes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can generate a debit note and get project expenses reimbursed by the customer. You can generate debit notes only for projects that have a transaction type of **Expense**. You can generate a project debit note by using the project debit note proposal workflow. Before you can generate a debit note, you must post an expense journal for the project.

You can cancel a debit note only when the period that the debit note is posted in is open. You can cancel a debit note that is settled if you select the **Cancel settled debit note** check box in the **Invoice** area in the **Project management and accounting parameters** form. When you cancel a debit note, the related transaction that is inclusive of taxes, if any, is reversed. The debit note proposal status is updated to **Debit note canceled** on the **Project debit note proposals** list page. After you cancel a debit note, the related expense journal transaction is available to create another debit note.

## See also

[(BRA) Set up number sequences for project debit notes](bra-set-up-number-sequences-for-project-debit-notes.md)

[(BRA) Set up a line property](bra-set-up-a-line-property.md)

  


