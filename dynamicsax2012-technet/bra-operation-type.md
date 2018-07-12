---
title: (BRA) Operation type
TOCTitle: (BRA) Operation type
ms:assetid: 2f83aef2-18f5-4611-87ff-a714d1ba37ef
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ714190(v=AX.60)
ms:contentKeyID: 49651299
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (BRA) Operation type 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In releases before Microsoft Dynamics AX 2012 R2, sales operation types are created in the **Sales operation types** form and purchase operation types are created in the **Purchase operation types** form. The sales and purchase operation types are stored in two different tables. You can create sales and purchase operation types with the same identification code in the **Sales operation types** and **Purchase operation types** forms. For example, the operation type code 001 could designate both a sales operation type and purchase operation type.

In Microsoft Dynamics AX 2012 R2 and R3, the sales and purchase operation types are created in the **Operations type** form and both are stored in one table. As a result, each operation type must have a unique operation type code.

During upgrade, if sales and purchase operation types with the same identification code are available in the source system, you must specify new, unique identification codes and names for the operation types in Microsoft Dynamics AX 2012 R2 or R3. You can also update the type of operation for which the operation type is used.

Use the following procedure to update the identification codes for the sales and purchase operations types that have the same identification code.

1.  In the **Preprocessing upgrade checklist**, expand **Prepare application data for preprocessing**, and then click **Operation type** to open the **Resolve purchase and sales operation type ID conflicts** form.

2.  Select a sales or purchase operation type.

3.  In the **Sales/Purchase** field, select **Sales**, **Purchase**, or **Both** as the type of transaction for which the operation type is used.
    

    > [!NOTE]
    > <P>You cannot update the type of transaction for the operation types for which <STRONG>Both</STRONG> is selected in the <STRONG>Sales/Purchase</STRONG> field.</P>



4.  In the **New operation type ID** and **Name** fields, update the identification code and name of the operation type in Microsoft Dynamics AX 2012 R2 oe R3.

5.  After you update the information for all operation types, click **Set to ready for upgrade** to mark the checklist task as complete and to close this form.

## See also

[(BRA) Resolve purchase and sales operation type ID conflicts (form)](https://technet.microsoft.com/en-us/library/jj713626\(v=ax.60\))

  


