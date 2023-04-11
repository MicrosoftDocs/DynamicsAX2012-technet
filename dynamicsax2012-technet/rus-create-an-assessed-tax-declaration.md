---
title: (RUS) Create an assessed tax declaration
TOCTitle: (RUS) Create an assessed tax declaration
ms:assetid: 09c73f3b-db8f-4e69-bf0e-285345d4df1c
ms:mtpsurl: https://technet.microsoft.com/library/JJ711371(v=AX.60)
ms:contentKeyID: 49387190
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (RUS)
- Russia
- assessed tax
audience: Application User
ms.search.region: Russia
---

# (RUS) Create an assessed tax declaration 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to create an assessed tax declaration. An assessed tax declaration is based on a tax register journal. You must calculate and approve the assessed tax registers before you can generate an assessed tax declaration that is accurate. For more information, see [(RUS) Calculate assessed tax registers](rus-calculate-assessed-tax-registers.md).

1.  Click **Fixed assets (Russia)** \> **Journals** \> **Tax register journal**.

2.  Select a journal, and then click **Print** \> **Assessed tax** if the tax is calculated for a year.
    
    –or–
    
    Click **Print** \> **Advance payment** if the tax is calculated for other periods, such as monthly, quarterly, or half-yearly.

3.  In the **Correction number** field, enter the number of documents that correct previous tax declarations.

4.  In the **By place** field, select the location for the declaration, from the following options:
    
      - **of accounting of the first-rate taxpayer**
    
      - **of Russian organization being**
    
      - **of detached department being**
    
      - **of accounting of foreign organization**
    
      - **of immovable property object being**
    
      - **of accounting of the assignee, who is the first-rate taxpayer**
    
      - **of location of the assignee, who is not a first-rate taxpayer**

5.  In the **Representative** field, select an authorized representative in the list of company employees.

6.  Select the **Reorganization (liquidation)** check box to indicate that the prepared reports are the final reports before the company is restructured.

7.  In the **Reorganization or liquidation code** field, select the code from the following options:
    
      - **Transformation**
    
      - **Merging**
    
      - **Splitting**
    
      - **Joining**
    
      - **Splitting with simultaneous rejoining**
    
      - **Liquidation**

8.  In the **INN** field, enter the identification number of the tax payer.

9.  In the **Registry reason code** field, enter the code for the registry reason.

10. Select the **Export declaration** check box to export the declaration as a Microsoft Excel file.

11. In the **Template** field, select the document template that is used to export the assessed tax declaration.

12. In the **Print declaration for** grid, specify the legal entities that the assessed tax declaration is generated for.

13. In the **Select RCOAD** field group, specify the Russian Classification of Objects of Administrative Division (RCOAD) codes, based on the declaration that is printed. A separate declaration is generated for each RCOAD code.

14. Click **Select all** to set the parameter for all RCOAD codes.
    

    > [!NOTE]
    > <P>Click <STRONG>Deselect all</STRONG> to remove the parameter for all RCOAD codes.</P>



15. Click **OK** to export the assessed tax declaration.

## See also

[(RUS) Print assessed tax declaration (form)](https://technet.microsoft.com/library/jj711475\(v=ax.60\))

[(RUS) Create a ledger journal of assessed tax transactions](rus-create-a-ledger-journal-of-assessed-tax-transactions.md)

  


