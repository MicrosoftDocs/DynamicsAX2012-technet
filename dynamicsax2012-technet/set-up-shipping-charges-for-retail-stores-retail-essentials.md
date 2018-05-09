---
title: Set up shipping charges for retail stores (Retail essentials)
TOCTitle: Set up shipping charges for retail stores (Retail essentials)
ms:assetid: 85af0fe6-6dd4-43c7-a0cf-d72156166c47
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn688620(v=AX.60)
ms:contentKeyID: 62230652
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up shipping charges for retail stores (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up shipping charges for customer orders that are created in retail stores. There are three main steps to setting up shipping charges:

  - Set up the charges codes that specify which ledger accounts are used to post shipping charges.

  - Select the charges code for the shipping charge that your store charges to ship a customer’s order.

  - Set up the auto charges that specify the actual amounts that you charge for each shipping method that your store offers.

## Set up charges codes

1.  Click **Retail essentials** \> **Financials** \> **Setup** \> **Charges** \> **Charge codes**.

2.  Click **New**, and then, in the **Charges code** field, enter a code.

3.  Enter a description for the charges code. Then, if the charge is subject to sales tax, select a tax in the **Item sales tax group** field.

4.  Select the **Prorate** check box to prorate shipping charges across invoices.

5.  On the **Posting** FastTab, set up and view details about the debit and credit accounts for the charges code.

## Select a charges code for customer orders

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **Retail parameters**.

2.  Click **Customer orders**, and then, in the **Charge codes** group, in the **Shipping charge code** field, select a charges code.

## Set up auto charges

1.  Click **Retail essentials** \> **Financials** \> **Setup** \> **Charges** \> **Auto charges**.

2.  Click **New**, and then, in the **Account code** field, enter a code.

3.  In the **Mode of delivery code** field, select **Table**, and then, in the **Mode of delivery relation** field, select a mode of delivery.
    
    For example, your store might offer “Next-day air” or “Standard ground” shipping.
    

    > [!TIP]
    > <P>To set up modes of delivery, follow these steps:</P>
    > <OL>
    > <LI>
    > <P>Click <STRONG>Retail essentials</STRONG> &gt; <STRONG>Channels</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Retail parameters</STRONG>.</P>
    > <LI>
    > <P>Click <STRONG>Customer orders</STRONG>.</P>
    > <LI>
    > <P>Under <STRONG>Sales order</STRONG>, right-click the <STRONG>Electronic mode of delivery</STRONG> field, and then click <STRONG>View details</STRONG>.</P></LI></OL>



4.  On the **Lines** tab, click **Add**, and then specify the following settings:
    
      - **Currency** – Specify the currency of the shipping charge.
    
      - **Charges code** – Specify the charges code to use to post the shipping charge.
    
      - **Category** – Specify whether the shipping charge is a percentage, a fixed amount, a charge per piece that is shipped, or an external charge that is determined by a shipping company.
    
      - **Charges value** – Specify the amount of the shipping charge.
    
      - **Charges currency code** – Specify the currency of the charges code.
    
      - **From amount** – Specify the minimum purchase amount that the shipping charge applies to.
    
      - **To amount** – Specify the maximum purchase amount that the shipping charge applies to.
    
      - **Sales tax group** – If the shipping charge is subject to sales tax, select the sales tax.
    
      - **Keep** – Select this check box to retain the charges transaction after invoicing.

5.  Repeat step 4 to add as many lines as you require.
    
    For example, you add a line for a shipping charge that applies to purchases under $100 and another line for a charge that applies to purchases over $100.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

