---
title: Attach a question to a questionnaire with result groups
TOCTitle: Attach a question to a questionnaire with result groups
ms:assetid: 149e3f29-f6f1-45cd-a224-fe26287cf7a6
ms:mtpsurl: https://technet.microsoft.com/library/Aa496618(v=AX.60)
ms:contentKeyID: 42117749
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Attach a question to a questionnaire with result groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Using result groups is optional when you attach questions to a questionnaire. Create result groups only if you want to evaluate results based on correct answers. For more information, see [About result groups](about-result-groups.md).


> [!NOTE]
> <P>Before you can set up result groups, you must:</P>
> <UL>
> <LI>
> <P>Set up closed-ended questions. For a question to be a closed-ended question, the input type in the <STRONG>Questions</STRONG> form must be <STRONG>Check box</STRONG>, <STRONG>Alternative button</STRONG>, or <STRONG>Combo box</STRONG>.</P>
> <LI>
> <P>Define points for answers in the answer groups assigned to each question.</P>
> <LI>
> <P>Set up a questionnaire.</P></LI></UL>
> <P>For more information, see <A href="setting-up-questionnaires.md">Setting up questionnaires</A>, <A href="designing-questionnaires.md">Designing questionnaires</A>, and <A href="using-questionnaires.md">Using questionnaires</A>.</P>



## Set up a result group

1.  Click **Home** \> **Common** \> **Questionnaires** \> **Design** \> **Questionnaires**.

2.  Select a questionnaire to create a result group for.

3.  Click the **Result** FastTab, and select the **Point statistics** check box to activate the **Result groups** button.

4.  Click **Result groups** to open the **Result groups** form.

5.  Click **New** to create a new line.

6.  In the **Result group** field, type a unique identification for the result group, and in the **Description** field, type a brief description of the result group.

7.  Enter additional information, as needed, in the remaining fields.
    
    For more information, see [Result groups (form)](https://technet.microsoft.com/library/aa587908\(v=ax.60\)).

## Add questions to a result group

1.  Click **Home** \> **Common** \> **Questionnaires** \> **Design** \> **Questionnaires**.

2.  Select a questionnaire to attach questions to, and then click **Result groups**.

3.  In the **Result groups** form, select a result group and then click **Questions**.

4.  In the **Questions** form, click **New** to create a new line.

5.  In the **Question** field, select a question from the list.

6.  In the **Result calculation** field, specify how to distribute points to the result groups. The next step in the process depends on your selection:
    
      - **Questions** – Points for answers are added to the result group for the question.
        
        Next step: Select a result group in the **Result groups** field, and verify that the correct result group appears in the **Result group** field.
    
      - **Answer** – Points for answers are added to the result group for the answer.
        
        Next step: Click **Answer**, and in the **Answer** form, select the result group for the answer and the sequence number.
        
        Create a new line for each answer that will contribute to the result group.
        
        For more information, see [Result groups for answer (form)](https://technet.microsoft.com/library/aa618542\(v=ax.60\)).
    
      - **If not answer, then question** - Points for answers are added to the answer result group for the answer, if specified. Otherwise, they are added to the question result group for the question. For example, you can define the points for specific answers that should not be assigned to the question result group for the question.
        
        Next step: Select a result group. Then, click **Answer**, and in the **Answer** form, select the result group for the answer.
        
        For more information, see [Result groups for answer (form)](https://technet.microsoft.com/library/aa618542\(v=ax.60\)).

7.  Enter information, as needed, in the remaining fields.
    
    For more information, see [Question selection (form)](https://technet.microsoft.com/library/aa553083\(v=ax.60\)).

## Set up points/texts for a result group


> [!NOTE]
> <P>Setting up points/texts is optional when you set up result groups.</P>



1.  Click **Home** \> **Common** \> **Questionnaires** \> **Design** \> **Questionnaires**.

2.  Select the questionnaire that the result group is related to, and then click **Result groups** to open the **Result groups** form.

3.  Select the result group, and then click **Calculate points**. The maximum number of points is displayed in the **Max. number of points** field in the **Result groups** form.
    

    > [!NOTE]
    > <P>If the <STRONG>Several rows</STRONG> check box in the <STRONG>Questions</STRONG> form is selected for the questions that you assign to a result group, each row counts in the total as an independent question.</P>



4.  Click **Points/texts** to open the **Points/texts** form.

5.  In the **From points** and **To points** fields, type the minimum and the maximum number of points in the result group interval. The values in these boxes must not exceed the maximum number of points for the result group.

6.  Click **Edit**, and then enter the text to display in the result report for scores within the interval.

## Possible next steps

The following links provide a logical progression to follow in the sequence. Depending on the questionnaire features that you are using, refer to the following information about the next steps:

[About conditional question hierarchies](about-conditional-question-hierarchies.md)

[Distributing questionnaires](distributing-questionnaires.md)

  


