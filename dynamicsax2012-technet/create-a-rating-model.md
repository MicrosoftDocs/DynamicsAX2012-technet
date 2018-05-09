---
title: Create a rating model
TOCTitle: Create a rating model
ms:assetid: 81eca856-f7ac-4406-9635-3a3d64cceb9f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213153(v=AX.60)
ms:contentKeyID: 50619131
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- rating model
- Set up an employee rating system
---

# Create a rating model 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create rating models with graduated levels that you can then use to rate worker skills.

For example, a rating model titled “Typing” might include the following levels.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Level</p></th>
<th><p>Description</p></th>
<th><p>Factor</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>70+ words per minute</p></td>
<td><p>2</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>50-70 words per minute</p></td>
<td><p>1</p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p>0-50 words per minute</p></td>
<td><p>0</p></td>
</tr>
</tbody>
</table>


### To create a rating model

1.  Click **Human resources** \> **Setup** \> **Competencies** \> **Skills** \> **Rating models**.

2.  Click **New**.

3.  In the **Rating** field, enter a name for the rating model.

4.  Enter a description of the rating model.

5.  On the **Levels** FastTab, click **New** to create a level for the rating model.
    
    You can enter up to 10 levels for a rating model.

6.  Enter an identifier and description for the level.
    
    The description can indicate the rating, for example, "Satisfactory" or "Needs Improvement". The person providing a rating will use this to make his or her decision.

7.  In the **Factor** field, enter a factor for the level. The factor value will be used to normalize scores of skills that use different rating models.
    
    The factor must be a number 0-9 and each level must have a unique factor. Levels with higher factor values carry more weight in a rating model.

8.  To enter additional detail about a level, select a level and then, on the **Note** FastTab, enter additional information about the level.

9.  Complete steps 5 through 8 for each additional level in the rating model.

## See also

[About skills](about-skills.md)

[Rating models (form)](https://technet.microsoft.com/en-us/library/jj856599\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

