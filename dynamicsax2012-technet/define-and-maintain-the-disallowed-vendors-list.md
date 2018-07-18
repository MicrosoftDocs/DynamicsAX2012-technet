---
title: Define and maintain the disallowed vendors list
TOCTitle: Define and maintain the disallowed vendors list
ms:assetid: 3ba21984-54eb-474a-8b21-e90729fed06b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh433533(v=AX.60)
ms:contentKeyID: 36941322
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Define and maintain the disallowed vendors list 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create a list of vendors that you do not want to do business with. The disallowed vendors list is used in system checks for certain types of vendor-related requests.

If disallowed vendor validation is enabled, a system check is performed when a vendor request is submitted. The system searches the disallowed vendor table for matches in the following fields:

  - **Name**

  - **Address**

  - **Phone**

  - **1099 tax ID**

  - **Bank account number**

If a match is found, the vendor request is flagged to indicate to the reviewer that the vendor is disallowed.


> [!NOTE]
> <P>Users who have access to the <STRONG>All vendors</STRONG> list page and appropriate permissions can add a disallowed vendor to the disallowed vendors list. Disallowed vendor validation is used only during the vendor request process.</P>




> [!NOTE]
> <P>Before you can select a number sequence for disallowed vendors, you must define your number sequences in the <STRONG>Number sequences</STRONG> form. For more information about how to set up number sequences, see <A href="https://technet.microsoft.com/en-us/library/aa600321(v=ax.60)">Number sequences (list page)</A>. This topic explains how to set up number sequences, and how to set them up in specific modules.</P>



1.  Click **Procurement and sourcing** \> **Setup** \> **Vendors** \> **Disallowed vendors**.

2.  In the **Disallowed vendors** form, press CTRL+N to create a new entry or click **New**.

3.  Enter the vendor name and any other identifying details that you have for the vendor.

4.  On the **Company accounts** tab, select the legal entities that the disallowed vendor applies to. You must select at least one legal entity.
    
      - **Selected company accounts** – The companies for which the vendor is considered a disallowed vendor.
    
      - **Remaining company accounts** – The companies for which the vendor is not considered a disallowed vendor. Vendors can be disallowed in some companies and allowed in others.
    

    > [!TIP]
    > <P>When you create a disallowed vendor, if the vendor type is an organization, the <STRONG>Company accounts</STRONG>, <STRONG>Address</STRONG>, and <STRONG>Contact information</STRONG> FastTabs may not be displayed. To see all the FastTabs, complete the information on the <STRONG>General</STRONG> and <STRONG>Details</STRONG> FastTabs, and then save the record.</P>



## See also

[Configuring Enterprise Portal for vendor requests](configuring-enterprise-portal-for-vendor-requests.md)

  


