---
title: Configure security for integration ports
TOCTitle: Configure security
ms:assetid: fec2d03e-d8bf-41c2-8fbd-1cb565b9449b
ms:mtpsurl: https://technet.microsoft.com/library/Hh202131(v=AX.60)
ms:contentKeyID: 35949394
author: Khairunj
ms.author: daxcpft
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Configure security for integration ports 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>This topic describes one step in the process for managing integration ports. For more information, see <A href="managing-integration-ports.md">Managing integration ports</A>.</P>



This topic describes how to configure security settings in services and Application Integration Framework (AIF) by using either the **Inbound ports** form or the **Outbound ports** form. To open these forms, follow one of these steps.

  - Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

  - Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Outbound ports**.

Use the **Security** FastTab to specify how the integration port enforces access permissions.

## Configure restrictions on port access

The Microsoft Dynamics AX role-based security framework is applicable to all service operations that are exposed from an integration port. For more information about role-based security, see [About role-based security](role-based-security-in-microsoft-dynamics-ax.md). You can specify the following additional restrictions on access to the integration port:

  - **Restrict to partition:** – By default, the integration port processes all documents, regardless of the partition key that is specified in the document's XML. To limit the use of the integration port to a specific partition, select the partition. For each partition, the list shows the partition key and name.
    

    > [!NOTE]
    > <P>This control is available only if Microsoft Dynamics AX 2012 R2 is installed.</P>



  - **Restrict to company** – By default, the integration port processes all documents, regardless of the company ID that is specified in the document's XML. To limit the use of the integration port to a specific company, select the name of the company.
    
    In Microsoft Dynamics AX 2012 R2, you must select a partition before you can select a company.

  - **Restrict users** – By default, all users have permission to use the integration port. Select this check box to limit the use of the inbound port to specific users or user groups. When this check box is selected, only the users who are listed in the **Authorized users** form can submit requests to the inbound integration port. To specify the list of users or user groups that have permission to use the integration port, follow these steps.
    
    1.  Click **Authorized users**.
    
    2.  In the **Authorized users** form, click **New** to add a new user or user group.
    
    3.  In the **User type** list, select **User** or **User group**.
    
    4.  The **Application user or group** list displays the IDs and names of users or user groups. Select the user or user group to which to grant permission to access the integration port.
    
    5.  To revoke permission to access the integration port, select a user or user group, and then click **Delete**.
    
    6.  Close the form.

## Configure trusted intermediary users

Trusted intermediary users, or trusted intermediaries, are middleware applications that can submit requests to an integration port on behalf of another user, after they have authenticated the other user's identity. Trusted intermediaries are represented by Microsoft Dynamics AX users or user groups that are authorized to submit inbound requests. By using trusted intermediaries, you can delegate authentication to a trusted source. However, authorization continues to be managed by Microsoft Dynamics AX through the role-based security framework.

Trusted intermediaries are typically used for business-to-business data exchanges. A trusted intermediary must be an Active Directory user. A trusted intermediary can impersonate any other Microsoft Dynamics AX user. A trusted intermediary can even impersonate a claims user. For more information about users, see [About role-based security in services and AIF](about-role-based-security-in-services-and-aif.md).

To enable trusted intermediaries, follow these steps.

1.  Select **Allow trusted intermediary to impersonate**.

2.  Click **Trusted intermediary users**.

3.  In the **Trusted intermediaries** form, click **New** to add a new user or user group.

4.  In the **User type** list, select **User** or **User group**.

5.  The **Application user or group** list displays the IDs and names of users or user groups. Select the user or user group to which to grant permission to access the integration port.

6.  To revoke permission for a trusted intermediary to access the integration port on behalf of an external user, select a user or user group, and then click **Delete**.

7.  Close the form.

## Next steps

To use the port, follow these steps.

1.  Click **Activate** to enable the port.
    

    > [!WARNING]
    > <P>If you activate an integration port, all integration ports on the instance of Application Object Server (AOS) are reactivated. Do not click <STRONG>Activate</STRONG> when integration ports are processing messages.</P>



2.  Close the **Inbound ports** form or the **Outbound ports** form.

