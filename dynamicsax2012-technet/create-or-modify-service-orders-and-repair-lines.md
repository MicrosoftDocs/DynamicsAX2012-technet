---
title: Create or modify service orders and repair lines
TOCTitle: Create or modify service orders and repair lines
ms:assetid: aa86b1ec-ebeb-473b-8dd2-d5cee0906b66
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271620(v=AX.60)
ms:contentKeyID: 36384252
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- EPServiceOrderCreate
- EPServiceOrderCreateTunnel
- EPServiceOrderEdit
- EPServiceOrderLineCreate
- EPServiceRepairLineCreate
- EPServiceRepairLineEdit
---

# Create or modify service orders and repair lines 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create a service order and its service repair lines at the same time by using the Service Order Wizard. Alternatively, you can create a service order that does not include repair lines by using the **Create service order** page. You also use the **New service order line** page to add service order lines to a service order, and the **Edit service order** page to change an existing service order.


> [!NOTE]
> <P>Before you can add repair lines to a service order, the service object relation must be set up in the Microsoft Dynamics AX client. For information about service object relations, see <A href="view-service-object-relations.md">View service object relations</A>.</P>



## Create a service order and repair lines

If you want to create a service order and service repair lines at the same time, you must use the Service Order Wizard. You can add more repair lines later.

1.  Click **Service management** on the top link bar, and then click **Service orders** on the Quick Launch.

2.  On the **Service orders** page, on the **Action Pane**, click **Service order wizard**.

3.  On the **New service order** page, in the **Service agreement** field, select the service agreement that the service order is based on.

4.  The following step is optional. In the **Description** field, change the description of the service agreement.

5.  In the **Preferred service time** fields, enter the date and time of day to perform the service and then click **Next**.

6.  On the next page, in the **Service name** field, select the location where the service occurs.
    

    > [!NOTE]
    > <P>If a service agreement is selected, the field displays information that is specified for the selected service agreement. You can change the information for the service order.</P>



7.  In the **Delivery address** field, select the address where the service occurs.
    

    > [!NOTE]
    > <P>The full delivery address displays in the <STRONG>Address</STRONG> field. You cannot change the information for the delivery address.</P>



8.  Click **Next**.

9.  On the next page, in the **Service object relation** field, select the item to repair.

10. In the **Service responsible** field, select the worker who manages service for the customer.

11. In the **Condition** field, select the condition that is present when the malfunction occurs.

12. In the **Symptom area** field, select a general category for the malfunction.

13. In the **Symptom code** field, select a specific characteristic of the malfunction.

14. In the **Title** field, enter a title for the repair line, and then enter any additional information about the repair in the **Text** field.

15. Click **Finish** to create the service order.

## Create a service order and add lines later

If you want to create a service order and then add repair lines later, use the **Create service order** page.

1.  Click **Service management** on the top link bar, and then click **Service orders** on the Quick Launch.

2.  On the **Service orders** page, on the **Action Pane**, click **Create service order**.

3.  On the **New service order** page, on the **Identification** FastTab, in the **Customer account** field, select the customer account for the service order.

4.  In the **Service agreement** field, select the service agreement that the service order is based on.

5.  If the service order is part of a project, select the project in the **Project ID** field.

6.  In the **Description** field, enter a description of the service order.
    

    > [!NOTE]
    > <P>If a service agreement is selected, the field displays information that is specified for the selected service agreement. You can change the information for the service order.</P>



7.  In the **Preferred service time** fields, enter the date and time of day to perform the service.
    
    The **Sign off** field indicates whether the service order has been completed.

8.  In the **Service responsible** field, select the worker who is responsible for the service.

9.  In the **Preferred technician** field, select the worker who you want to assign the service order to.

10. On the **Address and contact** FastTab, enter the address information, and select the contact person.
    

    > [!NOTE]
    > <P>If a service agreement is selected, the field displays information that is specified for the selected service agreement. You can change the information for the service order.</P>



11. Click **Save and close** to create the service order.

## Add repair lines to a service order

