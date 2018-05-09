---
title: (RUS) Create a transport tax declaration
TOCTitle: (RUS) Create a transport tax declaration
ms:assetid: d57c2f41-966e-4c76-98dc-6e1445e9e010
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711647(v=AX.60)
ms:contentKeyID: 49387971
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- declaration
- Russia
- transport tax
---

# (RUS) Create a transport tax declaration 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to create a transport tax declaration. You must calculate and approve the transport tax registers before you can generate an accurate transport tax declaration. For more information, see [(RUS) Calculate transport tax registers](rus-calculate-transport-tax-registers.md).

1.  Click **Fixed assets (Russia)** \> **Journals** \> **Tax register journal**.

2.  Select a journal, and then click **Print** \> **Transport tax** if the tax is calculated for a year.

3.  In the **Correction number** field, enter the sequence number of the correction document.

4.  In the **By place** field, select the location for the declaration, from the following options:
    
      - **of accounting of the first-rate taxpayer**
    
      - **of accounting of the assignee, who is the first-rate taxpayer**
    
      - **vehicle location**

5.  In the **Representative** field, select an authorized representative in the list of employees.

6.  Select the **Reorganization (liquidation)** check box to indicate that the reports that are prepared are the final reports before the company is restructured.

7.  In the **Reorganization or liquidation code** field, select the reorganization or liquidation code from the following options:
    
      - **Transformation**
    
      - **Merging**
    
      - **Splitting**
    
      - **Joining**
    
      - **Splitting with simultaneous rejoining**
    
      - **Liquidation**

8.  In the **INN** field, enter the identification number of the taxpayer.

9.  In the **Registry reason code** field, enter the registry reason code.

10. Select the **Export declaration** check box to export the declaration as a Microsoft Excel file.

11. In the **Template** field, select the document template that is used to export the transport tax declaration.

12. In the **Print declaration for** grid, specify the legal entities for which the transport tax declaration is generated.

13. In the **Select Department** field group, specify the department codes. The declaration is printed based on your selections. A separate declaration is generated for each department code.

14. Click **Select all** to set the parameter for all department codes.
    

    > [!NOTE]
    > <P>Click <STRONG>Deselect all</STRONG> to remove the parameter for all department codes.</P>



15. Click **OK** to export the transport tax declaration.

## See also

[(RUS) Print transport tax declaration (form)](https://technet.microsoft.com/en-us/library/jj711516\(v=ax.60\))

[(RUS) Create a ledger journal of transport tax transactions](rus-create-a-ledger-journal-of-transport-tax-transactions.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

