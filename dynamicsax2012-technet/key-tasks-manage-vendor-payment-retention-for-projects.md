---
title: 'Key tasks: Manage vendor payment retention for projects'
TOCTitle: 'Key tasks: Manage vendor payment retention for projects'
ms:assetid: b84c57d9-256b-4a54-b223-c6afcdb10970
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh351823(v=AX.60)
ms:contentKeyID: 36676406
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- project add-in
- vendor payments
- vendor retention
- customer payments
- retention terms
- partial payment
- retention details
---

# Key tasks: Manage vendor payment retention for projects 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Your organization might want to retain part of the payments to a vendor for a project. For example, you can make sure that the products from the vendor meet your expectations before you pay the vendor.

When you negotiate with a vendor, you can specify the vendor payment retention terms. You can specify the retention as a percentage of the contract with a vendor or as a specific amount. As the vendor delivers items and services, you deduct the specified retention percentage or amount from your payment to the vendor. When the project is completed or reaches an interim stage specified in the contract with the vendor, you release the retained amount and create a payment to the vendor.

## What do you want to do?

Learn more about...

Create vendor retention terms

Set up vendor retention terms for the project

Review customer payment information and pay the vendor

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About vendor payment retention for projects](about-vendor-payment-retention-for-projects.md)

## Create vendor retention terms

Use the **Vendor retention terms** form to set up and maintain retention terms for vendor payments. You can enter the percentage of a vendor payment to retain and the percentage of the previously retained amounts to release. Amounts are automatically retained on vendor invoices until the contract reaches the specified state of completion. After you have set up retention terms for a vendor, you can apply them to any project on which the vendor works.

1.  Click **Project management and accounting** \> **Setup** \> **Retention** \> **Vendor payment retention terms**.

2.  Click **New** to add a new vendor retention term. The **Rule ID** value for the new term is automatically entered. Enter a descriptive name in the **Description** field.

3.  On the **Terms** FastTab, click **Add line** to enter a vendor retention term.

4.  In the **Percentage of units delivered** field, enter a percentage of completion for the rule. Amounts are automatically retained on vendor invoices until the project stage of completion is equal to the percentage that you enter. For example, if you enter 50.00, amounts are retained until the project is 50 percent completed.

5.  In the **Percentage to retain** field, enter the percentage of a vendor invoice amount to retain. For example, if you enter 10.00 in this field, 10 percent of the amount on vendor invoices is retained until the project reaches the percentage of completion that you select in the **Percentage of units delivered** field.

6.  In the **Percentage to release** field, enter the percentage of any previously retained amounts to release at the selected level of project completion.
    

    > [!NOTE]
    > <P>If you have more than one milestone for different levels of project completion, enter a separate vendor retention term line for every retention rule. Each line can specify a different percentage to retain and a different percentage to release for each designated level of project completion.</P>



Back to top

## Set up vendor retention terms for the project

Set up the vendor retention terms that apply to the project. The vendor retention terms are also displayed on purchase orders that you create for the vendor.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open a project from the project list page.

2.  On the **Vendor agreements** FastTab, click **Add line**.

3.  In the **Account code** field, select one of the following options:
    
      - **Table** – The vendor retention terms apply to a single vendor.
    
      - **Group** – The vendor retention terms apply to all vendors in a vendor group.
    
      - **All** – The vendor retention terms apply to all vendors.

4.  In the **Vendor/Vendor group** field, select the vendor or vendor group to which the vendor retention terms apply. If you selected **All** in the previous step, this field is unavailable.

5.  In the **Vendor retention terms** field, select the rule ID for the retention terms to apply to this vendor.

6.  If the project also has pay-when-paid (PWP) terms set up for the vendor, in the **PWP threshold percentage** field, enter the threshold percentage for the project.

Back to top

## Review customer payment information and pay the vendor

You can review vendor payment retention details in the **Vendor invoices with retention** form. You can also use the **Vendor invoices with retention** form to release all or part of the retained amounts when the project is completed, or when a defined percentage of the work is completed.

1.  Use one of the following navigation paths to open the **Vendor invoice** form. By default, the form opens in line view.
    
      - Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**. Select an invoice. On the **Action Pane**, click **Edit**. Alternatively, you can double-click an invoice to open the **Vendor invoice** form.
    
      - Click **Accounts payable** \> **Periodic** \> **Maintain vendor invoices**.
    
      - Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order. On the **Action Pane**, click the **Invoice** tab. In the **Generate** group, click **Invoice** to create an invoice from the selected purchase order.
    
      - Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Select a vendor account. On the **Action Pane**, on the **Invoice** tab, in the **New** group, click **Invoice** to create an invoice.
    
      - Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice approval journal**. Click **Lines**. Click **Functions** \> **Purchase order**, and then click **OK**.

2.  In the **Vendor invoice** form, on the **Line details** FastTab, on the **Line details** tab, in the **Vendor payment retention** section, review the vendor retention details.
    

    > [!NOTE]
    > <P>The <STRONG>Vendor payment retention</STRONG> fields are not available if a vendor invoice was created in versions of Microsoft Dynamics AX earlier than Microsoft Dynamics AX 2012.</P>



3.  If the project has been satisfactorily completed, and you want to release all of the amounts retained from payments to a vendor, select the **Release all retained amount** check box.

4.  To release part of the retained amounts for the vendor, in the **Release retained** section, in the **Percentage** field, enter a percentage of the retained amount to release. Alternatively, you can enter a specific amount of the retained amount to release in the **Amount** field.
    
    An invoice proposal for the released amount is created.

Back to top

## Find form help

[Vendor retention terms (form)](https://technet.microsoft.com/en-us/library/hh227442\(v=ax.60\))

[Vendor invoice (form)](https://technet.microsoft.com/en-us/library/hh209644\(v=ax.60\))

## Find related tasks

[Key tasks: Vendor invoices](key-tasks-vendor-invoices.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

