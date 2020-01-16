---
title: 'Key tasks: Set up vendor category requests'
TOCTitle: 'Key tasks: Set up vendor category requests'
ms:assetid: e0a34904-3bbc-40bd-9324-a5d09c49f21d
ms:mtpsurl: https://technet.microsoft.com/library/Hh227421(v=AX.60)
ms:contentKeyID: 36059704
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- vendors
- employee request
- set up vendor request
- vendor portal
- vendor category request
- category request
- category requests
- vendor categories
- vendor category
audience: Application User
ms.search.region: Global
---

# Key tasks: Set up vendor category requests 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Vendors who are approved to do business in a procurement category in your organization might want to extend their business to additional procurement categories. The vendor makes the category application request in the Vendor portal in Enterprise Portal for Microsoft Dynamics AX.

Employees can also submit a request to allow vendors to do business in additional categories. The employee creates the request on the **Category request** page in the Employee services portal in Enterprise Portal.

Vendor category applications and employee category requests are routed, via workflow, to an approver. If an application or request is approved, a category confirmation is sent to the vendor. The vendor must complete the application and submit it for approval. If the application or request is rejected, the status of the request in the Employee services portal will change to **Request rejected**.

Before the vendor can create a category application, you must set up the required and optional fields on the category application page that appears in the Vendor portal. You must also set up the employee category request page and the vendor category confirmation page.

A default profile is available for each page. The default profile is displayed for all countries/regions. You can create a custom profile for specific countries/regions.


> [!NOTE]
> <P>You cannot select a country/region for the default profile.</P>



## What do you want to do?

Learn more about...

Configure the vendor category application page

Configure the category request page

Configure the category request confirmation page

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Manage vendor requests overview](manage-vendor-requests-overview.md)

[About workflow statuses for category extension requests](about-workflow-statuses-for-category-extension-requests.md)

## Configure the vendor category application page

Use this procedure to define the appearance of the vendor category application page in the Vendor portal. A vendor category application is a request that a vendor submits to do business in additional procurement categories in your organization.

1.  Click **Procurement and sourcing** \> **Setup** \> **Vendors** \> **Vendor request configurations**.

2.  In the **Vendor request configurations** form, in the **Request type** field, select **Vendor category application**, and then click **New**.

3.  On the **Details** FastTab, in the **Configuration name** field, enter a name for the configuration profile. The name for the profile must be unique.

4.  Optional: In the **Description** field, enter additional details about the profile.

5.  On the **Countries/regions** FastTab, in the **Available countries/regions** pane, select the countries/regions to which the profile applies.

6.  On the **Content** FastTab, select the **Select to display defined text** check box if you want to display instructions, terms and conditions, policies, or other text to the vendor. Enter the text in the **General text** field.

7.  If you want a vendor to acknowledge that the vendor read or agrees to any terms and conditions that you enter in the **General text** field, select the **Select to display the acknowledgement check box** check box.

8.  If you selected to display the acknowledgement check box, enter a label for the check box. For example, enter **I agree to comply with these terms and conditions.**

Back to top

## Configure the category request page

Use this procedure to define the appearance of the vendor category request page in the Employee services portal. The vendor category request is a request that an employee submits to allow a vendor to do business in additional procurement categories in your organization.

1.  Click **Procurement and sourcing** \> **Setup** \> **Vendors** \> **Vendor request configurations**.

2.  In the **Vendor request configurations** form, in the **Request type** field, select **Vendor category request**, and then click **New**.

3.  On the **Details** FastTab, in the **Configuration name** field, enter a name for the configuration profile. The name for the profile must be unique.

4.  Optional: In the **Description** field, enter additional details about the profile.

5.  On the **Fields** FastTab, select a field, and then click **Displayed**, **Hidden**, or **Required**. An employee must complete all **Required** fields before they can submit the request.

6.  On the **Countries/regions** FastTab, in the **Available countries/regions** pane, select the countries/regions to which the profile applies.

7.  On the **Content** FastTab, select the **Select to display defined text** check box if you want to display instructions, terms and conditions, policies, or other text to the employee. Enter the text in the **General text** field.

8.  If you want an employee to acknowledge that the employee agrees to any terms, conditions, or policies that you enter in the **General text** field, select the **Select to display the acknowledgement check box** check box.

9.  If you selected to display the acknowledgement check box, enter a label for the check box. For example, enter **This request complies with the policies of our organization.**

Back to top

## Configure the category request confirmation page

Use this procedure to define the appearance of the vendor category confirmation page in the Vendor portal. A vendor category request confirmation is the vendor’s response to the category request that was submitted by the employee and approved by the reviewer. On this page in the Vendor portal, the vendor confirms their ability to do business in the categories that are specified in the category request that the employee submitted.

1.  Click **Procurement and sourcing** \> **Setup** \> **Vendors** \> **Vendor request configurations**.

2.  In the **Vendor request configurations** form, in the **Request type** field, select **Vendor category confirmation**, and then click **New**.

3.  On the **Details** FastTab, in the **Configuration name** field, enter a name for the configuration profile. The name for the profile must be unique.

4.  Optional: In the **Description** field, enter additional details about the profile.

5.  On the **Countries/regions** FastTab, in the **Available countries/regions** pane, select the countries/regions to which the profile applies.

6.  On the **Content** FastTab, select the **Select to display defined text** check box if you want to display instructions, terms and conditions, policies, or other text to the vendor. Enter the text in the **General text** field.

7.  If you want a vendor to acknowledge that the vendor agrees to any terms, conditions, or policies that you enter in the **General text** field, select the **Select to display the acknowledgement check box** check box.

8.  If you selected to display the acknowledgement check box, enter a label for the check box. For example, enter **I agree to comply with all terms and conditions for the requested categories.**

Back to top

## Find form help

[Vendor request configurations (form)](https://technet.microsoft.com/library/hh209430\(v=ax.60\))

## Find related tasks

[Maintain vendor category assignments](maintain-vendor-category-assignments.md)

  


