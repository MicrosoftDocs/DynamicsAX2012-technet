---
title: Design a screen layout
TOCTitle: Design a screen layout
ms:assetid: fd836a1e-ab35-4f05-b721-5d8e29d2d911
ms:mtpsurl: https://technet.microsoft.com/library/Hh597301(v=AX.60)
ms:contentKeyID: 39519390
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Design a screen layout 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

You can only use this feature if you have been granted special permissions to the database. For more information, see this [TechNet article](https://go.microsoft.com/fwlink/?linkid=267571).

1.  Click **Retail** \> **Setup** \> **POS** \> **Screen layouts**.

2.  To create a new layout, press CTRL+N, and then, in the **Screen layout ID** field, type an ID for the layout. To modify an existing layout, select a layout. Then click **Designer**.

3.  Click **Design mode**, and then click **Main layout**. The following parts are available:
    
      - **Empty Space Item** – Insert space between button grids.
    
      - **Label** – Insert a text label.
    
      - **Separator** – Insert a separator between parts.
    
      - **Splitter** – Insert a separator that you use to resize the screen layout grid in Microsoft Dynamics AX for Retail POS.
    
      - **Button grid 1** to **Button grid 5** – The button grids that were created and selected to appear when Retail POS starts.
    
      - **Cash changer** – Insert a pane that displays information about a cash changer, if one is in use at the register.
    
      - **Customer** – Information about the customer.
    
      - **Logo** – An image box that displays the company’s logo.
    
      - **Message** – A pane that displays a message whenever a function is performed in Retail POS.
    
      - **Receipt** – A pane that displays sales information, such as the item number, product name, price, and sales tax.
    
      - **Numpad** – A pane that displays only numbers. This part can be used to enter item numbers, bar codes, and product quantities.
    
      - **Totals** – A pane that displays sales transactions. The information that is displayed includes discounts, taxes, line numbers, and balance amounts.

4.  Select a part, and then drag the part onto the layout designer.
    
    **Examples**
    
      - Click **Receipt**, and then drag this part onto the layout designer. **Receipt** no longer appears in the **Customization** form, because each layout can have only one receipt part.
    
      - Select **Label**, and then drag this part onto the layout designer. **Label** still appears in the **Customization** form, because each layout can have several label parts.
    

    > [!NOTE]
    > <P>When you select a part, and then move the mouse pointer over the design window and to the edge of the part, a thick dashed black line appears. When you release the mouse button while the mouse pointer is over this line, the button grid appears there. After the button grid appears in the layout designer window, you can change the size of the button grid.</P>

    
    To remove a part from the layout, drag the part back into the **Customization** form.

5.  After you have finished designing the **Main layout** section, you can design the **Customer layout** section. Click **Design mode**, and then click **Customer layout**.
    
    The following parts are available:
    
      - **Empty Space Item** – Insert space between button grids.
    
      - **Splitter** – Insert a separator that you use to resize the screen layout grid in Retail POS.
    
      - **Invoice Account** – The customer account to which the invoice is addressed, if this account differs from the customer account number.
    

    > [!NOTE]
    > <P>You can add these parts only to the <STRONG>Customer layout</STRONG> section of a screen layout. When you drag a part, the mouse pointer indicates when you are in the correct section.</P>



6.  Click **Design mode**, and then select **Totals layout**.
    
    The following parts are available:
    
      - **Empty space item** – Insert space between button grids.
    
      - **Splitter** – Insert a separator that you use to resize the screen layout grid in Retail POS.
    
      - **Gross amount** – The gross amount of the transaction.
    
      - **Gross amount with tax** – The gross amount of the transaction, including tax.
    
      - **Sum of discounts with tax** – The total amount of discounts that are applied to the transaction, including tax.
    
      - **Line discount** – The amount of the discounts that are applied to line items.
    
      - **Line discount with tax** – The amount of the discounts that are applied to line items, including tax.
    
      - **No. of items** – The number of line items in the transaction.
    
      - **Payment** – The payment applied to the transaction.
    
      - **Rounded** – The amount of rounding that is applied to the total.
    
      - **Net amount with tax** – The net amount of the transaction's total, including tax.
    
      - **Sum of discounts** – The total amount of discounts that are applied to the transaction.
    
      - **Total discount** – The amount of the discount that is applied to the transaction's total.
    
      - **Total discount with tax** – The amount of the discount that is applied to the transaction's total, including tax.
    

    > [!NOTE]
    > <P>You can add these parts to, or remove them from, only the <STRONG>Totals layout</STRONG> section of a screen layout.</P>



7.  Click **Design mode**, and then select **Product grid layout**.
    
    The **Customization** form displays the columns that you can drag to and from the transaction's product grid (the pane that displays the line items that are added to the transaction).
    

    > [!NOTE]
    > <P>You can add these parts to, or remove them from, only the <STRONG>Product grid layout</STRONG> section of a screen layout.</P>



## See also

[About setting up screen layouts](about-setting-up-screen-layouts.md)

  


