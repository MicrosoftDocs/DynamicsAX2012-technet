---
title: Setting up questionnaires
TOCTitle: Setting up questionnaires
ms:assetid: 7bbd14a2-9aa1-4ef6-b83e-748179f3b45f
ms:mtpsurl: https://technet.microsoft.com/library/Hh597137(v=AX.60)
ms:contentKeyID: 39519191
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- setup
- set up
- questionnaires
- questionnaire
audience: Application User
ms.search.region: Global
---

# Setting up questionnaires 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the information in this topic to compose questions and enter answers for a questionnaire.


> [!NOTE]
> <P>Before you can set up a questionnaire, you must set up answers, questions, and prerequisites. For more information see <A href="designing-questionnaires.md">Designing questionnaires</A> and <A href="using-questionnaires.md">Using questionnaires</A>.</P>



For each questionnaire, you can specify:

  - The total time or time limit to answer mandatory questions.

  - Whether all questions are mandatory.

  - Whether to calculate points on a questionnaire.

  - How to categorize results.

  - User rights to control access to the questionnaire.

  - If a form template should be displayed as a background behind each page of the questionnaire.

  - Additional notes to clarify the intent of the questionnaire for the respondent.

  - Whether to display questions that are in a set sequence, or to select them from a pool randomly.

  - Questions that will be asked only if specific responses are given for previous answers.

## Set up a questionnaire

The primary form used to set up a questionnaire is **Questionnaires**. Set up a questionnaire in the following order:

1.  Create a questionnaire.

2.  Attach questions to the questionnaire. You can do this in one of two ways, depending on whether you are using result groups:
    
      - To attach questions to a questionnaire using result groups, set up the result groups for the questionnaire, and then add questions to the result groups.
    
      - If you do not use result groups, you can attach questions directly to the questionnaire.

3.  Set up a conditional question hierarchy, if needed. For more information, see [About conditional question hierarchies](about-conditional-question-hierarchies.md)

4.  Test the questionnaire.
    
    In the **Questionnaires** form, click **Validate** to test whether the questionnaire is assembled correctly. However, we also recommend that you complete the questionnaire and test yourself before you distribute it.

## Modify a questionnaire

You can complete the following tasks in a questionnaire:

  - Modify information in the questionnaire, which includes its result groups and questions.

  - Delete and add questions.

  - Make changes in the result groups and sequence number.
    

    > [!WARNING]
    > <P>Be careful when you change questionnaires that have already been answered. Doing so can reduce the accuracy of statistics, which can result in a poor basis for evaluation. Consider creating a new question instead of changing a question that has already been answered.</P>



In a questionnaire, you cannot delete:

  - Questions that are attached to a questionnaire.

  - Questions that are already answered, and are, therefore, found in the **Answers** dialog box.

## More information about how to set up questionnaires

[Set up a questionnaire](set-up-a-questionnaire.md)

[About result groups](about-result-groups.md)

[Attach a question to a questionnaire without result groups](attach-a-question-to-a-questionnaire-without-result-groups.md)

[Attach a question to a questionnaire with result groups](attach-a-question-to-a-questionnaire-with-result-groups.md)

[About conditional question hierarchies](about-conditional-question-hierarchies.md)

[Set up a conditional question hierarchy](set-up-a-conditional-question-hierarchy.md)

  


