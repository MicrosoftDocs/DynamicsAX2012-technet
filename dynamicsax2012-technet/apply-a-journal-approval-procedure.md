---
title: Apply a journal approval procedure
TOCTitle: Apply a journal approval procedure
ms:assetid: 0ed8c6d3-b90a-4e40-a84f-e2b057b6fba7
ms:mtpsurl: https://technet.microsoft.com/library/Aa496413(v=AX.60)
ms:contentKeyID: 36811394
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- journal
- journal approval
- journal line
- approval procedure
audience: Application User
ms.search.region: Global
---

# Apply a journal approval procedure 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to apply a journal approval procedure to an hour journal. Journal approval procedures can be used to approve timesheet transactions that are entered by workers.

Applying a journal approval procedure involves attaching an approval procedure to a journal name, applying the journal approval procedure to a journal, and then approving the journal lines.


> [!NOTE]
> <P>Journal approval procedures are created in the <STRONG>Journal approval</STRONG> form. For more information, see <A href="https://technet.microsoft.com/library/aa499141(v=ax.60)">Journal approval (form)</A>.</P>



1.  Click **Project management and accounting** \> **Setup** \> **Journals** \> **Journal names**.

2.  Create or select a journal name.
    

    > [!NOTE]
    > <P>Journal approval procedures apply only to hour journals. Ensure that <STRONG>Hour</STRONG> is selected in the <STRONG>Journal type</STRONG> field.</P>



3.  In the **Approve** field, select an approval procedure.

4.  Click **Project management and accounting** \> **Journals** \> **Hour**.

5.  In the **Journal** form, create or select an hour journal line.

6.  On the **General** tab, in the **Approve** field, select a journal approval procedure.

7.  Click the **Approval** button to select an approval status.


> [!NOTE]
> <P>Journal lines can only be approved in a batch per journal. They cannot be approved line by line.</P>



## See also

[About journal approval procedures](about-journal-approval-procedures.md)

[Create a journal approval procedure](create-a-journal-approval-procedure.md)

[Set up project journal names](set-up-project-journal-options.md)

[Journal names (form)](https://technet.microsoft.com/library/aa617509\(v=ax.60\))

  


