---
title: "What's New: Visual Studio Tools for Developers in Microsoft Dynamics AX 2012"
TOCTitle: Visual Studio Tools for Developers
ms:assetid: ae392160-88e1-415f-a676-c7b5e7c7db23
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg863931(v=AX.60)
ms:contentKeyID: 35249729
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# What's New: Visual Studio Tools for Developers in Microsoft Dynamics AX 2012 [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This page lists the new and enhanced features for Visual Studio Tools available in Microsoft Dynamics AX 2012.

Microsoft Dynamics AX now provides an integrated development experience with Visual Studio. Visual Studio Tools for Microsoft Dynamics AX (Visual Studio Tools) is a set of tools and functionality that support development for Microsoft Dynamics AX in .NET managed code. Visual Studio Tools contains tools and functionality from both the MorphX and Visual Studio development environments.

## What is new or changed?

This feature has changed considerably since Microsoft Dynamics AX 2009. In addition to the new features that have been added, support for managed code has been integrated into Microsoft Dynamics AX in various ways.

New features have been added to the tools for modeling business application elements in Visual Studio. You can now add Visual Studio projects to Microsoft Dynamics AX and they are stored in the same model store as X++ code. You can view Visual Studio projects from either the Application Explorer in Visual Studio or the Application Object Tree (AOT) in MorphX. Reporting projects created in Visual Studio are stored in granular and customizable elements in the AOT. Source control is available for application projects from either the AOT or Visual Studio. The following sections describe the components that comprise Visual Studio Tools.

  - Application Explorer

  - Managed Code Business Logic

  - Proxies

  - Managed Code Event Handlers

  - Deployment

  - Cross-Reference Tool Support for Managed Code

  - Code Upgrade Tools Support for Managed Code

### ![Gg863931.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg863931.collapse_all(en-us,AX.60).gif")Application Explorer

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>Microsoft Dynamics AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The Application Explorer displays a view of the AOT within the Visual Studio IDE.</p></td>
<td><p>Model View enabled developers to view, create, edit, and delete models in a reporting project.</p></td>
<td><ul>
<li><p>View, open for edit, and delete code elements in the model store whether they are managed code or X++ elements</p></li>
<li><p>Edit reports and Enterprise Portal Web controls</p></li>
<li><p>Add managed code projects to the model store</p></li>
<li><p>Edit managed projects that have been added to the AOT (model store)</p></li>
<li><p>View X++ code</p></li>
</ul></td>
<td><p>Enables you to see all objects in the model store from the Visual Studio IDE.</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/cc637855(v=ax.60)">Application Explorer</a></p></td>
</tr>
</tbody>
</table>


### ![Gg863931.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg863931.collapse_all(en-us,AX.60).gif")Managed Code Business Logic

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>Microsoft Dynamics AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>You can write business logic in .NET languages and manage this code in Microsoft Dynamics AX just as you would with X++ classes.</p></td>
<td><p>Feature not available.</p></td>
<td><ul>
<li><p>You can save .NET class library projects to the model store.</p></li>
<li><p>You can customize these managed code projects using the various layers.</p></li>
<li><p>You can build managed code projects in Visual Studio and they are automatically deployed if configured to do so.</p></li>
</ul></td>
<td><p>Developing code that integrates with Microsoft Dynamics AX is now possible in Visual Studio. The full development and deployment scenario is supported for managed code.</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg889157(v=ax.60)">Visual Studio Development for Microsoft Dynamics AX</a></p>
<p><a href="http://go.microsoft.com/fwlink/?linkid=206389">Getting Started with Visual Studio</a></p></td>
</tr>
</tbody>
</table>


### ![Gg863931.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg863931.collapse_all(en-us,AX.60).gif")Proxies

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>Microsoft Dynamics AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Allows you to add an X++ class or table to your project in Visual Studio so it can be accessed by managed code.</p></td>
<td><p>Feature not available.</p></td>
<td><p>When you add an X++ class or table to a project by using the Application Explorer, a proxy for that class is created internally by the system. After the proxy is created, that type is then available as a strong type and features like IntelliSense are available.</p></td>
<td><p>You can easily add X++ objects to your Visual Studio project and write managed code that accesses those objects.</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg889157(v=ax.60)">Visual Studio Development for Microsoft Dynamics AX</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/gg889200(v=ax.60)">Walkthrough: Adding an X++ Object to a Visual Studio Project</a></p></td>
</tr>
</tbody>
</table>


