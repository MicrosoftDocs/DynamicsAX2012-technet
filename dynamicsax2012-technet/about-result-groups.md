---
title: About result groups
TOCTitle: About result groups
ms:assetid: d5097f08-6429-4fcb-b6bb-2db086f37d75
ms:mtpsurl: https://technet.microsoft.com/library/Aa499370(v=AX.60)
ms:contentKeyID: 36059524
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About result groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Result groups are optional when you attach questions to a questionnaire. To attach questions to a questionnaire using result groups, first set up the result groups for the questionnaire, and then add questions to the result groups. If you do not use result groups, questions can be attached directly to a questionnaire.


> [!NOTE]
> <P>Before you can set up result groups, you must:</P>
> <UL>
> <LI>
> <P>Set up closed-ended questions. For a question to be closed-ended, the input type in the <STRONG>Questions</STRONG> form must be <STRONG>Check box</STRONG>, <STRONG>Alternative button</STRONG>, or <STRONG>Combo box</STRONG>.</P>
> <LI>
> <P>Define points for answers in the answer groups that are assigned to each question.</P>
> <LI>
> <P>Set up a questionnaire.</P></LI></UL>
> <P>For more information, see <A href="setting-up-questionnaires.md">Setting up questionnaires</A>, <A href="designing-questionnaires.md">Designing questionnaires</A>, and <A href="using-questionnaires.md">Using questionnaires</A>.</P>



A result group is used to calculate points and categorize the results of a questionnaire. If you use result groups, you can:

  - Evaluate questionnaire results based on point statistics.

  - Evaluate a respondent’s score for each result group that you set up.

  - Generate statistics for each result group to help you analyze results.

  - Print a report that shows results for each result group and also optional points/texts that are based on points earned in each result group.

You can set up multiple result groups in order to evaluate points earned by a respondent in each category. After a questionnaire is completed, you can view the points that have been achieved for each result group.


> [!TIP]
> <P>To evaluate a questionnaire using points, but not separate categories, you can add all questions to a single result group.</P>



For each result group, you can also set up one or more points/texts, which are texts that can be shown to a respondent after they complete a questionnaire. The text that is displayed can vary according to the score that the respondent achieves in a result group. To use points/text, you must define point intervals and a description of each interval. When a respondent achieves a score in a specific interval, the text for that interval is included in the results report.

Because a result group relates to points associated with specific sets of questions on a questionnaire, you can use only a specific result group for one questionnaire.

## Example: Points/texts for result group 3

If you use a questionnaire for a leadership test with 15 questions in three categories, you can create three result groups and add five questions to each result group. The result groups could be:

  - Creative abilities

  - Leadership abilities

  - Technical abilities

Points are then totaled in the three groups: creative, leadership, and technical abilities.

To use points/texts, you can set up text intervals for each result group. If each question is assigned two points, the maximum point total in each result group would be ten.

The following table is an example of points/texts that have been defined for the “leadership abilities” result group.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Point interval</p></th>
<th><p>Text</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1 to 3</p></td>
<td><p>You have average leadership abilities.</p></td>
</tr>
<tr class="even">
<td><p>4 to 7</p></td>
<td><p>You have good leadership abilities.</p></td>
</tr>
<tr class="odd">
<td><p>8 to 10</p></td>
<td><p>You have outstanding leadership abilities.</p></td>
</tr>
</tbody>
</table>


You can set up point intervals and texts for each result group on a questionnaire. Texts that correspond to each respondent’s score are displayed for each result group.


> [!NOTE]
> <P>You can change intervals and texts. However, if a questionnaire has been completed, changes may cause differences between previous and new result reports.</P>



## Possible next steps

The following links provide a logical progression to follow in the sequence. Depending on the questionnaire features that you are using, refer to the following information about the next steps:

[Attach a question to a questionnaire with result groups](attach-a-question-to-a-questionnaire-with-result-groups.md)

[Attach a question to a questionnaire without result groups](attach-a-question-to-a-questionnaire-without-result-groups.md)

  


