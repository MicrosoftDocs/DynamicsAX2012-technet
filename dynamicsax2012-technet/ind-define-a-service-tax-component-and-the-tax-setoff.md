---
title: (IND) Define a service tax component and the tax setoff
TOCTitle: (IND) Define a service tax component and the tax setoff
ms:assetid: 1c67cc44-419c-4c5a-a240-0305954f3453
ms:mtpsurl: https://technet.microsoft.com/library/JJ664533(v=AX.60)
ms:contentKeyID: 49385613
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Define a service tax component and the tax setoff 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can define the tax components for service tax and then offset the amounts of those components in the service tax payable account. The amounts of those components are also included in the service tax recoverable account.

You can offset the amounts of the service tax components that include excise tax in the service tax payable account.


> [!NOTE]
> <P>In the <STRONG>Tax setoff rule</STRONG> form, you cannot select the same setoff component more than one time for a tax component.</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Tax components**.

2.  In the **Tax type** filter, select **Service tax**.

3.  Click **New** to create a new line, and then enter the tax component. For example, enter Service tax, E-cess, or She-cess.

4.  Enter a description for the tax component.

5.  Click **Tax setoff rule** to create or update tax setoff rules in the **Tax setoff rule** form.

6.  In the **Column** field, view the order of priority for the tax component that is used to offset the original service tax component.

7.  In the **Setoff component** field, select a tax component that is offset against the service tax component.

8.  Use the **Up** and **Down** buttons to change the order of priority of the setoff components.
    
      - Click the **Up** button to move the record up by one position and therefore increase the priority of the tax component by one.
    
      - Click the **Down** button to move the record down by one position and therefore decrease the priority of the tax component by one.

9.  Close the **Tax setoff rule** form and the **Tax components** form.

## See also

[(IND) Tax setoff rule (form)](https://technet.microsoft.com/library/jj677818\(v=ax.60\))

[(IND) Tax components (form)](https://technet.microsoft.com/library/jj664734\(v=ax.60\))

  