### ![Gg863931.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg863931.collapse_all(en-us,AX.60).gif")Managed Code Event Handlers

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>Microsoft Dynamics AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>You can create a managed code event handler for an instance method of an X++ class.</p></td>
<td><p>Feature not available.</p></td>
<td><p>The event handler subscribes to the X++ event and can be called before the method begins or after the method completes. You can handle events raised only by a class in the <strong>Classes</strong> node in the AOT.</p></td>
<td><p>You can now create event handlers in managed code as well as X++. This means you can write .NET code to handle class events.</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg889181(v=ax.60)">Walkthrough: Creating an Event Handler in Visual Studio</a></p></td>
</tr>
<tr class="even">
<td><p>You can create a managed code event handler for an X++ delegate.</p></td>
<td><p>Feature not available.</p></td>
<td><p>The event handler subscribes to the X++ delegate, and the code runs when the delegate fires.</p></td>
<td><p>You can now create event handlers in managed code as well as X++. This means you can write .NET code to handle delegate events.</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg889181(v=ax.60)">Walkthrough: Creating an Event Handler in Visual Studio</a></p></td>
</tr>
</tbody>
</table>


### ![Gg863931.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg863931.collapse_all(en-us,AX.60).gif")Deployment

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>Microsoft Dynamics AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The deployment functionality enables you to automatically deploy managed assemblies (DLLs) that you create in Visual Studio to Microsoft Dynamics AX.</p></td>
<td><p>Feature not available.</p></td>
<td><p>Managed code assemblies are automatically deployed to the location that you specify: client, server, Reporting Services or Enterprise Portal. You can specify where the assembly is deployed by setting project properties in Visual Studio. After you deploy an assembly, you can then see the managed code classes via IntelliSense and call the managed code from X++.</p></td>
<td><p>Deployment happens automatically to the locations you specify.</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg889192(v=ax.60)">Deploying Managed Code</a></p></td>
</tr>
</tbody>
</table>


### ![Gg863931.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg863931.collapse_all(en-us,AX.60).gif")Cross-Reference Tool

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>Microsoft Dynamics AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The <a href="https://technet.microsoft.com/en-us/library/aa626961(v=ax.60)">Cross-reference Tool</a> in Microsoft Dynamics AX lets you see the relationships between elements and now supports managed code that that has been added to the model store.</p></td>
<td><p>Feature not available.</p></td>
<td><p>In order to see cross-references for a Visual Studio project, you must first add the project to the model store by using the Application Explorer. After you add a project to the model store, the project and its cross-reference information are updated every time you build the project.</p></td>
<td><p>Managed code is now supported by the Cross-reference Tool in MorphX. This means you can see the same cross-reference information for both X++ and managed code. For example, when you access the Cross-reference Tool from a report, you can see what the report data source.</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg889138(v=ax.60)">Cross-References and Visual Studio Projects</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/gg889239(v=ax.60)">Walkthrough: Using the Cross-Reference Tool with Visual Studio Projects</a></p></td>
</tr>
</tbody>
</table>


### ![Gg863931.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg863931.collapse_all(en-us,AX.60).gif")Code Upgrade Tools

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>Microsoft Dynamics AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Microsoft Dynamics AX supports layer-based customizations for managed code. Therefore, the tools that enable developers to find and resolve conflicts that result from those customizations also support managed code. The code upgrade tools enable developers to detect and resolve conflicts between two versions of Microsoft Dynamics AX.</p></td>
<td><p>Feature not available.</p></td>
<td><p>The conflict detection and resolution tools enable developers to find conflicts and compare customizations in different layers. These tools are available in the MorphX IDE and include the following:</p>
<ul>
<li><p>Detect code upgrade conflicts tool - Reports conflicts in both X++ and managed code that has been added to the model store.</p></li>
<li><p>Compare tool – Enables you to compare both X++ code and managed code in two layers and resolve any conflicts.</p></li>
</ul></td>
<td><p>The code upgrade tools that are included with Microsoft Dynamics AX support managed code development. Therefore, the same code upgrade process can be used for code whether it originates in MorphX or in Visual Studio.</p>
<p>These tools are used to detect and resolve code conflicts when upgrading to a new version of Microsoft Dynamics AX, installing customizations, or installing new modules developed by a VAR or partner.</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg889224(v=ax.60)">Upgrade Support for Managed Code</a></p></td>
</tr>
</tbody>
</table>


## See also

[What's New in Microsoft Dynamics AX 2012 for Developers](https://technet.microsoft.com/en-us/library/gg845327\(v=ax.60\))

[Visual Studio Development for Microsoft Dynamics AX](https://technet.microsoft.com/en-us/library/gg889157\(v=ax.60\))

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

