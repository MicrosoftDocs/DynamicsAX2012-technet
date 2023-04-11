---
title: Unapprove a formula
TOCTitle: Unapprove a formula
ms:assetid: ef25fde2-1d46-4cb0-aff6-d85cab811509
ms:mtpsurl: https://technet.microsoft.com/library/Hh328612(v=AX.60)
ms:contentKeyID: 36688041
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Unapprove a formula 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to remove an approval status from a formula.


> [!NOTE]
> <P>If the <STRONG>Block removal of approval</STRONG> check box is selected on the <STRONG>General</STRONG> tab in the <STRONG>Production control parameters</STRONG> form, you cannot change the approval status of an approved formula.</P>



1.  Click **Inventory and warehouse management** \> **Common** \> **Formula**.

2.  Select the formula to be unapproved.

3.  To unapprove the formula, click the **Approve formula** button.

4.  From the **Approved by** list, select the worker who is removing the approval status from the formula.

5.  Select the **Remove approval** check box.

6.  Click **OK**.
    

    > [!NOTE]
    > <P><SPAN id=q></SPAN>If a user is set up to require electronic signature, a <STRONG>Signature</STRONG> form is displayed after you clear the <STRONG>Approval</STRONG> status. You must be authorized to sign electronically and the certificate must be successfully validated for the change to be committed. If your signature cannot be authenticated, the request to remove approval is denied and the change that initiated it is returned to its original state.</P>



## See also

[Formula (form)](https://technet.microsoft.com/library/hh328668\(v=ax.60\))

[Production control parameters (form)](https://technet.microsoft.com/library/aa498700\(v=ax.60\))

  


