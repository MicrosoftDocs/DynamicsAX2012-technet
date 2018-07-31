---
title: Register absences
TOCTitle: Register absences
ms:assetid: 5452a64b-ff46-4f87-a65c-dca5f5170c46
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa548933(v=AX.60)
ms:contentKeyID: 42117757
ms.date: 05/16/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Register absences 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can record your work absences in multiple ways. You can register past absences and you can request future absences. For both future and past absences, you can create open-ended absence transactions for employees whose working time is measured in hours. An open-ended absence transaction does not have an ending date. If you are an absence administrator, you also can register absences for the workers whom you are the absence administrator.

Absence registrations are grouped into absence journals that are defined by an absence period. Each worker’s absence period is determined by the absence setup that is assigned to their record in the **Worker** form. For more information about how to set up absences, see [Key task: Set up absence information](key-task-set-up-absence-information.md).

## Register a past absence

You must have an absence journal already created for the current absence period before you can register a past absence. For more information, see [Create absence journals](create-absence-journals.md).

1.  Click **Home** \> **Common** \> **Absences** \> **Register absences**.

2.  Click **New**.

3.  Select the date of the absence.
    

    > [!TIP]
    > <P>To save time when you enter consecutive absences, use the <STRONG>Create series</STRONG> form. For more information, see the <STRONG>Enter a series of consecutive absences</STRONG> procedure later in this topic.</P>



4.  Select an absence code to apply to the absence. The absence code indicates the type of absence it is. For example, if you were absent for a dentist appointment, you might select an absence code titled Dentist.

5.  Enter a description of the absence.

6.  If the absence is an open-ended absence, click **Open**.

7.  On the **General** FastTab, enter the number of hours that you were absent. If the **Hours** field is not displayed, go to the next step.

8.  Repeat steps 2 through 7 for each additional absence.

9.  On the **Notes** FastTab, you can enter additional information about the absence journal that the absence is included in.

After you have entered all your absence registrations for a specific absence period, you must transfer the current absence journal for approval. For more information, see [Transfer absence journals for approval](transfer-absence-journals-for-approval.md).

## Request a future absence

You must have an absence journal created for the current absence period before you can request a future absence. For more information, see [Create absence journals](create-absence-journals.md).

1.  Click **Home** \> **Common** \> **Absences** \> **Request future absences**.

2.  Click **New**.

3.  Enter a date for the future absence.
    

    > [!TIP]
    > <P>To save time when you enter consecutive absences, use the <STRONG>Create series</STRONG> form. For more information, see the <STRONG>Enter a series of consecutive absences</STRONG> procedure later in this topic.</P>



4.  Select an absence code to apply to the absence. The absence code indicates the type of absence it is. For example, if you were absent for a dentist appointment, you might select an absence code titled Dentist.

5.  Enter a description for the absence.

6.  Enter the number of hours that you were absent. If the **Hours** field is not displayed, go to the next step.

7.  Repeat steps 2 through 7 for each additional future absence.

After you have entered all your future absence requests, you must transfer the requests for approval. If your future absence requests are approved, they will automatically be registered in the absence journal.

## Register absences for multiple workers

You must create an absence journal for each worker for the current absence period before you can record absence registrations the workers. For more information, see [Create absence journals](create-absence-journals.md).

Also, you can only register absences for the workers whom you are the absence administrator.

1.  Click **Home** \> **Common** \> **Absences** \> **Register absences for multiple workers**.

2.  Select the worker to register an absence for.

3.  On the **Absence registration details** FastTab, click **Add**.
    

    > [!TIP]
    > <P>To save time when you enter consecutive absences, use the <STRONG>Create series</STRONG> form. For more information, see the <STRONG>Enter a series of consecutive absences</STRONG> procedure later in this topic.</P>



4.  Enter the date of the absence, the absence code, and a description of the absence.

5.  Enter the number of hours that the worker was absent. If the **Hours** field is not displayed, go to the next step.

6.  If the absence is an open-ended absence, click **Open**.

7.  Repeat steps 2 through 6 for each additional absence.

## Enter a series of consecutive absences

When you record an absence request or an absence registration for multiple-day absences, instead of entering each absence separately, you can click **Create series** in any of the following forms to create the consecutive absences at the same time:

  - [Register absences for multiple workers (form)](https://technet.microsoft.com/en-us/library/aa554509\(v=ax.60\))

  - [Request future absences (form)](https://technet.microsoft.com/en-us/library/aa556621\(v=ax.60\))

  - [Absence registration (form)](https://technet.microsoft.com/en-us/library/aa585058\(v=ax.60\))

## See also

[Manage absence in Human resources](manage-absence-in-human-resources.md)

[Register absences for multiple workers (form)](https://technet.microsoft.com/en-us/library/aa554509\(v=ax.60\))

[Request future absences (form)](https://technet.microsoft.com/en-us/library/aa556621\(v=ax.60\))

  


