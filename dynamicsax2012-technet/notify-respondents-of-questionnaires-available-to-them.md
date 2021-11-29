---
title: Notify respondents of questionnaires available to them
TOCTitle: Notify respondents of questionnaires available to them
ms:assetid: b7bbb4b5-6304-4bae-8cc0-1d544306c59d
ms:mtpsurl: https://technet.microsoft.com/library/Hh500668(v=AX.60)
ms:contentKeyID: 37822156
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Notify respondents of questionnaires available to them 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you distribute a questionnaire, you are required to notify respondents that questionnaires are available to them.


> [!NOTE]
> <P>Before you can notify respondents of questionnaires, you must design a questionnaire. For more information, see <A href="distributing-questionnaires.md">Distributing questionnaires</A>, <A href="designing-questionnaires.md">Designing questionnaires</A>, and <A href="using-questionnaires.md">Using questionnaires</A>.</P>



## Notify respondents of a planned answer session

If you use a planned answer session, you must notify the person manually, for example, by telephone or by using your default email application.

## Notify respondents of a scheduling

Use the **Questionnaire schedules** form to prepare and send an email to all respondents who are assigned to the questionnaire. Depending on whether you will send the email to internal respondents, such as employees, or to external respondents, such as applicants, contact persons, or course participants, you can use one of the following procedures:

  - For internal respondents only, enter the email text on the **E-mail for private site** tab. Respondents can then log on to the web site and complete the questionnaire.

  - For external respondents only, enter the email text on the **E-mail for public site** tab. The email contains a link to the public web site where they can complete the questionnaire.

## Use a public or private web site

The **Questionnaire schedules** form is also used to distribute a questionnaire on Enterprise Portal. How you do this depends on whether you want to invite internal respondents only, or external respondents only.


> [!NOTE]
> <P>You cannot distribute a questionnaire on Enterprise Portal to both internal and external respondents at the same time. To do this you must create two separate schedulings.</P>



  - Internal respondents can access Enterprise Portal to complete the questionnaire by using their logon credentials.

  - External respondents must use the public web site that you select. To enable the public web site on the **Setup** tab, select the **Use public site only?** check box, and then select the public site to use in the **Web site** list. A link that opens the public web site is included in the email that is sent to notify the respondent of the scheduled questionnaire.

## Possible next steps

The following links provide a logical progression to follow in the sequence. Depending on the questionnaire features that you are using, refer to the following information about the next steps:

[End a scheduled questionnaire](end-a-scheduled-questionnaire.md)

  


