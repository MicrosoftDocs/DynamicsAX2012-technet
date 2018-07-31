---
title: (RUS) Create a sales order or free text invoice for a fixed asset
TOCTitle: (RUS) Create a sales order or free text invoice for a fixed asset
ms:assetid: f5cf2405-d220-4763-a8e2-db2018765296
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678624(v=AX.60)
ms:contentKeyID: 49388106
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a sales order or free text invoice for a fixed asset 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can record the sale of fixed assets in Fixed assets, or you can create a sales order or a free text invoice in Accounts receivable. When you sell a fixed asset, you must calculate its depreciation during that period.

If the fixed asset to be sold is registered in the **Inventory management** items list, you must create a sales order. However, you can record the sale of a non-inventoried item in **Fixed assets**, or you can create a free text invoice. The status of an asset that is sold under a sales order or free text invoice is **Sold (waiting for posting)**, until the transaction is posted. After posting, the status of the asset is **Written off (sale)**.


> [!NOTE]
> <P>You must set up posting profiles before you can create transactions for the sale of fixed assets. For more information, see <A href="rus-set-up-fixed-asset-posting-profiles.md">(RUS) Set up fixed asset posting profiles</A>.</P>



If the invoice expenses are included in the sales order header when you sell a fixed asset or inventory asset, the sum of these miscellaneous charges is not included in the profit or loss from the sale.

However, if the invoice expenses are included in the order line that corresponds to the asset, the charges are considered when the profit or loss is calculated from the sale.

## Create a sales order for a fixed asset

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Press CTRL+N to create a new sales order.

3.  Enter information about the sales order.
    

    > [!NOTE]
    > <P>For more information, see “Create a sales order" in the Applications and Business Processes Help.</P>



4.  In the lower pane, press CTRL+N to create new line items.

5.  In the **Item number** field, select a fixed asset inventory item.

6.  In the **Quantity** field, enter the quantity of fixed assets.

7.  In the **Unit** field, enter the measurement unit for fixed assets, such as pieces.

8.  In the **Unit price** field, enter the sale value of the fixed asset.

9.  Click the **General** tab.

10. In the **FA number** field, select the fixed asset number.

11. Click the **Dimension** tab and select the warehouse dimensions.
    

    > [!NOTE]
    > <P>Click <STRONG>Inventory management</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Inventory</STRONG> &gt; <STRONG>Item model groups</STRONG>. If the <STRONG>Physical negative inventory</STRONG> check box is selected, then you can sell an item that is a fixed asset type without entering an inventory item. If not, you can sell an inventory asset that has a <STRONG>Purchased</STRONG> status.</P>



12. Click **Posting** \> **Facture** to post the sales order.

13. Click **OK** to post the sales invoice.
    

    > [!NOTE]
    > <P>An invoice, facture, ledger, and fixed asset transactions are created, and the <STRONG>Status</STRONG> of the sales invoice changes to <STRONG>Shipped</STRONG>. The status of fixed asset, changes to <STRONG>Written off (sale)</STRONG>. The <STRONG>Disposal (sale)</STRONG> and <STRONG>Gain/Loss</STRONG> fields are updated in the <STRONG>FA balances</STRONG> form. The <STRONG>Disposal date</STRONG> and <STRONG>Disposal cost</STRONG> fields are updated in the <STRONG>FA Value models</STRONG> form.</P>



## Create a free text invoice for a fixed asset

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Press CTRL+N to create a new invoice.
    

    > [!NOTE]
    > <P>For more information, see “Create a free text invoice" in the Applications and Business Processes Help.</P>



3.  In the **Customer account** field, select a customer account.

4.  In the **Date** field, enter an invoice date.

5.  In the **Currency** field, select an invoice currency.

6.  Press CTRL+N in the lower pane, to create a new invoice line.

7.  In the **Ledger account** field, select the ledger account for posting the revenue to the current invoice line.

8.  In the **Sales tax group** field, select the sales tax group.

9.  In the **Item sales tax group** field, select the item sales tax group.

10. In the **Quantity** field, enter the quantity of fixed assets sold.

11. In the **Unit price** field, enter the sale value of the fixed asset unit.

12. In the **Measurement unit** field, select the unit of measurement unit for the fixed asset.

13. Click the **General** tab.

14. In the **FA number** field, select the fixed asset number.
    

    > [!NOTE]
    > <P>When including references to the fixed asset in an invoice line, its status changes to <STRONG>Sold (waiting for posting)</STRONG>.</P>



15. Click **Posting** \> **Update facture** to open the **Post facture** form.

16. Click **OK** to post the facture.
    

    > [!NOTE]
    > <P>An invoice, facture, and ledger and fixed asset transactions are created, and the status changes to <STRONG>Shipped</STRONG>. The status of the asset is <STRONG>Written off (sale)</STRONG>.</P>



17. Click **Fixed assets (Russia)** \> **Common** \> **Fixed assets**. to open **FA Value Models** form. The disposal date and cost of the fixed asset are displayed in the **Disposal date** and **Disposal cost** fields.

18. Click **Balance** to open the **FA balances** form. The details are displayed in the **Leaving (sale)** and **Gain/Loss** fields.

19. Press CTRL+S or close the form.

## See also

[(RUS) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj733272\(v=ax.60\))

[(RUS) FA value models (form)](https://technet.microsoft.com/en-us/library/jj856113\(v=ax.60\))

[(RUS) FA balances (form)](https://technet.microsoft.com/en-us/library/jj711559\(v=ax.60\))

  


