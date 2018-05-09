---
title: Increase or decrease the letter of guarantee value
TOCTitle: Increase or decrease the letter of guarantee value
ms:assetid: 4a5558a5-0607-462e-a0b8-d843726f2fcd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208707(v=AX.60)
ms:contentKeyID: 36056962
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Increase or decrease the letter of guarantee value 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can increase or decrease the letter of guarantee value, as agreed on between the principal and beneficiary, after the letter of guarantee is delivered to the beneficiary.

You can increase the value of a letter of guarantee if the principal and beneficiary ask for a guarantee of a higher amount than the original request. Similarly, if the principal and beneficiary consider it mutually beneficial to lower the letter of guarantee value, they may request a decrease in the value of a letter of guarantee.

Use the **Create quotation**, **Sales quotation**, **Sales order**, **Purchase order**, or **Project details** form to request an increase or decrease in the value of the letter of guarantee. After making the request, use the **Letter of guarantee** form in **Bank** to increase or decrease the letter of guarantee value.

## Request to increase the letter of guarantee value

Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order line and on the **Action Pane**, on the **Manage** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**. Double-click a sales quotation line to open the **Sales quotation details** form. On the **Action Pane**, on the **Quotation** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Double-click a sales order line to open the **Sales order details** form. On the **Action Pane**, on the **Manage** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**. Double-click a project quotation line to open the **Project quotation details** form. On the **Action Pane**, on the **Quotation** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Double-click a project line to open the **Project details** form. On the **Action Pane**, on the **Project** tab, click **Letter of guarantee**.

1.  Click **Increase value** to open the **Increase the value of letter of guarantee** drop dialog.

2.  In the **Value to add** field, enter the amount to be added to the original letter of guarantee value. The currency is displayed.

3.  Click **OK** to request an increase in the letter of guarantee value. The **Facility status** field of the request is updated to **Request increase value**.

## Increase the letter of guarantee value

1.  Click **Cash and bank management** \> **Common** \> **Letters of guarantee**.

2.  In the left pane, select the request with the status **Request increase value** and click **Increase value** to open the **Increase the value of letter of guarantee** drop dialog.
    
    The amount you entered in the **Value to add** field when you requested an increase in value is displayed in the **Increased value** field.

3.  In the **Margin** field, enter the margin amount that corresponds to the increased value.
    
    The margin amount is calculated and displayed as the amount specified in the **Increased value** field multiplied by the percentage specified in the **Cash margin** field in the **Bank facility agreements** form. If you have specified a fixed amount instead of a percentage in the **Bank facility agreements** form, the fixed amount is displayed in this field. You can modify this amount if required.

4.  In the **Commission expense** field, enter the increased value commission charged by the bank to increase the letter of guarantee value.
    
    The commission expense amount is calculated as the amount specified in the **Increased value** field multiplied by the percentage specified in the **Increase value commission** field in the **Bank facility agreements** form and displayed here. If you have specified a fixed amount instead of a percentage in the **Bank facility agreements** form, the fixed amount is displayed in this field. You can modify this amount if required.

5.  Click **OK** to increase the value of the letter of guarantee. Journal entries are posted to the accounts specified in the **Bank documents posting profile** form, using the daily journal specified in the **Transaction journal** field in the **Cash and bank management parameters** form. The **Facility status** field is updated to **Value increased**.

## Request to decrease the letter of guarantee value

Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order line and on the **Action Pane**, on the **Manage** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**. Double-click a sales quotation line to open the **Sales quotation details** form. On the **Action Pane**, on the **Quotation** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Double-click a sales order line to open the **Sales order details** form. On the **Action Pane**, on the **Manage** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**. Double-click a project quotation line to open the **Project quotation details** form. On the **Action Pane**, on the **Quotation** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Double-click a project line to open the **Project details** form. On the **Action Pane**, on the **Project** tab, click **Letter of guarantee**.

1.  Click **Decrease value** to open the **Decrease the value of letter of guarantee** drop dialog.

2.  In the **Value to decrease** field, enter the amount to be subtracted from the original letter of guarantee value. The currency is displayed.

3.  Click **OK** to request a decrease in the letter of guarantee value. The **Facility status** field of the request is updated to **Request decrease value**.

## Decrease the letter of guarantee value

1.  Click **Cash and bank management** \> **Common** \> **Letters of guarantee**.

2.  In the left pane, select the request with the status **Request decrease value** and click **Decrease value** to open the **Decrease the value of letter of guarantee** drop dialog.
    
    The amount you entered in the **Value to decrease** field when you requested a decrease in value is displayed in the **Decreased value** field.

3.  In the **Margin** field, enter the margin amount that corresponds to the decreased value.
    
    The margin amount is calculated and displayed as the amount specified in the **Decreased value** field multiplied by the percentage specified in the **Cash margin** field in the **Bank facility agreements** form. If you have specified a fixed amount instead of a percentage in the **Bank facility agreements** form, the fixed amount is displayed in this field. You can modify this amount if required.

4.  In the **Commission expense** field, enter the decreased value commission charged by the bank to decrease the letter of guarantee value.
    
    The commission expense amount is calculated as the amount specified in the **Decreased value** field multiplied by the percentage specified in the **Decrease value commission** field in the **Bank facility agreements** form and displayed here. If you have specified a fixed amount instead of a percentage in the **Bank facility agreements** form, the fixed amount is displayed in this field. You can modify this amount if required.

5.  Click **OK** to decrease the value of the letter of guarantee. Journal entries are posted to the accounts specified in the **Bank documents posting profile** form using the daily journal specified in the **Transaction journal** field in the **Cash and bank management parameters** form. The **Facility status** field is updated to **Value decreased**.

## See also

[Liquidate, extend, or cancel a letter of guarantee](liquidate-extend-or-cancel-a-letter-of-guarantee.md)

[Request and issue the letter of guarantee](request-and-issue-the-letter-of-guarantee.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

