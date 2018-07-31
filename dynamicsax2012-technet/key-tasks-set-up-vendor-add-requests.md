---
title: 'Key tasks: Set up vendor add requests'
TOCTitle: 'Key tasks: Set up vendor add requests'
ms:assetid: 7cf92c10-76ff-4090-b9d6-15b97ffa6521
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209269(v=AX.60)
ms:contentKeyID: 36058271
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- vendors
- vendor request
- vendor requests
audience: Application User
ms.search.region: Global
---

# Key tasks: Set up vendor add requests 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Employees can submit requests to add a vendor to the vendor master for their legal entity. Employees may want to add a new vendor if, for example, they want to purchase a product that is not offered by a vendor in the company’s current vendor master. New vendor requests are submitted in the Employee services portal in Enterprise Portal for Microsoft Dynamics AX.


> [!NOTE]
> <P>Only users who are assigned the Employee role in Microsoft Dynamics AX can submit a new vendor request in the Employee services portal.</P>



Before an employee can submit a request to add a new vendor, the **New vendor request** page must be set up in Enterprise Portal. An administrator sets up the page by using the **Vendor request configurations** form in the Microsoft Dynamics AX client.

When an employee submits a new vendor request, the request is routed to an approver through workflow. If the request is approved, the prospective vendor is invited to submit a full profile on the **Vendor registration** page.

Before vendors can complete the registration process, the **Vendor registration** page must be set up in Enterprise Portal. An administrator sets up the page by using the **Vendor request configurations** form in the Microsoft Dynamics AX client.

## What do you want to do?

Learn more about...

Configure the New vendor request page for Enterprise Portal

Configure the Vendor registration page for Enterprise Portal

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Configuring Enterprise Portal for vendor requests](configuring-enterprise-portal-for-vendor-requests.md)

## Configure the New vendor request page for Enterprise Portal

You define the fields that are displayed and required on the **New vendor request** page in Enterprise Portal by using the **Vendor request configurations** form in the Microsoft Dynamics AX client. You also use this form to set up other system checks for new vendor requests.

You use the **Vendor add request** request type to set up the **Vendor registration** page. You can create multiple profiles for this request type. This allows you create different profiles for different companies.

1.  Click **Procurement and sourcing** \> **Setup** \> **Vendors** \> **Vendor request configurations**.

2.  In the **Vendor request configurations** form, in the **Request type** field, select **Vendor add request**.

3.  On the **Fields** FastTab, indicate whether each business justification field that appears in the list should be displayed, hidden, or required on the **New vendor request** page. If you want the requester to specify a procurement category, select the **Require procurement category** check box.

4.  On the **Companies** FastTab, select the companies to which the profile applies.
    

    > [!NOTE]
    > <P>The default profile applies to all companies that do not have a defined profile. Specific companies cannot be selected for this profile.</P>



5.  If you want to display specific text on the vendor add request, on the **Content** FastTab, select the **Select to display defined text** check box. Enter the text in the **General text** box. For example, this text might contain information about terms, processes, or corporate policies.

6.  On the **System checks** FastTab, select the system checks that should be performed on new vendor requests. For example, the system can flag new vendor requests that reference a vendor that is located in a country or region that is embargoed.

7.  On the **Questionnaires** FastTab, select one or more questionnaires that you want employees to complete during the request process. You can specify different questionnaires for each profile.

Back to top

## Configure the Vendor registration page for Enterprise Portal

You use the **Vendor add application** request type to set up the **Vendor registration** page. Prospective vendors use this page when they respond to a vendor registration solicitation. You can create multiple profiles for the **Vendor add application** request type. This allows you create different profiles for different countries/regions. For example, in a profile for France, you might require the vendor to provide their French Siret number.

1.  Click **Procurement and sourcing** \> **Setup** \> **Vendors** \> **Vendor request configurations**.

2.  In the **Vendor request configurations** form, in the **Request type** field, select **Vendor add application**.

3.  Click **New**.
    

    > [!WARNING]
    > <P>If you do not click <STRONG>New</STRONG>, the changes that you make will affect the default profile.</P>



4.  On the **Fields** FastTab, indicate whether each business information field that appears in the list should be displayed, hidden, or required on the **Business information** FastTab on the **Vendor registration** page.
    
    If you do not want to display the **Business information** tab on the **Vendor registration** page, select the **Hide Business information FastTab** check box.

5.  On the **Countries/regions** FastTab, select the countries/regions to which the profile applies.
    

    > [!NOTE]
    > <UL>
    > <LI>
    > <P>The country/region that is identified in the primary address for the vendor is used to determine which vendor registration profile to display on the <STRONG>Vendor registration</STRONG> page.</P>
    > <LI>
    > <P>The default profile applies to all countries/regions that do not have a defined profile. Specific countries/regions cannot be selected for this profile.</P></LI></UL>



6.  If you want to display specific text on the **Vendor registration** page, on the **Content** FastTab, select the **Select to display defined text** check box. Enter the text in the **General text** box. For example, this text might contain privacy and disclosure information that the vendor must acknowledge before submitting the registration.

7.  On the **System checks** FastTab, select the system checks that should be performed on vendor registrations. For example, the system can flag vendor a registration that is submitted by a vendor who is located in a country or region that is embargoed.

8.  On the **Questionnaires** FastTab, select one or more questionnaires that you want vendors to complete during the request process. You can specify different questionnaires for each profile.

Back to top

## Find form help

[New vendor request (form)](https://technet.microsoft.com/en-us/library/hh242728\(v=ax.60\))

[Vendor requests (list page)](https://technet.microsoft.com/en-us/library/hh242710\(v=ax.60\))

[Vendor request configurations (form)](https://technet.microsoft.com/en-us/library/hh209430\(v=ax.60\))

## Find related tasks

[Configuring Enterprise Portal for vendor requests](configuring-enterprise-portal-for-vendor-requests.md)

  