You can use service repair lines to record the repair process for the service objects that are associated with service orders. You can use repair lines to record the symptoms, diagnosis, and the solution for the repair issues that are related to a service object.

1.  Click **Service management** on the top link bar, and then click **Service orders** on the Quick Launch.

2.  On the **Service orders** page, select a service order, and then on the **Action Pane**, click **Repair lines**.

3.  On the **View service repair lines** page, on the **Action Pane**, click **Service repair line**.

4.  On the **New service repair line** page, on the **Administration** FastTab, in the **Service object relation** field, select the item to repair.

5.  In the **Repair stage** field, select the repair stage that describes the status of the repair.

6.  In the **Technician** field, select the worker who is performing the repair.

7.  On the **Symptom and diagnosis** FastTab, in the **Condition** field, select the condition under which the malfunction occurs.

8.  In the **Symptom area** field, select a general category for the malfunction.

9.  In the **Symptom code** field, select a specific characteristic of the malfunction.

10. In the **Diagnosis area** field, select the diagnosis of the required repair.

11. In the **Diagnosis code** field, select the specific repair activity.

12. In the **Note** section, enter a description for the repair, and then enter any additional information about the repair in the **Text** field.

13. Click **Save and close** to create the repair line.

## Add lines to a service order

Each service order contains one or more service order lines. These lines provide specific details about the amount and type of work that the service technician must perform, and the status of the service task.

1.  Click **Service management** on the top link bar, and then click **Service orders** on the Quick Launch.

2.  On the **Service orders** page, click the link for the service order that you want to add lines to.

3.  On the **View service order** page, on the **Action Pane**, click **Edit**.

4.  On the **Edit service order** page, click the **Lines** FastTab, and then click **Add**.

5.  On the **New service order line** page, in the **Transaction type** field, select whether the service order line is for an hour, expense, item, or fee transaction, and then click **Next**.

6.  The fields on the next page vary, depending on the transaction type that you selected for the line. Depending on the selection in the **Transaction type** field, provide the following information, and then click **Next**:
    
      - Hour transactions – Provide information about the worker, category, service object relation, and service task. Additionally, provide information about the number of hours that have been incurred. You can also enter notes about the transaction.
    
      - Expense transactions – Provide information about the worker, category, service object relation, and service task. Additionally, provide information about the number of times that a cost has been incurred, and the cost price. You can also enter notes about the transaction.
    
      - Item transactions – Provide the item number, and specify the configuration, size, and color of the item. Click **Next**. Enter or select information about the category, service object relation, and service task. Enter any notes, and the unit and quantity of the item.
    
      - Fee transactions – Provide information about the worker, category, service object relation, and service task. Enter any notes and the number of fees that have been incurred.
        

        > [!NOTE]
        > <P>For more information about the transaction types, see <A href="about-project-transactions.md">About project transactions</A>.</P>



7.  Click **Finish** to create the service order line.

## Modify a service order or service order line

1.  Click **Service management** on the top link bar, and then click **Service orders** on the Quick Launch.

2.  On the **Service orders** page, select a service order, and then on the **Action Pane**, click **Edit**.

3.  On the **Edit service order** page, make the necessary changes to the service order header.

4.  Make the necessary changes to the service order lines. To save changes that you make to repair lines, click the **Update** icon for each service order line.
    

    > [!NOTE]
    > <P>If a service order line has been completed, and sign-off is required for each line, select the <STRONG>Sign off</STRONG> check box for the line.</P>



5.  Click **Save and close**.

## Modify a repair line

1.  Click **Service management** on the top link bar, and then click **Service orders** on the Quick Launch.

2.  On the **Service orders** page, select a service order, and then on the **Action Pane**, click **Repair lines**.

3.  On the **View service repair lines** page, select the repair line, and then on the **Action Pane**, click **Edit**.

4.  On the **Edit repair line** page, make the necessary changes, and then click **Save and Close**.

## See also

[About service agreements and service orders](about-service-agreements-and-service-orders.md)

[View service orders](view-service-orders.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

