---
title: (CHN) Set up item posting by site
TOCTitle: (CHN) Set up item posting by site
ms:assetid: 046d2892-3a9c-409a-94f0-f6fd883656e8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ663989(v=AX.60)
ms:contentKeyID: 49384576
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Set up item posting by site 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up or modify the posting of items to ledger accounts, based on item groups and warehouse sites for inventory transactions. By setting up ledger accounts of inventory value by site, you can post inventory transactions—such as inventory journals, sales orders, purchase orders, production journals, and project item journals—for each specific site.

The site-related fields are available in the **Transaction combinations** and **Posting** forms only if the **Separate ledger accounts of inventory value by sites** check box is selected in the **Inventory and warehouse management parameters** form.

## Set up item posting by site for sales transactions

Use this procedure to set up a ledger account number to post site-specific sales transactions. When you post sales orders, the ledger transactions are applied to the accounts that have the appropriate corresponding packing slips and invoices.

1.  Click **Inventory management** \> **Setup** \> **Posting** \> **Posting**.
    
    −or−
    
    Click **Inventory management** \> **Setup** \> **Inventory** \> **Item groups**. Click **Posting**.

2.  On the **Sales order** tab, in the **Select** pane, select **Packing slip** or **Issue**.

3.  Create an inventory line. For more information, see [Item posting (form)](https://technet.microsoft.com/en-us/library/aa589971\(v=ax.60\)).

4.  In the **Site code** field, select from the following options:
    
      - **Table** – Postings in the ledger account apply to a specific site code that is selected in the **Site relation** field.
    
      - **All** – Postings in the ledger account apply to all site codes.
        

        > [!NOTE]
        > <P>The options in this field are available based on your selection in the <STRONG>Transaction combinations</STRONG> form.</P>



5.  In the **Site relation** field, select the site code. You can modify this field only if you select **Table** in the **Site code** field.

6.  In the **Main account** field, select the ledger account number for posting in the general ledger.

7.  Close the form.

## Set up item posting by site for purchase transactions

Use this procedure to set up a ledger account number to post site-specific purchase transactions. When you post purchase orders, the ledger transactions are applied to the accounts that have the appropriate corresponding purchase packing slips, invoices, or return orders.

1.  Click **Inventory management** \> **Setup** \> **Posting** \> **Posting**.
    
    −or−
    
    Click **Inventory management** \> **Setup** \> **Inventory** \> **Item groups**. Click **Posting**.

2.  On the **Purchase order** tab, in the **Select** pane, select **Packing slip**, **Product receipt**, **Fixed receipt price profit**, **Fixed receipt price loss**, or **Fixed receipt price offset**.

3.  Repeat steps 3 through 6 in the **Set up item posting by site for sales transactions** procedure to set up site information.

4.  Close the form.

## Set up item posting by site for inventory transactions

Use this procedure to set up a ledger account number to post site-specific inventory transactions. When you post the inventory movement, profit and loss, bills of materials, item arrival, production input, physical counting, tag counting, or project item journals, the ledger account is selected based on the setup in the **Posting** form.

1.  Click **Inventory management** \> **Setup** \> **Posting** \> **Posting**.
    
    −or−
    
    Click **Inventory management** \> **Setup** \> **Inventory** \> **Item groups**. Click **Posting**.

2.  On the **Inventory** tab, in the **Select** pane, select **Fixed receipt price profit**, **Fixed receipt price loss**, **Issue**, or **Receipt**.

3.  Repeat steps 3 through 6 in the **Set up item posting by site for sales transactions** procedure to set up site information.

4.  Close the form.

## Set up item posting by site for production transactions

Use this procedure to set up a ledger account number to post site-specific production transactions. When you post end-production orders for inventory items using the standard cost model, the ledger account is selected based on the setup in the **Posting** form.

1.  Click **Inventory management** \> **Setup** \> **Posting** \> **Posting**.
    
    −or−
    
    Click **Inventory management** \> **Setup** \> **Inventory** \> **Item groups**. Click **Posting**.

2.  On the **Production** tab, in the **Select** pane, select **Picking list issue**, **Report as finished receipt**, **Issue**, or **Receipt**.

3.  Repeat steps 3 through 6 in the **Set up item posting by site for sales transactions** procedure to set up site information.

4.  Close the form.

## Set up item posting by site for standard cost variance transactions

Use this procedure to set up a ledger account number to post site-specific production transactions with cost variances.

1.  Click **Inventory management** \> **Setup** \> **Posting** \> **Posting**.
    
    −or−
    
    Click **Inventory management** \> **Setup** \> **Inventory** \> **Item groups**. Click **Posting**.

2.  On the **Standard cost variance** tab, in the **Select** pane, select **Purchase price variance**, **Inventory cost revaluation**, **Production lot size variance**, **Production quantity variance**, **Production price variance**, **Production substitution variance**, or **Rounding variance**.

3.  Repeat steps 3 through 6 in the **Set up item posting by site for sales transactions** procedure to set up site information.

4.  Close the form.

## See also

[(CHN) Activate an inventory transaction combination by site](chn-activate-an-inventory-transaction-combination-by-site.md)

[(CHN) About posting inventory main accounts by site](chn-about-posting-inventory-main-accounts-by-site.md)

[(CHN) Activate transaction combinations (modified form)](https://technet.microsoft.com/en-us/library/jj664107\(v=ax.60\))

[(CHN) Item posting (modified form)](https://technet.microsoft.com/en-us/library/jj664026\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

