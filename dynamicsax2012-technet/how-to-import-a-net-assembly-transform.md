---
title: 'How to: Import a .NET Assembly Transform'
TOCTitle: 'How to: Import a .NET Assembly Transform'
ms:assetid: 972112ef-46a3-4432-8cf3-d79e83b5e438
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg879513(v=AX.60)
ms:contentKeyID: 35247753
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Import a .NET Assembly Transform 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic shows you how to import a .NET assembly in Microsoft Dynamics AX. After you import the assembly, you can use the transformation components that it contains in the Application Integration Framework (AIF) pipeline. The transformation components are classes within the assembly that implement the ITransform interface. These classes perform processing on requests that come into or go out of the AIF pipeline. For more information about creating a .NET assembly transform, see [Walkthrough: Creating a .NET Assembly Transform](walkthrough-creating-a-net-assembly-transform.md).

## Importing the .NET Assembly

In this section you import the .NET assembly transform so you can use it in the AIF pipeline.

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


### To import the .NET assembly

1.  Copy the assembly file (DLL) to the server bin directory. This directory varies depending on your installation, but it may be named something like C:\\Program Files\\Microsoft Dynamics AX\\60\\Server\\MicrosoftDynamicsAX\\Bin.

2.  Copy the assembly file (DLL) to the client bin directory. This directory varies depending on your installation, but it may be named something like C:\\Program Files\\Microsoft Dynamics AX\\60\\Client\\Bin.

3.  Open Microsoft Dynamics AX and type CTRL+SHIFT+W to open a new development workspace.

4.  Select **Tools** \> **Application Integration Framework** \> **Manage transforms**.

5.  In the **Manage transforms** form, type CTRL+N to add a new transform.

6.  In the **Name** field, enter a unique name of up to 30 characters.

7.  In the **Description** field, enter a description of the transform of up to 1,000 characters.

8.  In the **Type** field, select **.NET Assembly**.

9.  Click **Load**, navigate to the assembly that you copied to the client bin directory, and then click **Open**.

10. In the **Class** field, select the class in the assembly that contains the transform you want to import.

11. Type CTRL+S to save the transform.


> [!WARNING]
> <P>We do not recommend adding multiple instances of the same .NET assembly to the <STRONG>Manage transforms</STRONG> form by using a different name for each instance. When multiple instances of the .NET assembly are listed in the form, each instance refers to the same .dll file. Changes to the .dll file will affect all ports that reference the transform, regardless of the name of the transform in the <STRONG>Manage transforms</STRONG> form.</P>



After you have imported the transform, you may add a new class to the assembly or change the code in an existing assembly class. For more information about how to import updated assemblies, see [Importing Updated .NET Assembly Transforms](importing-updated-net-assembly-transforms.md).

## See also

[About the AIF Pipeline and Transforms](about-the-aif-pipeline-and-transforms.md)

[Walkthrough: Creating a .NET Assembly Transform](walkthrough-creating-a-net-assembly-transform.md)

[Importing Updated .NET Assembly Transforms](importing-updated-net-assembly-transforms.md)

