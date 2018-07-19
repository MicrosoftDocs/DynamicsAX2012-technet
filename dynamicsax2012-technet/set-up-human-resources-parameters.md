---
title: Set up human resources parameters
TOCTitle: Set up human resources parameters
ms:assetid: 12c9e324-d565-41f8-b4eb-6633e1db3c86
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496591(v=AX.60)
ms:contentKeyID: 36056041
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- applicant number sequences
- Application number sequences
- compensation parameters
- Interview number sequences
- Recruitment parameters
audience: Application User
ms.search.region: Global
---

# Set up human resources parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Human resources shared parameters** form and the **Human resources parameters** form to set up Human resources parameters.

You should define all parameters before you start to create your data; however, you can modify your settings at any time.


> [!NOTE]
> <P>Before you can specify the human resources parameters for identification types and number sequences, you must first set them up. For more information, see <A href="set-up-identification-types.md">Set up identification types</A> and <A href="set-up-number-sequences-for-human-resources.md">Set up number sequences for Human resources</A>.</P>



## Set up shared parameters

Click **Human resources** \> **Setup** \> **Parameters** \> **Human resources shared parameters**.

Use the **Human resources shared parameters** form to set up parameters to use for all your legal entities. Parameters are grouped into areas according to their functionality. In each area, you can set up the following parameters:

1.  **Identification** – Select the identification types that represent the identification numbers listed in the following fields. The information for the following fields is maintained in the following form: [Identification type (form)](https://technet.microsoft.com/en-us/library/hh227646\(v=ax.60\)).
    
      - In the **SSN** field, select the identification type that represents the Social Security Number.
    
      - In the **National ID number** field, select the identification type that represents the National ID number.
    
      - In the **Alien ID number** field, select the identification type that represents the Alien ID number.

2.  **Number sequences** – Select the number sequences that will be used to automatically assign IDs to items in Human resources, such as positions, discussions, personnel numbers, and applicants. To maintain number sequence references and codes, use the **Number sequences** list page (Click **Organization administration** \> **Common** \> **Number sequences** \> **Number sequences**.).

3.  **Positions** – When new positions are created, select the appropriate worker assignment behavior:
    
      - **Always** – You can assign workers to new positions when positions are created. The **Available for assignment** date and time will be set to the creation date and time on the **General** tab in the **Position** form when positions are created.
    
      - **Never** – You cannot assign workers to new positions when positions are created. If you select this option, you will have to open the **Position** form for each new position as it becomes available and enter the **Available for assignment** date on the **General** tab to enable worker assignment.

## Set up company-specific parameters

Click **Human resources** \> **Setup** \> **Parameters** \> **Human resources parameters**.

Use the **Human resources parameters** form to set up parameters that are specific to the legal entity that you are currently logged on to. Parameters are grouped into areas according to their functionality. In each area, you can set up the following parameters:

1.  **General** – Select a color to apply to open absence transactions, specify the style sheet to use for reports, indicate whether to enable the integration between training courses and absence registration, select the absence code to use to control this integration, and indicate how long injury and illness case incidents should be kept.

2.  **Recruitment** – Select the document types to use for automated correspondence with applicants, select the recruitment project to use for unsolicited applications, and specify a period that is used to calculate expiration dates for applications.

3.  **Compensation** – Indicate whether to show a warning before a user saves information in a fixed or variable plan. If you are using performance management, you can select a rating model to use instead of the model assigned to compensation plans when rating performance.

4.  **Number sequences** – Select the sequences that will be used to automatically assign IDs to items in Human resources, such as applications, absence registrations, events, case numbers, courses, and course agendas. To maintain number sequence references and codes, use the **Number sequences** list page (Click **Organization administration** \> **Common** \> **Number sequences** \> **Number sequences**.).

5.  **FMLA** – When you open this tab, all Family and Medical Leave Act (FMLA) forms become available.
    
    Review the default settings and make any changes. Some of the values in this form are mandated by federal law and can’t be increased. For example, a maximum of 52 weeks and 1250 hours are required for standard FMLA leave.
    

    > [!TIP]
    > <P>The most beneficial eligibility date priority sequence for your workers is provided. We recommend that you leave this sequence as is to help make sure you are in compliance with federal FMLA laws, unless your organization has a specific need to change the order.</P>



## See also

[Human resource parameters (form)](https://technet.microsoft.com/en-us/library/aa596451\(v=ax.60\))

[Human resources shared parameters (form)](https://technet.microsoft.com/en-us/library/hh209632\(v=ax.60\))

[Number sequences (list page)](https://technet.microsoft.com/en-us/library/aa600321\(v=ax.60\))

  


