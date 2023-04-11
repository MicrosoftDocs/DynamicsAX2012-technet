---
title: (USA) Accept case requests online with Sites Services
TOCTitle: (USA) Accept case requests online with Sites Services
ms:assetid: b95319ad-cc44-47b8-8b34-5c8af0bf2981
ms:mtpsurl: https://technet.microsoft.com/library/Hh242763(v=AX.60)
ms:contentKeyID: 36059116
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: USA
---

# (USA) Accept case requests online with Sites Services 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX includes a Sites Services for Microsoft Dynamics ERP solution called Online case request. After your system administrator or sales manager activates the solutions and sets up the Sites Services web site is set up, customer service staff or sales staff can use this web site to accept case requests online from customers (in addition to vendors and employees). For more information about the solutions that are included with Microsoft Dynamics AX, see [(USA) About Sites Services](usa-about-sites-services.md).

## Activate the Online case request solution

Typically, the system administrator or the sales manager activates the Online case request solution.

1.  Click **Home** \> **Setup** \> **Sites Services** \> **Available solutions**.

2.  In the list of solutions on the left, select the **Online case request** solution, and then click **Activate**.

3.  Click **Synchronize** to synchronize Microsoft Dynamics AX with Sites Services.

## Set up the case request web site

Typically, the system administrator or the sales manager sets up the case request web site.


> [!NOTE]
> <P>The system administrator must sign up for a Sites Services account before the case requests web site.</P>



1.  Click **Home** \> **Setup** \> **Sites Services** \> **Available solutions**.

2.  In the list of solutions on the left, select the **Online case request** solution, and then click **Available pages**.

3.  On the **Available pages** form, click **Manage pages online** to open the Sites Services web site.

4.  In the navigation pane, click **Sales**, and then under **Pages**, click **Cases**.

5.  In the **Pages** group, click **New page**, select the **Case management** page template, and then click **Next step**.

6.  Enter a page name and a page URL, and then click **Create page**.
    
    Customers will use this web page to submit their case requests.

7.  Add text and customize the page the way you want.
    
    For each part on the page, click **Edit**, and then add the text you want, or select the fields from Microsoft Dynamics AX that you want to appear on the page. You can change field labels, specify whether the fields are read-only or accept input, and change their order.
    
    For more information, click the help button in Sites Services.

8.  When you finish customizing the page, click **Save and close**, and then click **Close**.

9.  Click **Sign out**.

10. Optional: Click **Synchronize** on the **Available solutions** form to synchronize the site with Microsoft Dynamics AX now. Alternatively, you can wait for the next scheduled synchronization job to run. After synchronization, you can view the new page in Microsoft Dynamics AX.

## Publicize the case request web site

After the case request web site is online, you can publicize its location and availability so that customers can submit their case requests. Typically you publish this information on your organization's customer service web site according to your organization's policies.

1.  Click **Home** \> **Setup** \> **Sites Services** \> **Available solutions**.

2.  In the list of solutions on the left, select the **Online case request** solution, and then click **Available pages**.

3.  Copy the web address (URL) of the case request page, and then use it in your customer service publicity to direct customers to the web page.

## Review the case requests

After you publish the case request web site, you can periodically view and evaluate the case request.

1.  Click **Home** \> **Common** \> **Cases** \> **All cases**.

2.  In the list of **All cases**, select the case that you want to view and evaluate.

## See also

[(USA) About Sites Services](usa-about-sites-services.md)

[(USA) Set up and maintain a Sites Services account](usa-set-up-and-maintain-a-sites-services-account.md)

  


