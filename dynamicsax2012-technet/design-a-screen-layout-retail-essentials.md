---
title: Design a screen layout (Retail essentials)
TOCTitle: Design a screen layout (Retail essentials)
ms:assetid: 9f85c09b-b4f6-4f64-9461-dc1ff36a085b
ms:mtpsurl: https://technet.microsoft.com/library/Dn736924(v=AX.60)
ms:contentKeyID: 62200399
author: Khairunj
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Design a screen layout (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to design a screen layout for a register. You can use this feature only if you have been granted the appropriate permissions to the database. For more information, see this [TechNet article](https://go.microsoft.com/fwlink/?linkid=267571).


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



To design a screen layout, follow these steps:

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Screen layouts**.

2.  To create a new layout, press CTRL+N, and then, in the **Screen layout ID** field, type an ID for the layout. To modify an existing layout, select the layout. Then click **Designer**.

3.  Click **Design mode**, and then click **Main layout**. The following parts are available:
    
      - **Empty Space Item** – Insert space between parts.
    
      - **Label** – Insert a text label.
    
      - **Separator** – Insert a separator between parts.
    
      - **Splitter** – Insert a separator that you can use to resize the screen layout grid inRetail essentials.
    
      - **Button grid 1** to **Button grid 5** – The button grids that were created and selected to appear when Microsoft Dynamics AX for Retail POS starts.
    
      - **Cash changer** – Insert a pane that displays information about the cash changer, if a cash changer is used at the register.
    
      - **Customer** – Information about the customer.
    
      - **Keyboard Buttons** – This part is not used.
    
      - **Keyboard Input** – This part is not used.
    
      - **Logo1** to **Logo5** – One or more image boxes that display the company’s logo or other selected images.
    
      - **Message** – A pane that displays a message whenever a function is performed in Retail essentials.
    
      - **Receipt** – A pane that displays sales information, such as the item number, product name, price, and sales tax.
    
      - **Numpad** – A pane that displays an input field and an onscreen number pad. This part can be used to enter item numbers, bar codes, and product quantities. You can also search for products and customers.
    
      - **Stringpad** – A pane that displays an input field that can be used to enter item numbers, bar codes, and product quantities. You can also search for products and customers.
    
      - **Totals** – A pane that displays sales transactions. The information that is displayed includes discounts, taxes, line numbers, and balance amounts.

4.  Select a part, and then drag the part onto the layout designer.
    
    **Examples**
    
      - Select **Receipt**, and then drag this part onto the layout designer. **Receipt** no longer appears in the **Customization** form, because each layout can have only one receipt part.
    
      - Select **Label**, and then drag this part onto the layout designer. **Label** still appears in the **Customization** form, because each layout can have several label parts.
    

    > [!NOTE]
    > <P>When you select a part, and then move the pointer over the layout designer window and to the edge of the part, a thick dashed black line appears. When you release the mouse button while the pointer is over this line, the button grid appears there. After the button grid appears in the layout designer window, you can change the size of the button grid.</P>

    
    To remove a part from the layout, drag the part back into the **Customization** form.

5.  After you have finished designing the **Main layout** section, you can design the **Customer layout** section. Click **Design mode**, and then click **Customer layout**.
    
    The following parts are available:
    
      - **Empty Space Item** – Insert space between button grids.
    
      - **Splitter** – Insert a separator that you can use to resize the screen layout grid in Retail POS.
    
      - **Balance info** – The balance that is due for the customer account.
    
      - **Customer address** – The customer’s address.
    
      - **Customer ID** – The customer’s ID number.
    
      - **Customer name** – The name of the customer.
    
      - **Invoice Account** – The customer account to which the invoice is addressed, if this account differs from the customer account number.
    

    > [!NOTE]
    > <P>You can add these parts only to the <STRONG>Customer layout</STRONG> section of a screen layout. When you drag a part, the pointer indicates when you are in the correct section.</P>



6.  Click **Design mode**, and then select **Totals layout**.
    
    The following parts are available:
    
      - **Empty space item** – Insert space between button grids.
    
      - **Label** – A text label.
    
      - **Separator** – A line that separates parts.
    
      - **Splitter** – Insert a separator that you can use to resize the screen layout grid in Retail POS.
    
      - **Number of line items** – The number of line items in a transaction.
    
      - **Amount** – The amount that is due.
    
      - **Line discount** – The amount of the discounts that are applied to line items.
    
      - **Loyalty points discount** – The discount amount that is applied to a transaction by using loyalty points as payment.
    
      - **Sum of discounts with tax** – The total amount of the discounts that are applied to the transaction. This amount includes tax.
    
      - **Number of items** – The number of line items in the transaction.
    
      - **Payment** – The payment that is applied to the transaction.
    
      - **Rounded** – The amount of rounding that is applied to the total.
    
      - **Sum of discounts** – The total amount of the discounts that are applied to the transaction.
    
      - **Total discount** – The amount of the discount that is applied to the transaction's total.
    
      - **Total discount with tax** – The amount of the discount that is applied to the transaction's total. This amount includes tax.
    
      - **Subtotal without tax** – The transaction’s subtotal. Sales tax is not included.
    
      - **Subtotal** – The transaction’s subtotal. Sales tax is included, but shipping and miscellaneous charges are not included.
    
      - **Tax on cancellation charges** – The sales tax that is applied to cancellation charges.
    
      - **Tax** – The amount of sales tax.
    
      - **Misc. charge total** – The amount of miscellaneous charges.
    
      - **Total** – The total amount of the transaction.
    
      - **Balance** – The balance that is due after partial payment.
    

    > [!NOTE]
    > <P>You can add these parts to, or remove them from, only the <STRONG>Totals layout</STRONG> section of a screen layout.</P>



7.  Click **Design mode**, and then select **Product grid layout**.
    
    The **Customization** form displays the columns that you can drag to and from the transaction's product grid. The product grid is the pane that displays the line items that are added to the transaction.
    

    > [!NOTE]
    > <P>You can add these parts to, or remove them from, only the <STRONG>Product grid layout</STRONG> section of a screen layout.</P>



## See also

[Setting up screen layouts (Retail essentials)](setting-up-screen-layouts-retail-essentials.md)

  


