---
title: Set effective dates and view inactive addresses for party record
TOCTitle: Set effective dates and view inactive addresses for party record
ms:assetid: 76e2e58d-f20f-4a92-92a3-e8ab15e44854
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh545523(v=AX.60)
ms:contentKeyID: 37832508
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set effective dates and view inactive addresses for party record [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can assign one or more addresses to all party record types in Microsoft Dynamics AX. For example, a customer might have one address for their main office, another address for deliveries, and another address for billing. You can view a record of each address on the **Addresses** FastTab in the party record’s form, for example, the **Customers** form.

In the **Manage addresses** form, you can add new addresses to use immediately, inactivate address records that are no longer being used for a party, or add an address to use in the future. The address information is stored in the **Manage addresses** form and only the current active addresses are displayed on the **Addresses** FastTab in the party record’s form. You can view any past or future addresses by setting the **View** filter in the **Manage addresses** form.

For any address record, you can select a date range to indicate a length of time when an address will be active. If you have no indication that the address will be used for a limited time, you can leave the date fields blank.

You can set a limit on the effective dates for an address when you add the address, or any time after. When you set effective dates, you are not required to set both an effective and an expiration date. You may want to set only an expiration date for an address that will become inactive at some time in the future. Similarly, you may want to set only an effective date for an address that will become effective at some time in the future.

## Set date effective limits for a new address

1.  Open the party record for which you want to add an address.

2.  In the party record form, on the **Addresses** FastTab, click **Add**.

3.  Enter a name for the address, for example, Main office, and select a purpose for the address.
    
    Enter the address component information on the **General** FastTab, and then in the **Effective:** and **Expiration:** fields, select the effective dates and times for the address.

4.  Enter any remaining information about the address, and then click **OK**.

## Set date effective limits for an existing address

1.  Open the party record that contains the address for which you want to set a date effective limit.

2.  In the party record form, on the **Addresses** FastTab, select the address that you want to update with effective dates, and then click **More options** \> **Advanced**.

3.  Select the address that you want to update, and then in the **Manage addresses** form, on the **General** FastTab, click the icon next to the **Effective:** field.

4.  In the **Enter new effective date** form, enter the date and time at which the address will become active, and then click **OK**.

5.  In the **Manage addresses** form, on the **General** FastTab, click the icon next to the **Expiration:** field. Then, in the **Enter new expiration date** form, enter the date and time at which the address will no longer be active.

6.  Click **OK**.

## View inactive addresses

You can view a party record’s addresses even if the addresses are not active. Use this procedure to view addresses that are no longer active or have not yet become active.

1.  Open the party record that contains the address that you want to view.

2.  In the party record form, on the **Addresses** FastTab, select the address that you want to view, and then click **More options** \> **Advanced**.

3.  In the **Manage addresses** form, in the **View** filter, select the address type that you want to view. For example, select **Future** to view the new address of a customer whom you know will be moving to a new office very soon.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

