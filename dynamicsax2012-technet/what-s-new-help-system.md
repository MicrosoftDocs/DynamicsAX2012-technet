---
title: "What's new: Help system"
TOCTitle: Help system
ms:assetid: f1462f27-baf5-4e53-a628-fff337eeafb2
ms:mtpsurl: https://technet.microsoft.com/library/Dn527266(v=AX.60)
ms:contentKeyID: 59623394
author: Khairunj
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# What's new: Help system 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Help system in Microsoft Dynamics AX 2012 has been redesigned so that deployment and customization are easier. The following sections highlight the major features of the new Help system.


> [!NOTE]
> <P>This topic describes only the Help system that is used by the Win32 client of Microsoft Dynamics AX. The Help system for Enterprise Portal for Microsoft Dynamics AX is based on Microsoft&nbsp;SharePoint technology. Therefore, the information in this topic does not apply to Enterprise Portal Help. For information about Enterprise Portal Help, see <A href="administering-enterprise-portal.md">Administering Enterprise Portal</A>.</P>



## Client/server architecture

In AX 2012, the Help system uses a client/server architecture. Help content is hosted on a dedicated server component, the Help server, which manages the storage and display of product documentation. The Help viewer, which is a component of the Microsoft Dynamics AX client, provides access to Help from individual workstations. In earlier versions of Microsoft Dynamics AX, Help was stored locally on each client system.

This new architecture provides the following benefits:

  - You can publish an HTML file to a web server when you want to add or change a topic.

  - You can deploy and manage Help from a centralized location.

  - You can more easily apply Help updates that are provided by Microsoft.

## The Help server

The Help server is an Internet Information Services (IIS) web server that is located inside your organization's local area network (LAN). When a Microsoft Dynamics AX user requests a topic, the Help server receives the request, locates the topic on the LAN, and sends the topic to the Help viewer. The Help viewer then displays the topic.

For information about how to install and configure the Help server, see [Deployment of the Help server](deployment-of-the-help-server.md) and [Help server operations](help-server-operations.md).

## Adding documentation to the Help server

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
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Publish new or updated documentation.</p></td>
<td><p>Changes to Help topics required recompilation of .chm files.</p></td>
<td><p>You add or update documentation by putting files on the Help server.</p></td>
<td><p>You can add or update documentation to reflect the requirements of your organization.</p>
<p>You can also add ongoing updates from Microsoft and other publishers.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg882334(v=ax.60)">Publishing Documentation to the Help System</a></p></td>
</tr>
<tr class="even">
<td><p>Distribute documentation updates to users.</p></td>
<td><p>You had to install an updated .chm file on each client computer.</p></td>
<td><p>Documentation updates are available to all client computers when the update is published on the Help server.</p></td>
<td><p>You can make sure that all clients have access to the same documentation.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg882324(v=ax.60)">How to: Publish a Help Document</a></p></td>
</tr>
</tbody>
</table>


## The Help viewer

You can open the Help viewer by using the **Help** menu in the Microsoft Dynamics AX client, clicking the **Help** button in a Microsoft Dynamics AX form, or clicking links in various parts of the Microsoft Dynamics AX client. The viewer contains two panes. One pane contains a table of contents that represents the documentation that is available on the Help server. The other pane displays a topic that is selected in the **Contents** pane.

You can perform the following tasks by using the Help viewer:

  - Browse topic titles in the **Contents** pane.

  - Read topics in the display pane, and follow links to other topics and to Microsoft Dynamics AX forms.

  - Search the topics on the Help server by entering keywords in the **Search** field.

## Customization

The content for the Help system is stored in HTML files and deployed on a standard web server. Therefore, the Help system can easily be customized. Microsoft Dynamics AX has extensive Help resources that you can use, modify, or replace to meet your requirements. You can also control the way that topics are returned in user searches.

## Customizing topics

