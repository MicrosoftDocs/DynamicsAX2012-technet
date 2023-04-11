---
title: Delete delivery schedules and delivery lines
TOCTitle: Delete delivery schedules and delivery lines
ms:assetid: 3d2b3435-ca67-4456-a2f6-5ef9ab87e65e
ms:mtpsurl: https://technet.microsoft.com/library/Hh242235(v=AX.60)
ms:contentKeyID: 36056674
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Delete delivery schedules and delivery lines 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to delete all of a delivery schedule with all associated delivery lines.

### Delete all of a delivery schedule

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**.

2.  Select your order and double-click to open it.

3.  In the **Purchase order lines**, **Sales order lines**, or **Lines** list, click the required order line.
    

    > [!NOTE]
    > <P>To delete all of the delivery schedule, you must click the delivery line with the associated delivery lines. The <STRONG>Remove</STRONG> option is not available if you only select a single delivery line. If you want to delete a single delivery line, you must follow the procedure below <STRONG>Delete a single delivery line</STRONG>.</P>



4.  Click **Remove**. You will be prompted to confirm or cancel your action.

5.  Click **Yes** to confirm that you want to delete the whole delivery schedule including all its delivery lines. The delivery schedule is then deleted, and the order line becomes a new order line. Click **No** to cancel.
    

    > [!NOTE]
    > <P>You can only delete the whole delivery schedule if all your delivery lines can be deleted. This means that no lines have been invoiced. However, if you have set the parameter field <STRONG>Delete order after invoicing</STRONG> in the <A href="https://technet.microsoft.com/library/aa576993(v=ax.60)">Accounts receivable parameters (form)</A> and <A href="https://technet.microsoft.com/library/aa596348(v=ax.60)">Accounts payable parameters (form)</A>, the whole delivery schedule will automatically be deleted when all the delivery lines have the status Invoiced.</P>



Use this procedure to delete one delivery line.

### Delete a single delivery line

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**.

2.  Select your order and double-click to open it.

3.  In the **Purchase order lines**, **Sales order lines**, or **Lines** list, click an order line and then click **Purchase order line**, **Sales order line**, or **Sales quotation line** \> **Delivery schedule**. The **Delivery schedule** form is displayed.

4.  Click the delivery line that you want to delete, and then press **Alt+F9** to delete the line.

5.  Click **Yes** to confirm that you want to delete the delivery line. Click **No** to cancel.

6.  Click **OK** to save the changes to the delivery schedule.

## See also

[Delivery schedule - Sales order (form)](https://technet.microsoft.com/library/hh209246\(v=ax.60\))

[Delivery schedule - Sales quotation (form)](https://technet.microsoft.com/library/hh209450\(v=ax.60\))

[Delivery schedule - Purchase order (form)](https://technet.microsoft.com/library/hh227634\(v=ax.60\))

[About delivery schedules](about-delivery-schedules.md)

  


