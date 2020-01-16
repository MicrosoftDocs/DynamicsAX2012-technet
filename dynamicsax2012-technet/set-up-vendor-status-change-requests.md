---
title: Set up vendor status change requests
TOCTitle: Set up vendor status change requests
ms:assetid: 531a77f5-f609-4d67-8470-2875e53401ba
ms:mtpsurl: https://technet.microsoft.com/library/Hh208949(v=AX.60)
ms:contentKeyID: 36057293
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up vendor status change requests 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The hold status for a vendor determines the types of transactions that are permitted for the vendor in your organization. For example, a vendor hold might prevent employees from creating purchase orders for a vendor. An employee can request to change the hold status for a vendor. To request the change, the employee submits a request in the Employee services portal in Enterprise Portal for Microsoft Dynamics AX.

Employees create vendor status change requests on the **Vendor status change request** page in the Employee services portal. This topic explains how to set up the **Vendor status change request** page for legal entities in your organization.

## Configure a status change request page

Use this procedure to define the appearance of the **Vendor status change request** page in the Employee services portal. You can create multiple profiles for vendor status change requests. This lets you customize the appearance of the request page for specific legal entities. Any legal entity that is not identified in a custom profile uses the default profile. The default profile is not specific to any legal entity.

1.  Click **Procurement and sourcing** \> **Setup** \> **Vendors** \> **Vendor request configurations**.

2.  In the **Vendor request configurations** form, in the **Request type** field, select **Vendor status change request**, and then click **New**.

3.  On the **Details** FastTab, enter a unique name and optional description for the configuration.

4.  On the **Fields** FastTab, indicate whether each field in the list is displayed, hidden, or required for a vendor status change request. By default, all fields are displayed and no fields are required.

5.  On the **Companies** FastTab, in the **Available companies** list, select the legal entities that will use this vendor status change request profile. Then, click the arrow to move them to the **Selected companies** list.

6.  On the **Content** FastTab, select the **Select to display defined text** check box if you want to display instructions or other text to employees. Enter the text in the **General text** field.

7.  If you want employees to acknowledge that they have read and agree to any terms and conditions that are specified in the **General text** field, select the **Select to display the acknowledgement check box** check box.

8.  If you selected to display the **Select to display the acknowledgement check box** check box, enter a label for the check box. For example, enter **I have read the policies for vendor status change requests and agree to comply with the policies.**

## See also

[About vendor request configuration](about-vendor-request-configuration.md)

[Configuring Enterprise Portal for vendor requests](configuring-enterprise-portal-for-vendor-requests.md)

[Vendor request configurations (form)](https://technet.microsoft.com/library/hh209430\(v=ax.60\))

  