You can customize Help content in the following ways.

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
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create Help documentation.</p></td>
<td><p>Changes could be made to Help documentation, but the process was cumbersome. Often, you then had to recompile and replace .chm files.</p></td>
<td><p>Users, system administrators, and developers can create documentation.</p></td>
<td><p>You can customize the documentation to fit the requirements of your organization.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg882390(v=ax.60)">Writing Documentation for the Help System</a></p></td>
</tr>
<tr class="even">
<td><p>Use Microsoft Word to create documentation.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>You can use Word to create documentation.</p></td>
<td><p>Anyone who has Word can create Help documentation.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg882374(v=ax.60)">How to: Create a Help Document using a Template</a></p></td>
</tr>
<tr class="odd">
<td><p>Use HTML or text editors to create documentation.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>You can use HTML to create documentation.</p></td>
<td><p>You can use any HTML or text editor to produce documentation.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg882374(v=ax.60)">How to: Create a Help Document using a Template</a></p></td>
</tr>
<tr class="even">
<td><p>Use Microsoft Dynamics AX labels in documentation.</p></td>
<td><p>Labels could be included, but you then had to recompile .chm files.</p></td>
<td><p>You can insert labels from the client user interface into your HTML Help documentation.</p></td>
<td><p>Your documentation matches what the user sees on the client.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg882347(v=ax.60)">How to: Add Labels, Fields, and Menu Items to a Content Element</a></p></td>
</tr>
<tr class="odd">
<td><p>Hide topics from other publishers.</p></td>
<td><p>You could remove topics from a .chm file, but you then had to recompile and redistribute the file.</p></td>
<td><p>When you add new Help documentation, you can also hide outdated documentation that was supplied by other publishers.</p></td>
<td><p>The Help viewer always shows the most relevant Help documentation.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg882313(v=ax.60)">How to: Replace Help Documentation</a></p></td>
</tr>
</tbody>
</table>


## Customizing search

Search capability on the Help server is enabled by Windows Search Service, which supports both full-text search and keyword search. By default, Microsoft Dynamics AX Help content is configured for keyword search. However, you can select whether full-text search or keyword search is used. You can also use both kinds of search and specify a priority for each kind. In addition to customizing Help content, you can customize and use search in the following ways to meet your organization's requirements.

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
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Add or change the keywords that are assigned to topics to improve discoverability.</p></td>
<td><p>Changes could be made, but you then had to recompile .chm files.</p></td>
<td><p>You can add keywords that improve the ranking of your topic in a list of search results.</p></td>
<td><p>Search results are more accurate and informative.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg882301(v=ax.60)">Authoring Help Documents</a></p></td>
</tr>
<tr class="even">
<td><p>View rich search results.</p></td>
<td><p>Search results from the .chm files were presented as a list of topic titles.</p></td>
<td><p>Search results contain topic titles, topic summaries, and links to additional sources of Help documentation.</p></td>
<td><p>You can use the summaries to find the documentation that you require.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg882357(v=ax.60)">Description Element</a></p></td>
</tr>
</tbody>
</table>


## Web connectivity

The Microsoft Help that is included with Microsoft Dynamics AX is also published on the web, where it is updated and supplemented by other Help resources. From the **Help** menu in the Microsoft Dynamics AX client, power users, system administrators, and developers can connect to web-based Help on TechNet and MSDN. Users who cannot find appropriate search results by using the Help viewer can continue their searches on the web without re-entering the search terms. A web search tool provides filtered searches that return focused search results.

## Support for multiple publishers

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
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>View Help documentation that is produced by more than one publisher.</p></td>
<td><p>Adding documentation to the .chm files was difficult. Therefore, Help documentation was often located in separate files.</p></td>
<td><p>The Help viewer automatically retrieves and displays documentation from all publishers.</p></td>
<td><p>The Help viewer automatically includes documentation from Microsoft, partners, developers, and other publishers.</p>
<p>For example, if you write an update to a procedure, your update can appear next to the Help documentation that Microsoft provides.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg882369(v=ax.60)">Publishing Overview</a></p></td>
</tr>
<tr class="even">
<td><p>Add entries to the table of contents.</p></td>
<td><p>Changes could be made, but you then had to recompile .chm files.</p></td>
<td><p>Each publisher can add table of contents entries for new documentation.</p></td>
<td><p>Your table of contents entries are added to the main table of contents that appears in the Help viewer.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg882385(v=ax.60)">How to: Create Table of Contents Entries</a></p></td>
</tr>
</tbody>
</table>


## Are there any special considerations?

To enable the customization of Help documentation, you have to add a folder to the Help server. Writers then put documentation files in this folder. A writer that publishes documentation files has to have write or modify security permissions to the folder.

  


