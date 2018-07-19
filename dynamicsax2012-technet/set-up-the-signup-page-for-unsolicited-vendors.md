---
title: Set up the Signup page for unsolicited vendors
TOCTitle: Set up the Signup page for unsolicited vendors
ms:assetid: 26c4f2b8-1363-42a9-988f-f57c3a750e79
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208487(v=AX.60)
ms:contentKeyID: 36056204
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up the Signup page for unsolicited vendors 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

An unsolicited vendor is a vendor who does not currently do business with your company but wants to be considered as a potential vendor. These vendors can submit information about their companies by using the **Signup** page in the Unsolicited vendor portal. Your employees can search for vendors in the unsolicited vendor database. To work with one of these vendors, an employee must submit a new vendor request.

Before unsolicited vendors can sign up to be considered as potential vendors, the system administrator for your company must complete the following tasks:

  - Define one or more unsolicited vendor profiles by country/region.

  - Set up the Unsolicited vendor portal. For information about how to set up the Unsolicited vendor portal, see [Checklists for deploying Enterprise Portal sites in Microsoft Dynamics AX 2012](http://go.microsoft.com/fwlink/?linkid=218011%26clcid=0x409).

## Configure the Signup page for unsolicited vendors

You use the **Unsolicited vendor registration** request type to set up the **Signup** page for unsolicited vendors. You can create multiple profiles for this request type. This lets you customize the signup process based on the fields that are required for a specific country/region. For example, in a profile for France, you might require the vendor to provide their French Siret number during the signup process.

1.  Click **Procurement and sourcing** \> **Setup** \> **Vendors** \> **Vendor request configurations**.

2.  In the **Vendor request configurations** form, in the **Request type** field, select **Unsolicited vendor registration**.

3.  Click **New**.
    

    > [!NOTE]
    > <P>If you do not click <STRONG>New</STRONG>, the changes that you make will affect the default <STRONG>Unsolicited vendor registration</STRONG> request type.</P>



4.  On the **Fields** FastTab, indicate whether each business information field that appears in the list should be displayed, hidden, or required on the **Signup** page.

5.  On the **Countries/regions** FastTab, select the countries/regions to which the profile applies.
    

    > [!NOTE]
    > <UL>
    > <LI>
    > <P>The country/region that is identified in the primary address for the vendor is used to determine which unsolicited vendor profile to display on the <STRONG>Signup</STRONG> page.</P>
    > <LI>
    > <P>The default profile applies to all countries/regions that do not have a defined profile. Specific countries/regions cannot be selected for the default profile.</P></LI></UL>



6.  If you want to display specific text to the vendor during the signup process, on the **Content** FastTab, select the **Select to display defined text** check box. Enter the text in the **General text** box. For example, this text might contain privacy and disclosure information that the vendor must acknowledge before completing the signup process.

## See also

[Vendor request configurations (form)](https://technet.microsoft.com/en-us/library/hh209430\(v=ax.60\))

  


