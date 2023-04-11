---
title: Complete common tasks in the Call center by using the Customer service form
TOCTitle: Complete common tasks in the Call center by using the Customer service form
ms:assetid: 0ad1d19f-83e6-4cc7-bd88-6bc5a927d5dd
ms:mtpsurl: https://technet.microsoft.com/library/Dn497711(v=AX.60)
ms:contentKeyID: 62490077
author: tonyafehr
ms.date: 11/19/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.MCRCheckHoldCustInfo
- Forms.MCRCustMessageAssociation
- Forms.MCRCustLookup
- Forms.MCRCustomerService
- Forms.MCRContinuityCustInfo
- Forms.MCRCustPaymDialog
- Forms.MCRCustServiceOrderDatesPart
- Forms.MCRCustPaymLookup
- Forms.MCRCustPaymInstallments
- Forms.MCRCustServiceOrderStatsPart
- Forms.MCRCustPaymDetail
- Forms.MCRCustPaymTable
- Forms.MCRCustSourceCodes
- Forms.MCRSalesTableOrderHistory
- Forms.MCRSalesStatsCustTable
audience: Application User
ms.search.region: Global
---

# Complete common tasks in the Call center by using the Customer service form 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to complete several common tasks in Call center by using the **Customer service** form. You can use this form to create new customer records and to complete customer service tasks such as creating and viewing sales orders, viewing customer cases, and updating customer information.

## Create new customer records and sales orders

To create records for new customers and create new sales orders, follow these steps:

1.  Click **Call center** \> **Journals** \> **Customer service**.

2.  Depending on whether you’re creating a new customer record or a new sales order, do one of the following:
    
      - To create a new customer, on the **Action Pane**, in the **New** group, click **Customer**. For more information about creating a customer record, see [Create a customer record](create-a-customer-record.md).
    
      - To create a new sales order, on the **Action Pane**, in the **New** group, click **Sales order**. For more information about creating a sales order in the Call center, see [Create sales orders in the call center](create-sales-orders-in-the-call-center.md).

## Search for customer-related information

Use the search fields in the **Customer service** form to search for a specific customer and all the information that is related to the customer’s account. When you search, the **Customer search** form opens showing the search results.

  - When the **Customer search** form opens, select the customer record that you want to work with, and then click **Select customer**.
    

    > [!NOTE]
    > <P>(BRA) You can select a keyword type such as <STRONG>CNPJ/CPF</STRONG> and enter the ID to filter the search results with the specified customer ID.</P>



## Use buttons on the Action Pane to complete tasks

After you select a customer record to work with, you can complete several tasks by using the buttons on the **Action Pane**. The **Action Pane** is divided into groups, and each group contains a set of buttons. The following sections describe the purpose of the buttons in each group.

## Details group

The **Details** group has three buttons: **Details**, **Options**, and **Related orders**.

Click **Details**, and then select one of the following:

  - **Other address** – Opens the **Address selection** form, where you can view all addresses that are associated with the selected customer.

  - **Contact details** – Opens the **Contacts** form, where you can view, update, or delete information for the customer contact.

  - **Backorder lines** – Opens the **Backorder lines** form, where you can review back orders, research missing deliveries, and view expected ship dates for the customer’s orders.

  - **Customer** – Opens the **Customers** form, where you can view or update the customer’s information.

Click **Options**, and then select one of the following:

  - **Notes** – Opens the **Notes** form, where you can add a note to the customer account.

  - **Source codes** – Opens the **Source codes** form, where you can view the sources codes of each catalog that the customer has received.

  - **Return inquiry** – Opens the **Return orders** form, where you can view orders that have been returned by the customer, or create a new return order.

  - **Customer item statistics** – Opens the **Customer item statistics** form, where you can view information about the items that the customer has previously ordered.

Click **Related orders** to open the **Sales related orders** form, where you can view parent or child orders that are related to the order that is selected in the grid.

## Show group

The **Show** group has three buttons: **Sales orders**, **Invoiced orders**, and **Archived sales orders**.

  - Click **Sales orders** to view all of the sales orders, including order information, that the customer has placed with your organization. You can view or modify information about sales orders and line items, and you can view information about order events.

  - Click **Invoiced orders** to view all of the customer’s orders, including order information, that have been invoiced.

  - Click **Archived sales orders** to view all of the customer’s sales orders, including order details, that have been archived.

## Catalog

The **Catalog** group has just one button: **Send catalog**. When a customer requests a catalog, click **Send catalog** to complete this task.

1.  On the **Action Pane**, click **Send catalog**.

2.  In the **Send catalog** form, in the **Send** column, select the check box for the catalog or catalogs that you want to send to the customer.

3.  Click **Send**, and then click **OK**.

The selected catalog or catalogs will be sent to the customer.

## Case

The **Cases** group has just one button: **Cases**. Click this button to view or change the details of an existing customer case, or create a new customer case.

Click **Cases**, and then select one of the following:

  - **View customer cases** – Opens the **Case** form, where you can view or update a customer case.

  - **Create case** – Opens the **New case** form, where you can create a new case for the customer. For more information about how to create a case, see [Create a case](create-a-case.md).

## View hot alerts for customer cases

You can create priorities and assign them to different entities in Microsoft Dynamics AX. You can assign priorities of high, medium, low, or you can assign priorities on a numerical scale, for example, 1 through 5 where 1 is low priority and 5 is high priority. You create priorities in the **Priority** form (**Sales and marketing** \> **Setup** \> **Leads** \> **Priority**), and you can mark one or more priorities as a hot alert. When you assign a priority to a customer case, you can view whether the priority is marked as a hot alert. If you assign a priority that is marked as a hot alert to a customer case, and you search for that customer by using the **Customer service** form, the **Hot alerts** form opens automatically, and you can view the notes that have been entered for the case. You can also click **Edit** to update the case details.

  - To remove a hot alert from a case – In the **Case** form, change the priority of the case to a priority that is not a hot alert.

  - To add a hot alert to a case – In the **Case** form, change the priority of the case to a priority that is marked as a hot alert.

  


