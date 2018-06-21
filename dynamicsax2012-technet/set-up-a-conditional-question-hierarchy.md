---
title: Set up a conditional question hierarchy
TOCTitle: Set up a conditional question hierarchy
ms:assetid: 8815c623-b3fd-4471-a1a0-920beac14327
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498221(v=AX.60)
ms:contentKeyID: 42117763
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up a conditional question hierarchy [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you set up a questionnaire, you can select to use conditional question hierarchies. For more information, see [About conditional question hierarchies](about-conditional-question-hierarchies.md).


> [!NOTE]
> <P>Before you can set up a conditional question hierarchy, you must attach questions with assigned answer groups to the questionnaire. For more information, see <A href="setting-up-questionnaires.md">Setting up questionnaires</A>, <A href="designing-questionnaires.md">Designing questionnaires</A>, and <A href="using-questionnaires.md">Using questionnaires</A>.</P>



1.  Click **Home** \> **Common** \> **Questionnaires** \> **Design** \> **Questionnaires**.
    
    For more information about the **Questionnaires** form, see [Questionnaires (form)](https://technet.microsoft.com/en-us/library/aa576998\(v=ax.60\)).

2.  Select a questionnaire.
    
    Verify that **Conditional** is selected in the **Sequence** list on the **Setup** tab.

3.  Click **Questions**, and then select **Conditional question** to open the **Conditional question** form. For more information, see [Conditional question (form)](https://technet.microsoft.com/en-us/library/aa596836\(v=ax.60\)).

4.  Select the conditional question, and then drag it to the primary question.
    

    > [!NOTE]
    > <P>The primary question must be a closed-ended question.</P>



5.  Click **Yes** to move the question.

6.  Select the conditional question, and in the **Answer** field, enter the sequence number for the answer in the answer group that the conditional question should depend on. For example, if one of the answers in the answer group has a sequence number of 1 and an answer of Outstanding, enter **1**.
    
    You can select answers from the answer group that is assigned to the primary question.
    

    > [!NOTE]
    > <P>The options that are available on the right side of this form are also available in the <STRONG>Questions</STRONG> form. Selections or changes that were made in either form will appear in both forms. For information about each field, see <A href="https://technet.microsoft.com/en-us/library/aa553083(v=ax.60)">Question selection (form)</A>.</P>



## Possible next steps

The following links provide a logical progression to follow in the sequence. Depending on the questionnaire features that you are using, refer to the following information about the next steps:

[Distributing questionnaires](distributing-questionnaires.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

