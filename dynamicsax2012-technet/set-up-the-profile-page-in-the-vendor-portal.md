---
title: Set up the Profile page in the Vendor portal
TOCTitle: Set up the Profile page in the Vendor portal
ms:assetid: a4a5862f-4811-4927-961b-5765d96d216d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242678(v=AX.60)
ms:contentKeyID: 36058859
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up the Profile page in the Vendor portal [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Approved vendors for your organization use the Vendor portal to maintain their company information, maintain company contacts, and manage transactions. The **Profile** page contains all of the critical vendor company details including address, banking, and company demographic information. The **Vendor profile** request type controls the settings and fields that appear on the **Profile** page in the Vendor portal.

You can define one or more vendor profile configurations. This lets you configure the **Profile** page based on the fields that you want to display and require by country/region.

## Configure the Profile page for the Vendor portal

1.  Click **Procurement and sourcing** \> **Setup** \> **Vendors** \> **Vendor request configurations**.

2.  In the **Request type** field, select **Vendor profile**.

3.  Click **New**.
    

    > [!NOTE]
    > <P>If you do not click <STRONG>New</STRONG>, the changes that you make will affect the default <STRONG>Vendor profile</STRONG> request type. The default profile is used by vendors in countries/regions for which you do not define a profile.</P>



4.  On the **Fields** FastTab, indicate whether each business information field that appears in the list should be displayed, hidden, or required on the **Profile** page.

5.  On the **Countries/regions** FastTab, select the countries/regions to which the profile applies.
    

    > [!NOTE]
    > <UL>
    > <LI>
    > <P>The country/region that is identified in the primary address for the vendor is used to determine which unsolicited vendor profile to display on the <STRONG>Profile</STRONG> page.</P>
    > <LI>
    > <P>The default profile applies to all countries/regions that do not have a defined profile. You cannot select specific countries/regions for the default profile.</P></LI></UL>



## See also

[Vendor request configurations (form)](https://technet.microsoft.com/en-us/library/hh209430\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

