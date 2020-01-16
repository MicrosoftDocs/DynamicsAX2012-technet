---
title: Create a project quotation
TOCTitle: Create a project quotation
ms:assetid: d1440fe5-cea8-486f-952a-5b5a02bf0215
ms:mtpsurl: https://technet.microsoft.com/library/Bb220756(v=AX.60)
ms:contentKeyID: 36811431
author: Khairunj
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- project quotation
- customer
- quotation
- prospect
- create quotation
audience: Application User
ms.search.region: Global
---

# Create a project quotation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In the initial sales phase of a project, a project quotation enables you to provide a customer with a binding offer.

A quotation can encompass elements such as the items and services that are quoted, basic contact information, special trade agreements and discounts, and possible taxes and surcharges.

Use the following procedures to create project quotations.

## Create a quotation for a customer

1.  Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**.

2.  On the **Action Pane**, on the **Quotation** tab, in the **New** group, click **Project quotation**.

3.  In the **Create quotation** form, in the **Account type** field, select **Customer**.

4.  In the **Customer account** field, select the recipient of the quotation.

5.  If invoices are to be sent to an account that differs from the customer account that you selected, select the alternate account in the **Invoice account** field.

6.  In the **Contact** field, select the name of the person in the customer organization who should be contacted about this quotation.

7.  Optional: Specify or change other project quotation details on the **General** FastTab, **Shipping and delivery** FastTab, and **Administration** FastTab.
    

    > [!TIP]
    > <P>For information about the fields on the FastTabs, see <A href="https://technet.microsoft.com/library/aa557295(v=ax.60)">Project quotation (form)</A>. For information about how to use the <STRONG>Template</STRONG> FastTab, see the procedure “Create a quotation from a template” in this topic.</P>



## Create a quotation for a prospect

1.  Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**.

2.  On the **Action Pane**, on the **Quotation** tab, in the **New** group, click **Project quotation**.

3.  In the **Create quotation** form, in the **Account type** field, select **Prospect**.
    

    > [!NOTE]
    > <P>Before the quotation can be confirmed or linked to a project, you must convert a prospect to a customer. In the <STRONG>Project quotation</STRONG> form, on the <STRONG>Action Pane</STRONG>, on the <STRONG>Follow up</STRONG> tab, click <STRONG>Convert to customer</STRONG>.</P>



4.  In the **Prospect** field, select the recipient for the quotation.

5.  In the **Contact** field, select the name of the contact person in the prospect organization.

6.  Optional: Specify or change other project quotation details on the **Template** FastTab, **General** FastTab, **Shipping and delivery** FastTab, and **Administration** FastTab.
    

    > [!TIP]
    > <P>For information about the fields on the FastTabs, see <A href="https://technet.microsoft.com/library/aa557295(v=ax.60)">Project quotation (form)</A>. For information about how to use the <STRONG>Template</STRONG> FastTab, see the procedure “Create a quotation from a template” in this topic.</P>



## Create a quotation from a template

Although templates are generally used to create quotations in a batch, you can also use a template to create a single quotation.

1.  To create a quotation for a customer from a template, follow the procedure “Create a quotation for a customer” in this topic, but do not click **OK**.
    
    –or–
    
    To create a quotation for a prospect from a template, follow the procedure “Create a quotation for a customer” in this topic, but do not click **OK**.

2.  On the **Template** FastTab, follow these steps:
    
    1.  In the **Group ID** field, select the template group.
    
    2.  In the **Template name** field, select the template that the quotation will be based on.
    
    3.  In the **Calculation method** field, select which prices you want to use for the quotations.
        
          - **Based on current values** – Use the prices that are on the item card.
        
          - **Based on template values** – Use the prices that are on the selected quotation template.

## Create quotations in a batch

If you need multiple identical quotations for various sales targets, you can create the quotations at the same time instead of one by one. When you create quotations in a batch, you must use a quotation template.

1.  Click **Project management and accounting** \> **Periodic** \> **Quotations** \> **Mass create quotations**.

2.  In the **Mass create quotations** form, in the **Account type** field, select **Customer** or **Prospect**.

3.  In the **Group ID** field, select a template group.

4.  In the **Template name** field, select a template.

5.  In the **Calculation method** area, select how you want to calculate prices for the quotations.
    
      - **Based on current values** – Use the prices that are on the item card.
    
      - **Based on template values** – Use the prices that are on the selected quotation template.

6.  In the **Expiration date** field, select the date on which the quotations will expire.

7.  To modify and filter the query that is used to generate the quotations, click the **Select** button.
    

    > [!NOTE]
    > <P>All quotations that are created in batches are sent to the contact person for the customer or account.</P>
    > <P>If no contact persons are selected or filtered, project quotations for the customer or account will be sent to all contact persons that are associated with this customer or account.</P>
    > <P>If no contact persons are associated with the customer or account, no project quotations will be created.</P>



8.  Click **OK** in the **Inquiry** dialog box.

9.  Click **OK** in the **Mass create quotations** form.

  


