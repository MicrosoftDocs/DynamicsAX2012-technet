---
title: Detect code upgrade conflicts
TOCTitle: Detect code upgrade conflicts
ms:assetid: fe368442-0046-4233-906a-74b405e3da4e
ms:mtpsurl: https://technet.microsoft.com/library/Aa497071(v=AX.60)
ms:contentKeyID: 35133342
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Detect code upgrade conflicts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Code upgrade conflicts occur when your customized legacy code cannot be safely used on a new Microsoft Dynamics AX target system without review and, in many cases, modification. This task opens the **Detect code upgrade conflicts** form, which offers options to perform various types of code conflict analysis and resolution. Conflicts are organized into development projects that allow for easy comparison of conflicting application object versions. The form also allows you to resolve some upgrade conflicts automatically.

For developer documentation about code upgrade in Microsoft Dynamics AX 2012, see the downloadable [code upgrade white papers](https://go.microsoft.com/fwlink/?linkid=215083). See also *Inside Microsoft Dynamics AX 2009*, Chapter 18: “Code upgrade,” pp. 623–644.

## Options for detecting and resolving code conflicts

The functions available from the **Detect code upgrade conflicts** form are listed below. You can:

  - Scan metadata (code, properties, form structure) and search for inconsistencies between the baseline and target versions.

  - Delete customized application objects where the customizations duplicate standard Microsoft Dynamics AX code.

  - Automatically merge versions of methods contained in multiple releases and customizations of Microsoft Dynamics AX.

  - Resolve object property conflicts automatically in favor of customer changes.

  - Scan for conformity to best practices in designing table and project references (IDs).

  - Analyze custom code on the target system for rule conflicts. This analysis is based on the code conflict rules that you imported during the [Configure rules for code upgrade](configure-rules-for-code-upgrade.md) step.

  - Auto-resolve code conflict patterns that are discovered.

## Code conflict projects

Projects that may be created include the following:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type of analysis</p></th>
<th><p>Project created</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Layer conflict</p></td>
<td><p>Private project AxUpgradeLayerConflicts_&lt;layer&gt;</p></td>
</tr>
<tr class="even">
<td><p>Framework (ID reference) conflict</p></td>
<td><p>Private project AxUpgradeRecIdConflicts_&lt;layer&gt;</p></td>
</tr>
<tr class="odd">
<td><p>Pattern (rule) conflict</p></td>
<td><p>Private project AxUpgradeRuleConflicts_&lt;layer&gt;</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>Although no baseline database is required to run code pattern detection, analysis of layer conflicts requires that you configure a baseline database before you run this task. Follow these steps to configure the baseline database:</P>
> <OL>
> <LI>
> <P>Close the Microsoft Dynamics AX client.</P>
> <LI>
> <P>Open the Microsoft Dynamics AX 2012 Server Configuration utility (<STRONG>Start</STRONG> &gt; <STRONG>Administrative Tools</STRONG> &gt; <STRONG>Microsoft Dynamics AX 2012 Server Configuration</STRONG>).</P>
> <LI>
> <P>If there is no editable configuration, create a new one.</P>
> <LI>
> <P>On the <STRONG>Database Connection</STRONG> tab, set the <STRONG>Baseline database name</STRONG> value so that it is the same as the <STRONG>Database name</STRONG> value.</P>
> <LI>
> <P>Restart AOS.</P>
> <LI>
> <P>Reopen the Microsoft Dynamics AX client, and continue with the upgrade.</P></LI></OL>


  


