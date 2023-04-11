---
title: 'How to: Import an XSLT Transform'
TOCTitle: 'How to: Import an XSLT Transform'
ms:assetid: e984da62-cd87-4096-a5c1-c3564a79a47b
ms:mtpsurl: https://technet.microsoft.com/library/Gg848023(v=AX.60)
ms:contentKeyID: 35253228
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Import an XSLT Transform 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic shows you how to import an XSLT transform in Microsoft Dynamics AX. After you import the XSLT, you can use it in the Application Integration Framework (AIF) pipeline. XSLTs are used to transform data in a request before it reaches the message queue.

## Importing the XSLT file

In this section you import the XSLT transform so you can use it in the AIF pipeline.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><img src="images/Ee355075.alert_security(AX.60).gif" title="Security note" alt="Security note" /><strong>Security Note</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>You must be logged into Windows Server as an administrator to add a new transform.</p></td>
</tr>
</tbody>
</table>


### To import the XSLT file

1.  Open Microsoft Dynamics AX and type CTRL+SHIFT+W to open a new development workspace.

2.  Select **Tools** \> **Application Integration Framework** \> **Manage transforms**.

3.  In the **Manage transforms** form, type CTRL+N to add a new transform.

4.  In the **Name** field, enter a unique name of up to 30 characters.

5.  In the **Description** field, enter a description of the transform of up to 1,000 characters.

6.  In the **Type** field, select **XSL**.

7.  Click **Load**, navigate to the XSLT file, and then click **Open**. The XSLT XML is displayed in the **Content** field.

8.  Type CTRL+S to save the transform.


> [!WARNING]
> <P>We do not recommend adding multiple instances of the same .NET assembly to the <STRONG>Manage transforms</STRONG> form by using a different name for each instance. When multiple instances of the .NET assembly are listed in the form, each instance refers to the same .dll file. Changes to the .dll file will affect all ports that reference the transform, regardless of the name of the transform in the <STRONG>Manage transforms</STRONG> form.</P>



## See also

[About the AIF Pipeline and Transforms](about-the-aif-pipeline-and-transforms.md)

