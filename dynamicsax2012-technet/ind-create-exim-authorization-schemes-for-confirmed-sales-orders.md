---
title: (IND) Create EXIM authorization schemes for confirmed sales orders
TOCTitle: (IND) Create EXIM authorization schemes for confirmed sales orders
ms:assetid: 1e6d00e3-54b0-4eae-a499-cd37c32f461a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664542(v=AX.60)
ms:contentKeyID: 49385621
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- sales order
- (IND)
- india
- EXIM
- authorization scheme
- confirmed sales order
- EXIM authorization scheme
---

# (IND) Create EXIM authorization schemes for confirmed sales orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create export-import (EXIM) authorization schemes for confirmed sales orders and export orders, and on the basis of annual consumption. This topic describes how to create EXIM authorization schemes for confirmed sales orders.

1.  Click **General ledger** \> **Common** \> **EXIM Authorization schemes**.
    

    > [!NOTE]
    > <P>Information on this page is available only if the <STRONG>Advance Authorization</STRONG> check box is selected in the <STRONG>Incentive scheme parameters</STRONG> form.</P>



2.  In the **Authorization type** field, select **AA** (Advance Authorization).

3.  On the **Action Pane**, in the **New** group, click **EXIM Authorization schemes** to create a new EXIM authorization scheme.
    
    The authorization ID is created automatically, based on the number sequence that is set up in the **General ledger parameters** form. The **Date/Time** field contains the date and time that the authorization was created. You can modify these values.

4.  On the **Overview** FastTab, select a product group and a port for the authorization scheme.

5.  In the **Authorization basis** field, select **Confirmed orders**. You cannot modify the **Authorization basis** field after the record is saved.
    
    The status of the authorization scheme is automatically set to **Created**.

6.  If the authorization scheme is transferable, select the **Transferable** check box.

7.  Click **Attach** \> **Confirmed orders**.
    

    > [!NOTE]
    > <P>The <STRONG>Attach</STRONG> button is available only if the <STRONG>Status</STRONG> field is set to <STRONG>Created</STRONG>. The <STRONG>Confirmed orders</STRONG> menu item is available only if <STRONG>Confirmed orders</STRONG> is selected in the <STRONG>Authorization basis</STRONG> field.</P>



8.  In the **From date** field, enter the starting date of the confirmed orders list. In the **To date** field, enter the ending date of the confirmed orders list.

9.  Click **Show data** to view all the confirmed sales orders.
    
    The **Overview** FastTab displays the identification number of the confirmed sales orders and the date when the sales orders were confirmed. These values reflect those in the sales order confirmation journal. To be listed here, confirmed sales orders must meet the following criteria:
    
      - The product group and port ID of the sales order match the product group and port ID of the authorization scheme that is selected in the **EXIM Authorization schemes** form.
    
      - The item lines of the order are not attached to any other incentive scheme license that has an **AA** authorization type.
    
      - The status of the order is either confirmed or invoiced. Orders that have a status of **Shipping bill** are not included.
    
      - Items on the order are part of a BOM (bill of materials).
    
      - The date of the order falls within the date range that is specified in the **Confirmed orders** form.

10. On the **Lines** FastTab, view all the item lines on the selected order.

11. Click **Apply SION** to update the **Importable Items** form.
    
    When you click **Apply SION**, you receive a confirmation message. Click **Yes** to update the **Importable Items** form for each record on the **Lines** FastTab in the **Confirmed orders** form.
    
    The fields in the **Importable Items** form are updated based on the data that is set up in the **SION Items** form. When you apply Standard Input Output Norms (SION), the importable items are updated for item lines for which the **Mark** check box is selected.

12. Click **Importable Items**, and then verify the records.
    
    For details about the information to verify, see "Updated information in the Importable items form," later in this topic.
    

    > [!NOTE]
    > <UL>
    > <LI>
    > <P>The <STRONG>Importable Items</STRONG> form does not display any records if you open the form before you click <STRONG>Apply SION</STRONG>.</P>
    > <LI>
    > <P>You cannot manually create a new record or delete an existing record in the <STRONG>Importable Items</STRONG> form.</P>
    > <LI>
    > <P>You must verify the records against the paper copy of the SION that you received from the Directorate General of Foreign Trade (DGFT).</P></LI></UL>



