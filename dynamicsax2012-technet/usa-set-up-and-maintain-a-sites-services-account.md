---
title: (USA) Set up and maintain a Sites Services account
TOCTitle: (USA) Set up and maintain a Sites Services account
ms:assetid: de142cf9-b6b3-4ae7-86bb-d00a98ab1d74
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227411(v=AX.60)
ms:contentKeyID: 36059685
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: USA
---

# (USA) Set up and maintain a Sites Services account 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can sign up for a Sites Services for Microsoft Dynamics ERP account, specify a web address for the sites that you create in Sites Services, and manage the account from Microsoft Dynamics AX.

After you sign up and configure your account, you can use the solutions that are included with Microsoft Dynamics AX and create your own solutions.


> [!IMPORTANT]
> <UL>
> <LI>
> <P>To allow Microsoft Dynamics AX and Sites Services to synchronize data, you must enable change tracking for your database. For more information, see <A href="http://msdn.microsoft.com/en-us/library/bb964713.aspx">Configuring and Managing Change Tracking</A>.</P>
> <P>When enabling change tracking, the retention period must be at least 2 days.</P>
> <LI>
> <P>The Microsoft Dynamics AX Application Object Server (AOS) must be run with credentials that have access to the Internet.</P></LI></UL>



## Sign up for a Sites Services account

1.  Click **Organization administration** \> **Setup** \> **Sites Services** \> **Configuration checklist**.

2.  Click **Set up Sites Services account**.

3.  On the **Sites Services** form, click **Set up account online** to open the Sites Services web site.

4.  Enter your Microsoft Windows Live™ ID and password.

5.  Enter account information on the Sites Services web site.

6.  After you finish, click **Sign out**.

## Specify a company web address

This is typically the name of the organization. The web address is composed of the text you specify and the string ".sites.dynamicssite.com". For example, if you provide the company name "Contoso," the web address will be http://contoso.sites.dynamicssite.com.


> [!NOTE]
> <P>After signing up for an account, it can take up to 24 hours for the account to become active. Until then, you cannot specify a company web address.</P>



1.  Click **Organization administration** \> **Setup** \> **Sites Services** \> **Company web address**.

2.  On the **Company web address - Sites Services** form, in the **Web address:** field, type the initial part of the web address (URL) for your Sites Services web sites.

## Maintain a Sites Services account

1.  Click **Organization administration** \> **Setup** \> **Sites Services** \> **Online service account**.

2.  On the **Sites Services** form, click **Manage account online** to open the Sites Services web site.

3.  Make changes as necessary, click **Sign out**, and then close the browser.

## See also

[(USA) About Sites Services](usa-about-sites-services.md)

[(USA) Activate or deactivate a solution](usa-activate-or-deactivate-a-solution.md)

[(USA) Create a Sites Services solution](usa-create-a-sites-services-solution.md)

  


