---
title: (IND) Split a DFIA license
TOCTitle: (IND) Split a DFIA license
ms:assetid: afc41858-4f2e-463f-a632-528a4090d60d
ms:mtpsurl: https://technet.microsoft.com/library/JJ664800(v=AX.60)
ms:contentKeyID: 49386130
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Split
- (IND)
- India
- DFIA license
audience: Application User
ms.search.region: India
---

# (IND) Split a DFIA license 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can split a Duty Free Import Authorization (DFIA) if all export obligations have been met for the authorization. After you submit the appropriate documents and the customs authority approves the split and issues a new authorization number, you can use or sell the new authorization.

1.  Click **General ledger** \> **Common** \> **EXIM Authorization schemes**.

2.  On the **Action Pane**, in the **New** group, click **EXIM Authorization schemes**.

3.  In the **EXIM Authorization schemes** form, in the **Authorization type** field, select **DFIA**. All authorizations that were created for the DFIA authorization type appear on the **Overview** FastTab.

4.  Select an authorization that has a status of **Approved**.

5.  Click **Functions**, and then click **Split**. In the **Split details** form, the selected authorization appears in the **Original authorization number** field.

6.  In the **Authorization number** field, enter the new authorization number for the split authorization.

7.  In the **Issue date** field, select the date when the authorization was issued.

8.  In the **Split pct.** field, enter the percentage of the split. The percentage value that you enter is applied to the remaining values in the **Balance**, **Net balance quantity**, and **Net balance value** fields in the **Import details** form.

9.  In the **Reference number** field, enter the reference number of the split authorization.

10. In the **Reference date/time** field, enter the date and time when the reference number was issued.

11. In the **Reason** field, enter a description or other information about the reason for the split.

This procedure results in the following changes:

  - After the authorization is split, the new authorization is available in the **EXIM Authorization schemes** form. The **Split approved** check box is selected automatically.

  - The **Product group**, **Port ID**, and **Authorization basis** fields of the new authorization are updated to match the values of the original license number.

  - The **Summary Importable items** form is updated with the details that are entered in the **Import details** form for the new authorization.

Additionally, the following details are updated in the **Import details** form:

  - The value in the **Allowed** field is equal to the value in the **Balance** field in the original authorization multiplied by the value that you entered in the **Split pct.** field.

  - The values in the **Utilized**, **Sold**, and **Split value** fields are set to zero.

  - The value in the **Balance** field equals the value in the **Allowed** field – the value in the **Utilized** field + the value in the **Sold** field + the value in the **Split value** field.

  - On the **Overview** FastTab, the **Item number**, **Product name**, **Unit**, **Balance importable quantity**, and **Balance importable value** fields are updated based on information in the **Summary Importable items** form.

  - On the **Details** FastTab, the **Split quantity** and **Split value** columns display the values that appear in the corresponding fields on the **Overview** FastTab.

## See also

[(IND) Set up EXIM authorization schemes for DFIA](ind-set-up-exim-authorization-schemes-for-dfia.md)

[(IND) EXIM Authorization schemes (form)](https://technet.microsoft.com/library/jj664625\(v=ax.60\))

[(IND) Split details (form)](https://technet.microsoft.com/library/jj678058\(v=ax.60\))

[(IND) Summary importable items (form)](https://technet.microsoft.com/library/jj664946\(v=ax.60\))

[(IND) Import details - AA/DFIA (form)](https://technet.microsoft.com/library/jj664632\(v=ax.60\))

  


