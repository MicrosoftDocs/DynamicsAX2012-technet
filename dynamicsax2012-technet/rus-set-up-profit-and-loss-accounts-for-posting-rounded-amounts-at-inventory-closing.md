---
title: (RUS) Set up profit and loss accounts for posting rounded amounts at inventory closing
TOCTitle: (RUS) Set up profit and loss accounts for posting rounded amounts at inventory closing
ms:assetid: eaa3f967-104e-41eb-9abc-e8353d9ecab5
ms:mtpsurl: https://technet.microsoft.com/library/Dn126131(v=AX.60)
ms:contentKeyID: 52075454
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up profit and loss accounts for posting rounded amounts at inventory closing 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up a ledger account to post rounding differences that occur during inventory settlement. The rounding difference can be a profit or a loss, based on the difference between the amount of the cost value adjustment for an inventory transaction and the minimum throughput adjustment that is indicated during inventory closing. You must perform inventory settlement before you run the inventory closing process.

1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  In the **General** area, select the **Storno for inventory adjustments** check box to allow a Storno accounting transaction when inventory cost value adjustments are posted.

3.  Select the **Use rounding accounts** check box to activate posting of minimum inventory adjustments on rounding accounts instead of profit and loss accounts during inventory closing.

4.  Close the form.

5.  Click **Inventory management** \> **Setup** \> **Posting** \> **Posting**.

6.  Click the **Inventory** tab, and then in the left pane, select **Rounding - Loss**.

7.  In the right pane, click **Add**.

8.  In the **Item code** field, select the items that the rounded-off losses are posted for, from the following options:
    
      - **Table** – The rounded-off loss is posted for the item that is selected in the **Item relation** field.
    
      - **Group** – The rounded-off loss is posted for the item group that is selected in the **Item relation** field.
    
      - **All** – The rounded-off loss is posted for all of the items.
        

        > [!NOTE]
        > <P>You cannot select item codes of the <STRONG>Category</STRONG> type for rounding-off transactions.</P>



9.  In the **Main account** field, select the account number to post the rounded-off loss to.

10. In the left pane, select **Rounding - Profit**.

11. In the right pane, click **Add**.

12. In the **Item code** field, select the items that the rounded-off profits are posted for, from the following options:
    
      - **Table** – The rounded-off profit is posted for the item that is selected in the **Item relation** field.
    
      - **Group** – The rounded-off profit is posted for the item group that is selected in the **Item relation** field.
    
      - **All** – The rounded-off profit is posted for all of the items.
        

        > [!NOTE]
        > <P>You cannot select item codes of the <STRONG>Category</STRONG> type for rounding-off transactions.</P>



13. In the **Main account** field, select the account number to post the rounded-off profit to.

## See also

[(RUS) Post rounded amounts during inventory closing](rus-post-rounded-amounts-during-inventory-closing.md)

[(RUS) Adjust the cost price in reporting currency by on-hand adjustment](rus-adjust-the-cost-price-in-reporting-currency-by-on-hand-adjustment.md)

[(RUS) Adjust a cost price using the adjustment wizard](rus-adjust-a-cost-price-using-the-adjustment-wizard.md)

[(RUS) Adjust cost price by inventory receipt adjustment](rus-adjust-cost-price-by-inventory-receipt-adjustment.md)

[(RUS) Adjust the cost price from the ledger account](rus-adjust-the-cost-price-from-the-ledger-account.md)

[(RUS) Inventory and warehouse management parameters (modified form)](https://technet.microsoft.com/library/jj733200\(v=ax.60\))

  


