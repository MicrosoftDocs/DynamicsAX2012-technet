---
title: Customizing the Help System
TOCTitle: Customizing the Help System
ms:assetid: bd340597-8ca9-4066-86d5-1c6deb07427d
ms:mtpsurl: https://technet.microsoft.com/library/Gg882382(v=AX.60)
ms:contentKeyID: 35257209
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Customizing the Help System 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX Help enables you to add new documentation, update existing documentation, and add entries to the table of contents. To customize documentation, you add one or more files to the Help server. While you can customize documentation, you cannot customize or change the operation of the Help server or the Help viewer. The following sections provide an overview of the types of customizations that you can perform and how you add or update Help documentation.

## Documentation

The Help documentation that you see is from a collection of document files on the Help server. To customize documentation, you add files to that collection. Before you attempt to customize documentation, you should be familiar with how the Help system framework organizes the documentation that you see. The following list contains several important concepts that affect how you customize documentation.

  - A content element is a single HTML file that contains the documentation for a specified topic. When you view documentation, the Help viewer displays a content element. To add or update Help documentation, you have to create a content element.

  - A topic is the documentation for a specified subject area. A topic must include at least one content element but can include two or more. In addition, a topic can include content elements from more than one publisher. To identify the content elements for a topic, each content element includes a document property that specifies a topic ID.

  - A publisher is an individual or organization that has documentation on the Help server. Each content element includes a document property that specifies the ID of a publisher. You also use the publisher ID to replace documentation for an existing topic.

  - A summary page is a list that the Help viewer displays when the requested topic includes more than one content element. To view a specific document, you click the link for that document.

  - A table of contents is a hierarchical list of topics that displays in the Help viewer. Each entry in the table of contents is a link to the documentation for that topic.

## Topics

All Help documentation is organized by topic. When you plan to customize the Help documentation, evaluate how your documentation fits into the existing topic structure. The following table describes the types of topic changes you can make.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Event</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Add a topic</p></td>
<td><p>To add a topic, you create documentation for a new process, form, class, or other component. A new topic requires that you define an ID for that topic. To create a context-sensitive topic, the topic ID has to match the ID of the form, class, or other component that you are documenting. In addition, a new topic might require that you add an entry to the table of contents.</p></td>
</tr>
<tr class="even">
<td><p>Update a topic</p></td>
<td><p>To update a topic, you create documentation that supplements or replaces an existing content element. An update documents a change, customization, or enhancement to an existing process, form, class, or other component. An update requires your content to include the same topic ID as the existing content element. To replace an existing content element, you have to know the ID of the publisher of that content element.</p></td>
</tr>
</tbody>
</table>


## Content Elements

Whether you create or update a topic, you have to create a content element. The content element contains the documentation that you see in the Help viewer. The typical content element is an HTML document but you can use other types of documents. Each content element includes a collection of document properties that the Help server uses to match your documentation to a Help request.


> [!WARNING]
> <P>Do not edit or delete any files that were created by Microsoft or any other publisher. If you change an existing file, your changes might be lost during an update or reinstall of the documentation from that publisher.</P>



To create a content element, you use XHTML. XHTML is a World Wide Web Consortium (W3C) standard that defines HTML as an XML document. The tag names in XHTML document must be lowercase. In addition, you must using closing tags for all the elements in the document. If you publish a content element that has an incorrect or missing tag, you will not be able to view that content element in the Help viewer.

## Table of Contents

You can add entries to the table of contents that appears in the Help viewer. You add an entry to the table of contents when you want your topic to be more easily discovered and viewed from the Help viewer. If you have several related topics, you can use the table of contents to display these topics as a hierarchical group.


> [!NOTE]
> <P>Adding entries to the table of contents is optional. You do not have to add an entry to the table of contents for each topic that you add or update. For example, an update to an existing topic does not need a new entry in the table of contents.</P>



