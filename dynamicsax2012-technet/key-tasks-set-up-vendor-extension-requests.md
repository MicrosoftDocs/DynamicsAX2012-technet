---
title: 'Key tasks: Set up vendor extension requests'
TOCTitle: 'Key tasks: Set up vendor extension requests'
ms:assetid: e73c2b14-d8cb-491b-ae1e-b74db0319f05
ms:mtpsurl: https://technet.microsoft.com/library/Hh227460(v=AX.60)
ms:contentKeyID: 36059812
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- vendors
- vendor portal
- add to another legal entity
- set up vendor extension request
- vendor extension
audience: Application User
ms.search.region: Global
---

# Key tasks: Set up vendor extension requests 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Employees of your organization might want to work with a vendor who is already doing business with another legal entity in your organization. An employee can submit a request to authorize the vendor to do business with another legal entity in the organization. An employee can also request to add another employee, a sales prospect, or a customer as a vendor.

The employee creates the request on the **Vendor requests** page in the Employee services portal in Enterprise Portal for Microsoft Dynamics AX. The request includes contact information for the vendor and a justification for the request. The request appears in the **Vendor requests** list page in the Microsoft Dynamics AX client, and has a request type of **Extension**.

When an employee submits a vendor extension request, the request is routed, via workflow, to an approver. If an application or request is approved, an application is sent to the vendor. In the Vendor portal, the vendor reviews the request and confirms that they are willing to do business in the specified legal entity.

Before an employee can create a vendor extension request, you must set up the required and optional fields for the vendor request page in the Employee service portal. You must also set up the vendor extension application page. As part of this configuration, you can select system checks that compare the name and other information in the request to the list of current employees or disallowed vendors.

A default profile of the vendor extension request page is available for use by all legal entities in your organization. The default profile is displayed for all countries/regions. You cannot select a company or legal entity for the default profile. Instead, you can create a custom profile for a legal entity in your organization.

## What do you want to do?

Learn more about...

Configure the vendor extension request page

Configure the vendor extension application

Find form help

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About vendor request configuration](about-vendor-request-configuration.md)

[Configuring Enterprise Portal for vendor requests](configuring-enterprise-portal-for-vendor-requests.md)

## Configure the vendor extension request page

Use this procedure to define the appearance of the vendor extension request page in the Employee services portal in Enterprise Portal.

1.  Click **Procurement and sourcing** \> **Setup** \> **Vendors** \> **Vendor request configurations**.

2.  In the **Vendor request configurations** form, in the **Request type** field, select **Vendor extension request**, and then click **New**.

3.  On the **Details** FastTab, in the **Configuration name** field, enter a unique name for the configuration profile. In the optional **Description** field, you can enter additional details about the profile.

4.  On the **Fields** FastTab, select the fields that you want to display, hide, and make required for the new profile. Select the **Require procurement category** check box to require the employee to specify a procurement category on the request. If the vendor confirms that they want to do business in the selected procurement categories and the extension is approved, the vendor is authorized to provide products in the specified category.

5.  On the **Companies** FastTab, select the legal entities that will use this extension request profile.

6.  On the **Content** FastTab, select the **Select to display defined text** check box if you want to display instructions, notifications, policies, or other text to the employee. Enter the text in the **General text** field.

7.  If you want an employee to acknowledge that the employee has read or agrees to any terms and conditions that you enter in the **General text** field, select the **Select to display the acknowledgement check box** check box. If you select the check box, enter a label for the check box. For example, enter **I have read the policies for vendor extension requests.**

8.  On the **System checks** FastTab, you can specify the system checks that you want to perform for an extension request. For example, the system can determine whether the vendor is located in a country or region that is embargoed, and whether the vendor is a disallowed vendor in the selected legal entity.

9.  On the **Questionnaires** FastTab, select a questionnaire that the employee must complete during the request process. Each legal entity may have its own questionnaire for an extension request.

Back to top

## Configure the vendor extension application

Use this procedure to define the appearance of the vendor extension request page in the Vendor portal.

1.  Click **Procurement and sourcing** \> **Setup** \> **Vendors** \> **Vendor request configurations**.

2.  In the **Vendor request configurations** form, in the **Request type** field, select **Vendor extension application**, and then click **New**.

3.  On the **Details** FastTab, in the **Configuration name** field, enter a unique name for the configuration profile. In the optional **Description** field, you can enter additional details about the profile.

4.  On the **Fields** FastTab, select the fields that you want to display, hide, and make required for the new profile. Select the **Hide Business information FastTab** check box to hide the **Business information** FastTab on the vendor extension application.

5.  On the **Countries/regions** FastTab, select the country or region that will use this extension request profile.

6.  On the **Content** FastTab, select the **Select to display defined text** check box if you want to display instructions, terms and conditions, or other text to the vendor. Enter the text in the **General text** field.

7.  If you want a vendor to acknowledge that the vendor has read or agrees to any terms and conditions that you enter in the **General text** field, select the **Select to display the acknowledgement check box** check box. If you select the check box, enter a label for the check box. For example, enter **I agree to comply with these terms and conditions.**

8.  On the **System checks** FastTab, you can specify the system checks that you want to perform for an extension request. For example, the system can determine whether the vendor is located in a country or region that is embargoed, and whether the vendor is a disallowed vendor in the selected legal entity.

9.  On the **Questionnaires** FastTab, select a questionnaire that the vendor must complete during the approval process. Each country/region may have its own questionnaire for an extension request.

Back to top

## Find form help

[Vendor request configurations (form)](https://technet.microsoft.com/library/hh209430\(v=ax.60\))

  


