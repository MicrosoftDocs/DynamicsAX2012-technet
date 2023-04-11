---
title: Set up global address book parameters
TOCTitle: Set up global address book parameters
ms:assetid: d2e0ed31-fb63-4407-9ce3-9ffa52ff55e8
ms:mtpsurl: https://technet.microsoft.com/library/Gg731966(v=AX.60)
ms:contentKeyID: 35132908
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up global address book parameters 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you begin to work with the global address book or another address book in Microsoft Dynamics AX, you must set default values for your address books in the **Global address book parameters** form.

1.  Click **Organization administration** \> **Setup** \> **Global address book** \> **Global address book parameters**.

2.  Select the default sequence in which you want names to be displayed for **Person** type party records. For example, Last First Middle.

3.  Select the **Delete parties with no roles** check box to delete a party record from the address book when the record is deleted as an entity. For example, if this check box is selected, when you delete a customer record the record will also be deleted from the corresponding address book.

4.  Select the **Use duplicate check** check box to search for a duplicate record in the global address book when you create a new record.

5.  Select the **Display DUNS number on addresses** check box to display the Data Universal Numbering System (DUNS) number in a party record’s information.

6.  Select the **Check for unique DUNS number** check box to verify that the DUNS number entered on a new party record is unique.

7.  Select the default party record type. The default type can be either **Organization** or **Person**. If you do not want to specify a default party record type, select **None**.

8.  Select one of the following check boxes to set security policies:
    
      - **Secure by legal entity** – Restrict access to party records based on the legal entity that the user has access to.
    
      - **Secure by address book** – Restrict user access to party records based on the team that the user is assigned to.

9.  Select which user roles can have access to private address and contact information by using the **Add \>\>** button. You can use the **\<\< Remove** button to remove the privilege from a role.

  