To add a topic to the table of contents, you use XML to create an entry in a file that is named **TableofContents.xml**. If you have to remove your entry from the table of contents, delete that entry from the **TableofContents.xml** file. For more information about how to create an entry in the table of contents, see [How to: Create Table of Contents Entries](https://technet.microsoft.com/library/gg882385\(v=ax.60\)).

The table of contents that appear in the Help viewer can include entries from more than one publisher. The table of contents entries that appear in the Help viewer are grouped by publisher. As a result, you cannot use your TableofContents.xml file to add, update, or modify the table of contents entries supplied by another publisher. To specify where the table of contents entries for each publisher appears in the Help viewer, use the list of publishers in the web.config file of the Help server. For more information about how to update the web.config file, see [How to: Add a Publisher to the Web.Config File](https://technet.microsoft.com/library/gg882378\(v=ax.60\)).

## Producing Custom Documentation

After you identify the type of documentation that you need, you should consider how you will add this documentation to the Help server. Adding documentation to the Help server enables you to use the Help viewer and the existing context-sensitive help process. To help plan your customization, the following sections provide an overview of the processes that you use.

## Authoring

Authoring describes how you create new documentation for the Help system. Before you add or update a topic, use the following guidelines to plan your custom documentation.

  - Determine whether you want to create a new topic or update an existing topic. Identify the ID for your topic. If you update an existing topic, get the ID of that topic. If you are adding a new topic, determine whether to add an entry to the table of contents.

  - Define the content you need for your topic. Determine whether your documentation requires one or more content elements.

  - You should plan to create an HTML file for each content element that you identified. The Help server and Help viewer support the use of HTML.
    
    You can use file types other than HTML to produce documentation but you have to also include an HTML file that contains the required document properties. In addition, each client system that opens your document must have an application that can open and view that type of file.

  - You have to gather the information for the required document properties. The Help server uses these properties to identify the content elements that satisfy a Help request. Your content element must contain the required document properties or it will not appear in the Help viewer.

  - You have to determine whether you want your documentation to match the look of the existing Help documentation. To use the existing document styles, the HTML in your content element has to include several cascading style sheet, script, and image files. In addition, your HTML must use the styles defined in the cascading style sheet files.

  - If you plan to add an entry to the table of contents, you should plan to create a table of contents XML file. For more information about how to create a table of contents entry, see [How to: Create Table of Contents Entries](https://technet.microsoft.com/library/gg882385\(v=ax.60\)).

To simplify how you create documentation, the Help system includes a set of templates. The templates enable you to produce HTML or Microsoft Word documents that you can add to the Help server. For more information about how to create documents and modifying the table of contents, see [Authoring Help Documents](https://technet.microsoft.com/library/gg882301\(v=ax.60\)).

## Publishing

Publishing describes how you add a content element or table of contents file to the Help server. After you create a content element or table of contents file, you have to add that file to the file system of the Help server. Before you publish a file, use the following guidelines to determine whether you are ready to add files to the server.

  - Identify the folder on the Help server where you put files. Each publisher should maintain a separate set of folders. If you do not have an existing folder, you might have to create a new folder for your documentation.

  - Determine whether your logon identity has security permissions to add files to your target folder. If you first have to add a folder, make sure that you are permitted to create folders on the Help server. For more information about how to add folders, see [How to: Add Folders to the Help Server](https://technet.microsoft.com/library/gg882311\(v=ax.60\)).

  - Determine whether to add your publisher ID to the web.config file of the Help server. The list of publishers helps determine where your documentation appears in a list of search results and the table of contents. For more information about how to add a pulisher to the web.config file, see [How to: Add a Publisher to the Web.Config File](https://technet.microsoft.com/library/gg882378\(v=ax.60\)).

  - If you plan to create non-HTML content element, you have to include the HTML file that contains the document properties in the same folder as the document file.

After you publish the file, your documentation will be available to the Help viewer of any client system that can access that Help server. For more information about publishing, see [Publishing Overview](https://technet.microsoft.com/library/gg882369\(v=ax.60\)).

## See also

[Help System Components](help-system-components.md)

[Context Sensitive Help](https://technet.microsoft.com/library/gg882389\(v=ax.60\))

  


