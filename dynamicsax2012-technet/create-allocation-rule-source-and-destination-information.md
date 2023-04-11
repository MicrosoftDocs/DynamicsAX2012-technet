---
title: Create allocation rule source and destination information
TOCTitle: Create allocation rule source and destination information
ms:assetid: 0c51afe5-e81b-4038-8d42-d258bbd95655
ms:mtpsurl: https://technet.microsoft.com/library/Gg230897(v=AX.60)
ms:contentKeyID: 36676366
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create allocation rule source and destination information 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Ledger allocation rule source** form to define the source information for the allocation rule.

Use the **Ledger allocation rule destination** form to define the destination information for the allocation rule.

## Create allocation rule source information

1.  Click **General ledger** \> **Setup** \> **Posting** \> **Ledger allocation rule**.

2.  Click **Source** to open the **Ledger allocation rule source** form.
    

    > [!TIP]
    > <P>If you are creating a new allocation rule, you must select an allocation method on the <STRONG>General</STRONG> tab before you can click <STRONG>Source</STRONG>.</P>



3.  Click **New** to create a source line.

4.  Select to allocate from an account or from an account and dimension combination.

5.  If you selected **Financial dimension** in the **Field setting** field, select a financial dimension.

6.  Enter the account or dimension source criteria information to allocate from. You can use wildcard characters.
    
    For example, suppose that you want to allocate a utility expense, such as telephone and fax costs. The chart of accounts is set up so that a ledger account that starts with 61 indicates the account where utilities expenses are posted. You could define the source criteria as one of the following.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Wildcard characters</p></th>
    <th><p>Example entry</p></th>
    <th><p>What is displayed</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>ALL</p></td>
    <td><p>61*</p></td>
    <td><p>All accounts or financial dimensions that begin with 61</p></td>
    </tr>
    <tr class="even">
    <td><p>RANGE</p></td>
    <td><p>6100..6110</p></td>
    <td><p>All accounts or financial dimensions that include, or are between, 6100 and 6110</p></td>
    </tr>
    <tr class="odd">
    <td><p>LIST</p></td>
    <td><p>6100, 6110</p></td>
    <td><p>The accounts or financial dimensions that are numbered 6100 and 6110</p></td>
    </tr>
    <tr class="even">
    <td><p>BLANK</p></td>
    <td><p></p></td>
    <td><p>All accounts and financial dimensions</p></td>
    </tr>
    </tbody>
    </table>


## Create allocation rule destination information

1.  Click **General ledger** \> **Setup** \> **Posting** \> **Ledger allocation rule**.

2.  Click **Destination** to open the **Ledger allocation rule destination** form.
    

    > [!TIP]
    > <P>If you are creating a new allocation rule, you must select an allocation method on the <STRONG>General</STRONG> tab before you can click <STRONG>Destination</STRONG>.</P>



3.  Depending on the allocation method that is selected in the **Ledger allocation rule** form, enter or select the following information.
    
      - If the allocation method is **Basis**, select the basis ID to associate to the destination line.
    
      - If the allocation method is **Fixed weight**, enter the fixed weight to assign to each destination line.
    
      - If the allocation method is **Fixed percentage**, enter the fixed percentage to assign to each destination line.

4.  If this rule is an intercompany rule, select the legal entity to allocate to.

5.  Select the account to allocate to.

6.  Select a financial dimension to allocate to.

## See also

[Create an allocation rule](create-an-allocation-rule.md)

[Ledger elimination rule (form)](https://technet.microsoft.com/library/hh209563\(v=ax.60\))

[Ledger allocation basis (form)](https://technet.microsoft.com/library/ff395367\(v=ax.60\))

  


