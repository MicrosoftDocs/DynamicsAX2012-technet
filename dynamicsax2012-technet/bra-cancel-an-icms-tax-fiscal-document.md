---
title: (BRA) Cancel an ICMS tax fiscal document
TOCTitle: (BRA) Cancel an ICMS tax fiscal document
ms:assetid: 26df34c8-8f96-4657-bb15-be01b1a585c2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710438(v=AX.60)
ms:contentKeyID: 49384330
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- ICMS
- ICMS tax document
- tax document
---

# (BRA) Cancel an ICMS tax fiscal document [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can cancel a posted tax fiscal document that is incorrect. When you cancel a tax fiscal document, a tax fiscal document with a negative amount is created. When you post the negative tax fiscal document, the original tax fiscal document is marked as canceled, and the settlements are reversed.

1.  Click **General ledger** \> **Journals** \> **All tax fiscal documents**.

2.  Double-click the tax fiscal document to cancel.

3.  In the **Tax fiscal document** form, on the **Action Pane**, click **Cancel fiscal document**.

4.  In the **Reason code** field, select the code for the reason to cancel the tax fiscal document.

5.  In the **Comments** field, enter the reason to cancel the tax fiscal document.

6.  Click **Create corrected invoice** to create a tax fiscal document with a negative amount in the **Tax fiscal document** form.

7.  In the **Tax fiscal document** form, on the **Action Pane**, click **Edit**.

8.  Click the **Tax fiscal document header** FastTab, and then in the **Date** field, specify the invoice date for the tax fiscal document with a negative amount.

9.  On the **Action Pane**, click **Post** to open the **Post fiscal document** form.

10. Click **OK** to post the tax fiscal document with a negative amount. The original tax fiscal document is marked as canceled, and the settlements are reversed.

## See also

[(BRA) About ICMS tax fiscal documents](bra-about-icms-tax-fiscal-documents.md)

[(BRA) Create and post an ICMS tax fiscal document](bra-create-and-post-an-icms-tax-fiscal-document.md)

[(BRA) Tax fiscal document (form)](https://technet.microsoft.com/en-us/library/jj710428\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

