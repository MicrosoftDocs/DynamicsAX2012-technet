---
title: (RUS) Set up an inventory owner for bailment
TOCTitle: (RUS) Set up an inventory owner for bailment
ms:assetid: 8c2551e1-0edd-4ca4-af55-f3558e435ac1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733255(v=AX.60)
ms:contentKeyID: 49685222
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up an inventory owner for bailment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Inventory owner** form to set up an inventory owner, or bailor, for the bailment process. A vendor, or bailee, can store items that belong to multiple owners. Therefore, you must set up an inventory owner for a vendor. You can set up an identification number for an inventory owner by using the **Accounts payable parameters** form or the **Inventory and warehouse management parameters** form. For more information, see [Accounts payable parameters (form)](https://technet.microsoft.com/en-us/library/aa596348\(v=ax.60\)) and [Inventory and warehouse management parameters (form)](https://technet.microsoft.com/en-us/library/aa587658\(v=ax.60\)).

1.  Click **Procurement and sourcing** \> **Setup** \> **Procurement and sourcing parameters**.

2.  In the **General** area, in the **Owner** field, select an inventory owner.

3.  In the **Owner ID initialization** field, select the method to use to set up an identification number for the inventory owner. The following options are available:
    
      - **Do not initialize** – The identification number must be set up manually.
    
      - **Vendor account/agreement** – The identification number must contain the vendor account number or contract number.
    
      - **Number sequence code** – A number sequence must be set up for the identification number.
        

        > [!NOTE]
        > <P>If you select <STRONG>Number sequence code</STRONG>, click the <STRONG>Number sequences</STRONG> link in the <STRONG>Inventory and warehouse management parameters</STRONG> form to set up a number sequence code for the <STRONG>Owner</STRONG> reference type.</P>



4.  Close the form.

5.  Click **Inventory management** \> **Inquiries** \> **Dimensions** \> **Owner**.

6.  In the **Owner** field, enter the name of the inventory owner.

7.  In the **Account type** field, select **Customer** or **Vendor**.

8.  In the **Account** field, select a customer account or a vendor account.

9.  In the **Agreement ID** field, select the agreement registration number for bailment.

## See also

[Procurement and sourcing parameters (form)](https://technet.microsoft.com/en-us/library/hh208706\(v=ax.60\))

[(RUS) Inventory owner (form)](https://technet.microsoft.com/en-us/library/jj678549\(v=ax.60\))

  


