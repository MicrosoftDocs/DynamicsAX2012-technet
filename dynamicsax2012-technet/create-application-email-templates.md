---
title: Create application email templates
TOCTitle: Create application email templates
ms:assetid: 2a0e57a4-9c43-4b24-b00a-36e51eef2530
ms:mtpsurl: https://technet.microsoft.com/library/JJ943749(v=AX.60)
ms:contentKeyID: 51020481
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create application email templates 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you can send emails to applicants that are based on the status of their application for employment, you must create application email templates. Create an application email template for each correspondence action that your organization uses. Application email templates can include bookmarks so that each email that uses the template can include specific information about the applicant and the job that the applicant applied for.

For example, an email template that you might use to respond to applicants who do not qualify for a job might contain the following text.

Dear \<bookmark for applicant’s name\>

Regarding your application for the position: \<bookmark for recruiting project\>   
 We have now reviewed your application and we are sorry that we cannot offer you a position at Contoso Entertainment Systems. We wish you the best of luck for the future.   
   
 Best regards,   
 Human Resources Department   
 Contoso Entertainment Systems

You can create an email template for each correspondence action that your company uses: **Received**, **Interview**, **Rejection**, **Employed**, and **Offer**. The previous example is an example of a template to associate with the **Rejection** correspondence action.

## Create an application email template

1.  Click **Human resources** \> **Setup** \> **Recruitment** \> **Application e-mail templates**.

2.  Click **New**.

3.  Select the correspondence action to associate with the email template.

4.  Enter a name for the email template.

5.  Enter the subject and text for your email template.
    
    To insert an application bookmark in the text, position your pointer in the location to insert the bookmark and then double-click the bookmark in the **Application bookmark variable to be used in e-mail** list. If the list is empty, you have not set up application bookmarks for the selected correspondence action. For more information, see [Set up application bookmarks](set-up-application-bookmarks.md).

## Next steps

After you set up your application email templates, you can use the templates when you send emails to applicants. For more information, see [Key tasks: Applicants](key-tasks-applicants.md).

## See also

[Manage recruitment](manage-recruitment.md)

[Application bookmarks (form)](https://technet.microsoft.com/library/aa573363\(v=ax.60\))

  


