---
title: '(USA) Key tasks: Form I-9 verification'
TOCTitle: '(USA) Key tasks: Form I-9 verification'
ms:assetid: 73b31e1f-1a5e-417f-8276-757510fdab71
ms:mtpsurl: https://technet.microsoft.com/library/Hh209229(v=AX.60)
ms:contentKeyID: 36058146
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Form I-9
- i-9
- I-9 Document
- I - 9 Document
- i - 9
audience: Application User
ms.search.region: USA
---

# (USA) Key tasks: Form I-9 verification 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This content contains common tasks related to entering and verifying Form I-9 information for workers in your companies, legal entities, or organizations.

## What do you want to do?

Learn more about...

Prerequisite information

Enter identification information for a worker

Enter Form I-9 information for a worker

Verify Form I-9 information for a worker

Attach a Form I-9 document to a worker record

Reset Form I-9 information for a worker

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About Form I-9 verification](about-form-i-9-verification.md)

## Prerequisite information

To set up the Form I-9 you must set up the information in the following order:

  - Set up an issuing entity in the **Issuing agencies** form. This is the government entity that is authorized to issue the particular document used to verify a person's identity and employment eligibility. For more information, see [(USA) Set up issuing agencies](usa-set-up-issuing-agencies.md).

  - Set up identification types. Some examples of identification types might be birth certificate, a Certificate of birth abroad (CBA), or a school ID. For more information, see [Set up identification types](set-up-identification-types.md).

  - Set up Form I-9 document types. Some examples of document types for the Form I-9 might be a driver’s license, a Passport, a visa, or a Social Security card. For more information, see [(USA) Set up Form I-9 document types](usa-set-up-form-i-9-document-types.md).

  - Select a number sequence code for the **I-9 document** reference in the **Human resources shared parameters** form. For more information, see [Set up number sequences for Human resources](set-up-number-sequences-for-human-resources.md).

Back to top

## Enter identification information for a worker

Before you can enter Form I-9 information for a worker, you must record information about the forms of identification for the worker.

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select the worker to record a form of identification for.

3.  On the **Action Pane**, click **Worker** tab \> **Related information** group \> **Personal information** \> **Identification**.

4.  Click **New**.

5.  Select the type of identification to record for the worker. If the identification type that you need is not listed, create it in the **Identification types** form.

6.  Enter the identification number.
    

    > [!NOTE]
    > <P>The remaining steps in this procedure are optional.</P>



7.  Enter a brief description of the identification record.

8.  Select the agency that issued the form of identification to the worker. For example, if you are recording a driver’s license as the form of identification, you might select **State**.

9.  In the **Entry type** field, enter additional classification information about the form of identification. For example, if you are recording a driver’s license as the form of identification and driver’s licenses have multiple classes of licenses that are issued, you might add the class of driver’s license that the worker has.

10. Indicate if the form of identification is the worker’s primary form of identification.

11. Enter the date when the issuing agency issued the form of identification to the worker.

12. Enter the date when the form of identification expires.

Back to top

## Enter Form I-9 information for a worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select the worker to add Form I-9 information for.

3.  On the **Action Pane**, click **Worker** tab \> **Related information** group \> **Employment** \> **I-9**.

4.  If this is the first time that you are entering Form I-9 information for the worker, click **New.**
    
    To modify Form I-9 information for a worker, select the I-9 document and click **Reset**.

5.  On the **Work eligibility** FastTab, select the option that indicates the eligibility for employment of the worker.
    

    > [!NOTE]
    > <P>If the employee is not a citizen or national of the United States, you must also select the worker’s resident alien or admission number.</P>



6.  Depending on the form of identification that the worker provided, on the **I-9 document** FastTab, select either the **List A** group or the **List B** and **List C** group.
    

    > [!NOTE]
    > <P>To comply with Form I-9 regulations, a worker must provide one List A document or one document from List B and List C. If you select List B, you must provide information about both List B and List C documents.</P>



7.  In the **I-9 document type** field, select the type of document that the worker provided.

8.  In the **Document number** field, select the official identification number of the document.
    

    > [!NOTE]
    > <P>If no values are available in this field, you must first enter identification information for the worker before you can complete this procedure. Refer to the “Enter identification information for a worker” procedure earlier in this topic.</P>



9.  If the employee required assistance to complete the original Form I-9 document, such as a translator, you can enter the name and address of this person on the **Preparer** FastTab.

Back to top

## Verify Form I-9 information for a worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select the worker to verify Form I-9 information for.

3.  On the **Action Pane**, click **Worker** tab \> **Related information** group \> **Employment** \> **I-9**.

4.  Select the Form I-9 document information to verify and click **Verify**.

5.  Select the user who verified that the information that was entered on the Form I-9 was correct.

6.  Click **OK**.
    

    > [!NOTE]
    > <P>After you have verified the document, it cannot be modified without first resetting the information in the form.</P>
    > <P>To modify information that was verified for Form I-9, you must click <STRONG>Reset</STRONG> and enter all of the information again.</P>



Back to top

## Attach a Form I-9 document to a worker record

You must have a digital copy of the Form I-9 document to attach it to a worker record using the document management system.

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select the worker record to attach the document to.

3.  On the **Action Pane**, click **Worker** tab \> **Attachments** group \> **Attachments**.

4.  Click **New** and select **File**.

5.  Browse to the location of the Form I-9 document file, select the file, and then click **Open**.

Back to top

## Reset Form I-9 information for a worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select the worker to reset Form I-9 information for.

3.  On the **Action Pane**, click **Worker** tab \> **Related information** group \> **Employment** \> **I-9**.

4.  Select the Form I-9 information to reset, and then click **Reset**.
    

    > [!NOTE]
    > <P>After you reset the Form I-9 information, you must repeat the verification procedure.</P>



Back to top

## Find form help

[Worker (form)](https://technet.microsoft.com/library/hh209054\(v=ax.60\))

[I-9 document (form)](https://technet.microsoft.com/library/hh227380\(v=ax.60\))

[I-9 document (form) - verification](https://technet.microsoft.com/library/hh242263\(v=ax.60\))

## Find related tasks

[Key tasks: Workers](key-tasks-workers.md)

  