13. Close the **Importable Items** form.

14. In the **Confirmed orders** form, click **Inventory** \> **Dimensions display**, and then select the dimensions for the inventory. Click **OK** to close the **Dimensions display** form.

15. In the **Confirmed orders** form, click **OK**.
    
    For information about the changes that occur in the form, see "Changes that occur when you close the Annual consumption form," later in this topic.

16. Close the **EXIM Authorization schemes** form.

## Updated information in the Importable items form

  - The **Item number** field displays the item numbers for items in the BOM of the selected line in the **Confirmed orders** form.

  - The **Product name** field and the **Unit** field are updated to display the values in these fields in the **SION Items** form.

  - If the **Basis** field of an item line in the **SION Items** form is set to anything other than **Pct. of FOB** or **Value**, and the **Apply restriction** check box is not selected, the value in the **Allowed quantity** field is used to calculate the **Quantity** field.
    
    If the **Apply restriction** check box is selected for an item line in the **SION Items** form, the value in the **Restricted allowed quantity** field is used to calculate the quantity, based on the following calculation:
    
    allowed quantity (or restricted allowed quantity) \* quantity (in the Confirmed orders form) / quantity (in the SION form)
    

    > [!NOTE]
    > <P>The <STRONG>Quantity</STRONG> field is updated after the units are converted. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh209285(v=ax.60)">Unit conversions (form)</A>.</P>



  - If the **Basis** field is set to **Pct. of FOB** for an item line in the **SION Items** form, the value in the **Value** field for an item in the **Importable Items** form is based on the following calculation:
    
    assessable value amount (in the Confirmed orders form) \* value amount (in the SION form) / 100
    
    If **Value** is selected in the **Basis** field for an item line in the **SION Items** form, the value for an item in the **Importable Items** form is based on the following calculation:
    
    quantity amount (in the Confirmed orders form) \* value amount (in the SION form)

## Changes that occur when you close the Annual consumption form

  - In the **EXIM Authorization schemes** form, the export assessable value is equal to the cumulative assessable value of all the confirmed order lines for which the **Mark** check box is selected. The import assessable value is updated based on the assessable value percentage that is set in the **Incentive scheme parameters** form.
    

    > [!NOTE]
    > <P>The <STRONG>Summary Importable items</STRONG> button is not available when the <STRONG>Status</STRONG> field of the authorization record is set to <STRONG>Created</STRONG>. You can view the details of importable items in the <STRONG>Summary Importable items</STRONG> form, based on the <STRONG>License status</STRONG> field. When you select the <STRONG>All</STRONG> check box, the summary of importable items for all statuses is displayed. You can modify the <STRONG>Allowed quantity</STRONG> field and the <STRONG>Allowed value</STRONG> field. When the authorization status is <STRONG>Applied</STRONG>, you can create a new record.</P>



  - The cumulative value of the amounts in the **Assessable value** field for all the item lines for which the **Mark** check box selected on the **Lines** FastTab in the **Confirmed orders** form is updated in the **Export assessable value** field for the record that is selected on the **Lines** FastTab in the **EXIM Authorization schemes** form. The value that is updated in the **Export assessable value** field is the value after conversion to the base currency. The value is converted by using the customs exchange rate.

  - The details in the **Importable Items** form for each item line are summarized and updated in the **Summary Importable items** form for the authorization. The **Status** field for the record that is selected on the **Overview** FastTab in the **EXIM Authorization schemes** form is updated to **Applied**. After you apply the SION, all the updated data is cleared and new records are updated when you click **Show data** in the **Confirmed orders** form.

  - The **Import assessable value** field in the **EXIM Authorization schemes** form is updated when the percentage in the **Assessable value pct.** field in the **Advance Authorization** area in the **Incentive scheme parameters** form is applied to the value in the **Export assessable value** field in the **EXIM Authorization schemes** form.

## See also

[(IND) Create EXIM authorization schemes for export orders](ind-create-exim-authorization-schemes-for-export-orders.md)

[(IND) Create EXIM authorization schemes on the basis of annual consumption](ind-create-exim-authorization-schemes-on-the-basis-of-annual-consumption.md)

[Setting up and maintaining inventory dimensions](setting-up-and-maintaining-inventory-dimensions.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

