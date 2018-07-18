---
title: (USA) Accept vendor registrations online with Sites Services
TOCTitle: (USA) Accept vendor registrations online with Sites Services
ms:assetid: 2e6229d0-c72d-4baf-a22f-070bd667ec1b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208529(v=AX.60)
ms:contentKeyID: 36056277
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: USA
---

# (USA) Accept vendor registrations online with Sites Services 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX includes a Sites Services for Microsoft Dynamics ERP solution called **Unsolicited vendor registration**. After a Sites Services account has been set up, purchasing department staff can use this solution to accept vendor registrations online and download them to Microsoft Dynamics AX.

For more information about Sites Services, see [(USA) About Sites Services](usa-about-sites-services.md).

## Activate the Unsolicited vendor registration solution

Typically, the system administrator or the purchasing manager activates the **Unsolicited vendor registration** solution.

1.  Click **Organization administration** \> **Setup** \> **Sites Services** \> **Available solutions**.

2.  In the list of solutions on the left, click the **Unsolicited vendor registration** solution, and then click **Activate**.

3.  Click **Synchronize** to synchronize Microsoft Dynamics AX with Sites Services.

## Set up the Sites Services web site for vendor registration

Typically, the system administrator or the purchasing manager sets up the vendor registration web site.


> [!NOTE]
> <P>The system administrator must sign up for a Sites Services account before you can set up the vendor registration web site.</P>



1.  Click **Organization administration** \> **Setup** \> **Sites Services** \> **Available solutions**.

2.  In the list of solutions on the left, click **Unsolicited vendor registration**, and then click **Available pages**.

3.  On the **Available pages** form, click **Manage pages online** to open the Sites Services web site.

4.  In the navigation pane on the left, click **Vendor**, and then under **Pages**, click **Vendor registration**.

5.  In the **Pages** group, click **New page**, select the **Unsolicited vendor** page template, and then click **Next step**.

6.  Enter a page name, and then click **Create page**.

7.  Add text and customize the page the way you want.
    
    For each part on the page, click **Edit**, and then add the text you want, or select the fields from Microsoft Dynamics AX that you want to appear on the page. You can change field labels, specify whether the fields are read-only or accept input, and change their order.
    
    For more information, click the Help button in Sites Services.

8.  When you finish customizing the page, click **Save and close**, and then click **Close**.

9.  Click **Sign out**.

10. Optional: To synchronize the page, click **Synchronize** on the **Available solutions** form. Alternatively, you can wait until the next scheduled synchronization job to run. After the page is synchronized, you can view the new page in Microsoft Dynamics AX.

## Publicize the vendor registration web site

After the vendor registration web site is online, you can publish its location and advertise for vendors to submit their registrations. Typically, you publish this information on your organization's web site according to your organization's policies.

1.  Click **Organization administration** \> **Setup** \> **Sites Services** \> **Available solutions**.

2.  In the list of solutions on the left, select **Unsolicited vendor registration**, and then click **Available pages**.

3.  Copy the web address (URL) of the vendor registration page, and then use it in your publicity for vendors to direct interested vendors to the web page.

## Review the registrations

After you publish the vendor registration web site, you can periodically view and evaluate the unsolicited registrations.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**.

2.  In the list of **Vendor requests**, select the registration that you want to view and evaluate.

## See also

[(USA) About Sites Services](usa-about-sites-services.md)

[(USA) Set up and maintain a Sites Services account](usa-set-up-and-maintain-a-sites-services-account.md)

  


