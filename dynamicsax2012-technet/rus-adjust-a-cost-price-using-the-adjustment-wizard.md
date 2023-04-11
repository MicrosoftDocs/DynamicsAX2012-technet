---
title: (RUS) Adjust a cost price using the adjustment wizard
TOCTitle: (RUS) Adjust a cost price using the adjustment wizard
ms:assetid: dfb9f2a7-77b2-4cad-b7a4-5111ed786982
ms:mtpsurl: https://technet.microsoft.com/library/Dn126130(v=AX.60)
ms:contentKeyID: 52075441
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Adjust a cost price using the adjustment wizard 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use this wizard to create and run cost price adjustments for on-hand transactions.

1.  Click **Inventory management** \> **Periodic** \> **Close and adjustment in currency**. Click **Adjustment** \> **Wizard** to open the **Wizard for cost value adjustment of inventory transactions or entire on-hand inventory** form.
    

    > [!NOTE]
    > <P>To use the wizard for on-hand inventory adjustments, select <STRONG>Closing</STRONG> in the <STRONG>Type</STRONG> field in the <STRONG>Closing and adjustment</STRONG> form. If you use the <STRONG>On-hand</STRONG> or <STRONG>Transactions</STRONG> standard adjustment functions, the adjustments are posted to the profit and loss accounts, as usual.</P>



2.  In the **Wizard for cost value adjustment of inventory transactions or entire on-hand inventory** form, select **On-hand** or **Transactions** as the method of cost price adjustment, and then click **Next \>**.

3.  In the **Select on-hand inventory** form, click **Select** to specify the selection criteria for **On-hand inventory** and **Inventory dimensions** transactions, and then click **OK**.

4.  Click **Next \>** to go to the **Functions for calculating adjustment amounts** page, where you can select **Item cost price**, **Fixed cost price**, **Amount**, **Value**, or **Percent** as the adjustment method.

5.  Click **Next \>** to go to the **Adjustment with amount** page.

6.  In the **Amount** field, enter the amount to be adjusted, and then click **Next \>**.

7.  On the **Posting** page, select the **Storno** check box to enter the ledger posting as a reverse note.
    

    > [!NOTE]
    > <P>This field is available only if the allocation amount is negative. If the amount is negative and the reverse parameter is not activated, the adjustment is reversed.</P>



8.  In the **Note** field, enter comments.

9.  In the **Corr. account** field, select the offset account to perform the adjustment transactions.
    

    > [!NOTE]
    > <P>If you selected <STRONG>From ledger account</STRONG> as the adjustment calculation method, then the account that is specified when calculating the total adjustment amount is used as the offset account.</P>



10. Click **Next \>** to open the **Finish** page.

11. Select the **Show ledger voucher list** check box to view the list of posted transactions.

12. Click **Finish** to run the wizard.

## See also

[(RUS) Closing and adjustment (form)](https://technet.microsoft.com/library/jj711629\(v=ax.60\))

[(RUS) Adjust the cost price from the ledger account](rus-adjust-the-cost-price-from-the-ledger-account.md)

  


