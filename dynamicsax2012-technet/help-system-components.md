---
title: Help System Components
TOCTitle: Help System Components
ms:assetid: 9913bc81-fa57-4401-8546-7dc50c01e32e
ms:mtpsurl: https://technet.microsoft.com/library/Gg882366(v=AX.60)
ms:contentKeyID: 35257195
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Help System Components 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX Help is a client and server based system that distributes and displays documentation.

  - The client is the Help viewer application that requests and displays documentation. The Help viewer installs with the Microsoft Dynamics AX client application.

  - The server is the Help server that responds to the Help viewer request for documentation. In addition, the Help server stores the files that contain the Help documentation.


> [!IMPORTANT]
> <P>The Help system does not supply Help documentation for Enterprise Portal.</P>



The following illustration shows how the Help viewer and Help server interact with the client and the Application Object Server (AOS). In addition, the illustration identifies the sequence of events that occur between the request and display of a document.

Help system components and events

  
![Help system components and events](images/Gg882366.HelpSystem_Components(AX.60).gif "Help system components and events")Help system components and events

The following sections discuss how each component responds to a typical request for Help documentation.

## Microsoft Dynamics AX client

The client application is the workspace you use to view and update information. Typically, you initiate a help request from either the client or developer workspace. For example, you press F1 or click a button or command to obtain Help while you are viewing a form. To get documentation for that form, the client performs the following actions:

  - The client identifies the Help topic to retrieve. For example, the client obtains the ID of the form that was open when you pressed F1. To identify the documentation for the form, the documentation has an ID property that has the same value as the ID of the form.

  - The client retrieves the URL of the Help web service. The first time that you request help; the client contacts the AOS to retrieve the URL of the help web service. The client then caches the URL and uses the cached URL for additional help requests.

  - The client calls the Help viewer. If the Help viewer is not running, the viewer is started. The call to the Help viewer includes the URL of the help server and the ID of the form.

## Help Viewer

The Help viewer is an application that retrieves and displays documentation. To retrieve documentation, the Help viewer requires a URL, and a topic ID or search parameters. Typically, the client provides the URL and ID. However, you can use a link, button, or command in the Help viewer to request a topic or search for documentation. The Help viewer then contacts the Help server and requests the specified documentation. After the Help server responds, the Help viewer displays the documentation in the viewer window. The Help viewer displays the following types of information.

  - The Help viewer displays the specified documentation.

  - If the Help server finds more than one document for the specified topic ID, the Help viewer displays a list of the available documents. The list includes links to the individual documents for that topic. To see specific a document, click the link for that document.

  - If you perform a search, the Help viewer lists the documents that match your search query. To open a specific document in the Help viewer, click the link for that document.

  - The Help viewer displays the table of contents. The table of contents contains links to other topics.

## Help Server

Help server is the name given to a group of related components that respond to a request for documentation from a Help viewer. When you install the Help server, you add the following components to the specified server.

## Help Web Service

The Help web service is an IIS web service that responds to a Help viewer request for documentation. The Help web service receives the request, finds the documentation that matches the request, retrieves the text for specified labels from the AOS, adds the label text to the HTML of the document, and then sends the HTML documentation to the Help viewer.

## Document Files

The install adds a collection of HTML and XML files to folders on the web server. The HTML files are the documents that contain the information that appears in the Help viewer. The XML files contain the table of contents information that appears in the Help viewer.

Each HTML file includes a set of document properties. To respond to a request, the Help web service does a search for documents that have properties that match the criteria in the Help viewer request. A typical request includes criteria that match one or more of the following properties.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Property type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Document ID</p></td>
<td><p>The ID that uniquely identifies a document. In the HTML file, the document ID is the <strong>Microsoft.Help.Id</strong> property.</p></td>
</tr>
<tr class="even">
<td><p>Document set</p></td>
<td><p>The name of the document set associated with the client workspace. In the HTML file, the document set is the <strong>DocumentSets</strong> property.</p></td>
</tr>
<tr class="odd">
<td><p>Language</p></td>
<td><p>Specifies the language displayed by the Help viewer. In the HTML file, the language is the <strong>Language</strong> property.</p></td>
</tr>
<tr class="even">
<td><p>Topic ID</p></td>
<td><p>The ID that specifies the documentation about a subject area. In the HTML file, the topic ID is the <strong>Microsoft.Help.F1</strong> property.</p></td>
</tr>
</tbody>
</table>


## Windows Search Service

The install enables the Windows Search Service. The Windows Search Service indexes all the document files that are added to the web server. The index includes the document properties found in each HTML file. When the Help web service receives a request, it queries the search service to find the document files that match the criteria specified by the request.

The following table specifies the precedence used to rank the content elements that appear in the list of search results. For example, a content element that has a keyword that matches the search request appears at the top of the list of search results.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Document element</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Keywords</p></td>
<td><p>The search service matches the search request to a specified keyword for a content element.</p></td>
</tr>
<tr class="even">
<td><p>Title</p></td>
<td><p>The search service matches the search request to part of the title of the content element.</p></td>
</tr>
<tr class="odd">
<td><p>Topic ID</p></td>
<td><p>The search service matches the search request to the topic ID of the content element.</p></td>
</tr>
<tr class="even">
<td><p>Content</p></td>
<td><p>The search service matches the search request to one our more values found in the body of the content element.</p></td>
</tr>
</tbody>
</table>


## Document Sets

A document set is a named collection of related help topics. All the document files on the Help server are a member of a document set. You use document sets to associate a collection of help documents to the client or developer workspace. The Help system includes the following documents sets:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Name</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>DeveloperDocumentation</strong></p></td>
<td><p>The document set that provides help information for users of the Microsoft Dynamics AX developer workspace. You cannot add new documents to the <strong>DeveloperDocumentation</strong> document set.</p></td>
</tr>
<tr class="even">
<td><p><strong>UserDocumentation</strong></p></td>
<td><p>The document set that provides help information for users of the Microsoft Dynamics AX client workspace.</p></td>
</tr>
</tbody>
</table>


## Application Object Server

To support the Help system, the AOS performs the following actions.

  - The AOS stores the URL of the Help server. Each Help viewer retrieves this URL before sending a request for documentation. This guarantees that changes to the URL of the Help server are available to all the clients of the AOS.

  - The AOS returns the text associated with a label. A label is the localized text you see in the user interface of the Microsoft Dynamics AX client. The Help web service retrieves label text and adds that text to the HTML of the document file. This allows the text in the documentation to match the text and language found in the user interface of the Microsoft Dynamics AX client.

  


