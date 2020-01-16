---
title: (IND) Create EXIM authorization schemes on the basis of annual consumption
TOCTitle: (IND) Create EXIM authorization schemes on the basis of annual consumption
ms:assetid: 63f6e998-23df-465a-87cf-12fbcbeffd8f
ms:mtpsurl: https://technet.microsoft.com/library/JJ677871(v=AX.60)
ms:contentKeyID: 49385836
author: Khairunj
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- EXIM
- authorization scheme
- EXIM authorization scheme
- annual consumption
audience: Application User
ms.search.region: India
---

# (IND) Create EXIM authorization schemes on the basis of annual consumption 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create export-import (EXIM) authorization schemes for confirmed sales orders and export orders, and on the basis of annual consumption. This topic describes how to create EXIM authorization schemes on the basis of annual consumption.

1.  Click **General ledger** \> **Common** \> **EXIM Authorization schemes**.
    

    > [!NOTE]
    > <P>Information on this page is available only if the <STRONG>Advance Authorization</STRONG> check box is selected in the <STRONG>Incentive scheme parameters</STRONG> form.</P>



2.  In the **Authorization type** field, select **AA** (Advance Authorization).

3.  On the **Action Pane**, in the **New** group, click **EXIM Authorization schemes** to create a new EXIM authorization scheme.
    
    The authorization ID is created automatically, based on the number sequence that is set up in the **General ledger parameters** form. The **Date/Time** field contains the date and time that the authorization was created. You can modify these values.

4.  On the **Overview** FastTab, select a product group and a port for the authorization scheme.

5.  In the **Authorization basis** field, select **Annual consumption**. You cannot modify the **Authorization basis** field after the record is saved.
    
    The status of the authorization scheme is automatically set to **Created**.

6.  If the authorization scheme is transferable, select the **Transferable** check box.

7.  Click **Attach** \> **Annual consumption**.
    

    > [!NOTE]
    > <P>The <STRONG>Attach</STRONG> button is available only if the <STRONG>Status</STRONG> field is set to <STRONG>Created</STRONG>. The <STRONG>Annual consumption</STRONG> menu item is available only if <STRONG>Annual consumption</STRONG> is selected in the <STRONG>Authorization basis</STRONG> field.</P>



8.  In the **Item number** field, select the number of the item.
    
    You cannot create a new record for an item number that already exists in the **Annual consumption** form.

9.  In the **Unit** field, enter the unit of measure for the item. In the **Quantity** field, enter the quantity of the item to export. In the **Unit price** field, enter the unit price of the item.

10. In the **Assessable value** field, enter the Free On Board (FOB) value for the item.
    
    The assessable value is based on the following calculation:
    
    quantity \* unit price
    
    If you modify the assessable value, the **Unit price** field is cleared, and the modified assessable value is saved.

11. Click **Apply SION** to update the **Importable Items** form.
    
    When you click **Apply SION**, you receive a confirmation message. Click **Yes** to update the **Importable Items** form for each record on the **Overview** FastTab in the **Annual consumption** form.
    
    The fields in the **Importable Items** form are updated based on the data that is set up in the **SION Items** form. When you apply Standard Input Output Norms (SION), the importable items are updated.

12. Click **Importable Items**, and then verify the records.
    
    For details about the information to verify, see "Updated information in the Importable items form," later in this topic.
    

    > [!NOTE]
    > <UL>
    > <LI>
    > <P>The <STRONG>Importable Items</STRONG> form does not display any records if you open it before you click <STRONG>Apply SION</STRONG>.</P>
    > <LI>
    > <P>You cannot manually create a new record or delete an existing record in the <STRONG>Importable Items</STRONG> form.</P>
    > <LI>
    > <P>You must verify the records against the paper copy of the SION that you received from the Directorate General of Foreign Trade (DGFT).</P></LI></UL>



13. Close the **Importable Items** form.

14. In the **Annual consumption** form, click **Inventory** \> **Dimensions display**, and then select the dimensions for the inventory. Click **OK** to close the **Dimensions display** form.

15. In the **Annual consumption** form, click **OK**.
    
    For information about the changes that occur in the form, see "Changes that occur when you close the Annual consumption form," later in this topic.

16. Close the **EXIM Authorization schemes** form.

## Updated information in the Importable Items form

  - The **Item number** field displays the item numbers for items in the bill of materials (BOM) that have been updated in the **SION Items** form.

  - The **Product name** field and the **Unit** field are updated to display the values in these fields in the **SION Items** form.

  - If the **Basis** field of an item line in the **SION Items** form is set to anything other than **Pct. of FOB** or **Value**, and the **Apply restriction** check box is not selected, the value in the **Allowed quantity** field is used to calculate the **Quantity** field.
    
    If the **Apply restriction** check box is selected for an item line in the **SION Items** form, the value in the **Restricted allowed quantity** field is used to calculate the quantity, based on the following calculation:
    
    allowed quantity (or restricted allowed quantity) \* quantity (in the Annual consumption form) / quantity (in the SION form)
    

    > [!NOTE]
    > <P>The <STRONG>Quantity</STRONG> field is updated after unit conversion. For more information, see <A href="https://technet.microsoft.com/library/hh209285(v=ax.60)">Unit conversions (form)</A>.</P>



  - If the **Basis** field is set to **Pct. of FOB** for an item line in the **SION Items** form, the value in the **Value** field for an item in the **Importable Items** form is based on the following calculation:
    
    assessable value amount (in the Annual consumption form) \* value amount (in the SION form) / 100
    
    If **Value** is selected in the **Basis** field for an item line in the **SION Items** form, the value for an item in the **Importable Items** form is based on the following calculation:
    
    quantity amount (in the Annual consumption form) \* value amount (in the SION form)

## Changes that occur when you close the Annual consumption form

  - In the **EXIM Authorization schemes** form, the export assessable value is updated to equal the cumulative assessable value of all of order lines. The **Summary Importable items** form and the export assessable value are updated when you click **OK**, even if the SION is not applied. The import assessable value is updated based on the assessable value percentage that is specified in the **Incentive scheme parameters** form.

  - The cumulative value of the amounts in the **Assessable value** field for all the records in the **Annual consumption** form is updated in the **Export assessable value** field for the record that is selected on the **Lines** FastTab in the **EXIM Authorization schemes** form.

  - The **Status** field for the selected record on the **Overview** FastTab in the **EXIM Authorization schemes** form is updated to **Applied**. This field is updated when you click **OK**, even if the SION is not applied.

  - You can view the details of importable items in the **Summary Importable items** form, based on the **License status** field. You can modify the **Allowed quantity** field and the **Allowed value** field. When the authorization status is **Applied**, you can create a new record.

## See also

[(IND) Create EXIM authorization schemes for confirmed sales orders](ind-create-exim-authorization-schemes-for-confirmed-sales-orders.md)

[(IND) Create EXIM authorization schemes for export orders](ind-create-exim-authorization-schemes-for-export-orders.md)

[Setting up and maintaining inventory dimensions](setting-up-and-maintaining-inventory-dimensions.md)

  


