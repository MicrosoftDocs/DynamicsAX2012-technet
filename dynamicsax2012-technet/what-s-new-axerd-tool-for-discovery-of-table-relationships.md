---
title: "What's new: AxErd tool for discovery of table relationships"
TOCTitle: AxErd tool for discovery of table relationships
ms:assetid: db83eede-c6f7-4a35-904c-25172787b4ba
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527239(v=AX.60)
ms:contentKeyID: 59623367
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# What's new: AxErd tool for discovery of table relationships [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The [AxErd website](http://go.microsoft.com/fwlink/p/?linkid=296623) provides 30 database entity relationship diagrams (ERDs). The ERDs display the foreign key relationships between the core tables in each of the application modules.

Aside from its ERD webpages, AxErd also has hundreds of other webpages that enable developers to easily find a variety of foreign keys. The website displays both the parent and child tables for any given target table. The website is rich with links that enable developers to traverse chains of tables that are associated by foreign key references. A display of tables categorized by their application module is also available. All this information is brought together to enable developers to extend our core ERDs, or to create new ERDs.

AxErd matches the database for Microsoft Dynamics AX 2012 R2, so it only approximates the database for Microsoft Dynamics AX 2012.

## AxErd webpage types

In addition to the ERD webpages, the AxErd website is composed of hundreds of webpages, each being one of four types:

  - PC - list of parent’s child tables.

  - CP - list of child’s parent tables.

  - MT - for each module, the tables in the module.

  - TM - for each table, the module that the table is in.

The webpages have numerous links to each other. For example, in many cases you can click on a parent table name in a PC page to jump to a CP page where that same table is the child.

## Comparison with alternative tools

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>Microsoft Dynamics AX 2012 R2</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Easily understand the boundaries between application modules in ERDs.</p></td>
<td><p>Security keys could provide information about module boundaries, in theory. But in practice it was a challenge to manually coordinate the references made to this information with foreign key information referenced separately from the cross-reference feature and from the AOT.</p></td>
<td><p>Security keys are obsolete and are ignored by the system.</p>
<p>The AxErd website has webpages dedicated to categorizing each table by its primary application module. On other types of webpages each table is tagged with its primary module as a clickable link.</p></td>
<td><p>An application developer who must customize a particular module benefits from knowing which tables are most essential to that module.</p></td>
</tr>
<tr class="even">
<td><p>Easily reference the foreign key information for a table, or for a chain of tables, to use when creating an ERD.</p></td>
<td><p>Versions earlier than Microsoft Dynamics AX 2012 R2 do provide information about both the parent and child tables for each given table. In the AOT under <strong>Data Dictionary</strong> &gt; <strong>Tables</strong> &gt; MyTable &gt; <strong>Relations</strong> there is a list of all the parent tables of the given table. But the AOT does not list the child tables of the given table.</p>
<p>Information that identifies the child tables can be obtained by using the cross-reference feature, but laborious clicking and scrolling is necessary to reach each child table.</p>
<p>The AOT and the cross-reference feature provide their foreign key information in different places from each other. This makes it more time-consuming to combine their information to create an ERD.</p></td>
<td><p>AxErd brings all foreign key information together in one place for both the parent and child tables.</p>
<p>The parent and child information is linked together in one place. This enables you to quickly and easily follow any chain of foreign keys, in either direction.</p></td>
<td><p>It is now more workable for you to create ERDs for the specific tables that are involved in your customization.</p></td>
</tr>
<tr class="odd">
<td><p>Look at ERDs provided by AxErd, each illustrating the relationships between the core tables in one application module.</p></td>
<td><p>There are no ERDs for earlier versions.</p></td>
<td><p>The AxErd website provides 30 core ERDs.</p></td>
<td><p>The application developer who customizes an application module often writes SQL in his X++ code. But the developer must first understand the relationships between the relevant tables before the SQL can be intelligently written. ERDs display the relationship information in a vivid and compact format.</p></td>
</tr>
</tbody>
</table>


## More information

  - [AxErd website home page](http://go.microsoft.com/fwlink/p/?linkid=296623)   

  - For instructions on how you can partially automate the task of extending or creating an ER diagram, click the **Help** link on the AxErd Home page. The steps involve using Microsoft Dynamics AX to generate a .ERx file, and then importing that file into Microsoft Visio 2010.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

