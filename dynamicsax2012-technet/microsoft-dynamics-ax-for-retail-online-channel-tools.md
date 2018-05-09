---
title: Microsoft Dynamics AX for Retail online channel tools
TOCTitle: Online channel tools
ms:assetid: 0466aa89-0570-49bc-922f-7173c58621b0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn720291(v=AX.60)
ms:contentKeyID: 62221432
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Microsoft Dynamics AX for Retail online channel tools 


The Retail SDK contains some tools that help you maintain your online channel. After you compile the Tools solution, you can use the SharePoint cleanup tool, the configuration updater tool, and the publishing job configuration tool.

## Compile Tools.sln

To compile the tools solution, open the Tools solution, define the TRACE constant for each project, and then compile the solution. The tools have dependencies on SharePoint DLLs, so you must have SharePoint installed. They also have dependencies on retail publishing job DLLs, which are included in Microsoft Dynamics AX.

1.  Open **Retail SDK** \> **Online Channel** \> **Tools** \> **Tools.sln**

2.  Right-click **ConfigurationUpdater** and then click **Properties**.

3.  Select **Define TRACE constant**.

4.  Repeat steps 2 and 3 for the **Management**, **MVVM**, and **PublishingConfig** projects.

5.  Compile the Tools solution.

## PublishingConfig

The publishing job configuration tool allows you to set the server name where your channel database is located, the database name, and the channel operating unit number. The difference between the publishing job configuration tool and the configuration updater tool is the publishing job configuration tool updates the channel operating unit number only for the retail publishing job.

The publishing job configuration tool can be found in \\Retail SDK\\Online Channel\\Tools\\PublishingConfig\\PublishingConfig\\bin\\Debug after you compile Tools.sln.

### ![Dn720291.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720291.collapse_all(en-us,AX.60).gif")Configure the publishing job configuration tool

If you have more than one publishing job on the same farm, specify the publishing job you want to configure in the \<appSettings\> section of the App.config file in the PublishingConfig project. Expand the **Publishing job configuration tool parameters** section to see the available parameters.

### ![Dn720291.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720291.collapse_all(en-us,AX.60).gif")Publishing job configuration tool parameters

The following table describes the parameters of the publishing job configuration tool.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Server Name</p></td>
<td><p>Specifies the server name where the channel is located.</p></td>
</tr>
<tr class="even">
<td><p>DB Name</p></td>
<td><p>Specifies the database name.</p></td>
</tr>
<tr class="odd">
<td><p>Channel Operating Unit Number</p></td>
<td><p>Specifies the channel that will be published to SharePoint. You can find it in the Online store form under <strong>General</strong> &gt; <strong>Identification</strong> &gt; <strong>Operating unit number</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Force Catelogless Publishing</p></td>
<td><p>Controls the behavior of the SharePoint publishing job in retrieving products. By default, when this check box is cleared, only products that have been published as part of a catalog that is not expired will be published to and visible in SharePoint.</p>
<p>Selecting this check box will force the publishing job to retrieve products that were published directly to the channel, and that are not associated with any catalog.</p></td>
</tr>
<tr class="odd">
<td><p>Force Timing Info Logging</p></td>
<td><p>Specifies whether to force timing info logging.</p></td>
</tr>
<tr class="even">
<td><p>Check Every Listing For Removal</p></td>
<td><p>Controls the ‘Delete Listings’ behavior. If selected, the publishing job will check every listing that is published to SharePoint with the CRT to find out whether it still exists there. If the listing does not exist in the CRT, it will be removed from SharePoint. If this check box is cleared, individual listings will not be probed. Instead, the removal will only be possible if:</p>
<ul>
<li><p>A catalog was retracted - in this case all products of the catalog will be removed from SharePoint.</p></li>
<li><p>The channel's language was removed - in this case, all listings for that language will be removed from SharePoint.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Listing Title Attribute Key</p></td>
<td><p>Specifies the KeyName (name with no spaces) of the Microsoft Dynamics AX attribute that will be mapped to the field Title of each SharePoint listing. The property that is specified here becomes a mandatory property, and channel publishing will fail if the property is not included in the channel. You can see available KeyNames in the KeyName column of the RetailPubProductAttributeChannelMetadata table in the CRT database.</p></td>
</tr>
<tr class="even">
<td><p>Default Uncategorized List Prefix</p></td>
<td><p>Specifies a prefix for a SharePoint list's name that will be used to create uncategorized lists (a list that is not supposed to contain only listings for specific category).</p></td>
</tr>
<tr class="odd">
<td><p>Categories Page Size</p></td>
<td><p>Specifies the number of categories that will be read from the CRT in a single call.</p></td>
</tr>
<tr class="even">
<td><p>Product Attributes Page Size</p></td>
<td><p>Specifies the number of Product Attributes returned to the job by a single CRT call.</p></td>
</tr>
<tr class="odd">
<td><p>CRT Listings Page Size</p></td>
<td><p>Specifies the number of listings that will be returned by the CRT in a single call. Values that are too small could lead to performance degradation during catalog publishing. Values that are too high might lead to timeouts and other issues related to absence of sufficient resources.</p></td>
</tr>
<tr class="even">
<td><p>SharePoint Listings Map Page Size</p></td>
<td><p>Specifies the number of listings that will participate in a single query to a SharePoint list while figuring out whether the listings with the specified IDs are already present in SharePoint.</p></td>
</tr>
<tr class="odd">
<td><p>Listing Map Page Size</p></td>
<td><p>Specifies the size of the page to store the listings map.</p></td>
</tr>
<tr class="even">
<td><p>Max Catalog Size Per Publishing Iteration</p></td>
<td><p>Specifies the maximum catalog size per single job run.</p></td>
</tr>
<tr class="odd">
<td><p>Max List Field Count</p></td>
<td><p>Specifies the maximum number of attributes in a single SharePoint list.</p></td>
</tr>
<tr class="even">
<td><p>Max List Length For Initial Publishing</p></td>
<td><p>Specifies the maximum number of Listings in a single SharePoint list during initial publishing.</p></td>
</tr>
<tr class="odd">
<td><p>Max List Length For Incremental Publishing</p></td>
<td><p>Specifies the maximum number of Listings in a single SharePoint list during incremental publishing.</p></td>
</tr>
<tr class="even">
<td><p>Max Active Crawler Wait Time</p></td>
<td><p>Specifies the maximum number of seconds the job will wait for active crawlers to complete their job before a new crawl operation is initiated. Value of 0 means no limit.</p></td>
</tr>
<tr class="odd">
<td><p>Custom Types Mapping</p></td>
<td><p>Provides an ability to override a Microsoft Dynamics AX attribute's type with a specific SharePoint type. A custom type should have a value from the standard SharePoint enumeration SPFieldType. Microsoft Dynamics AX doesn't distinguish between short and long text – it has a single type Text. SharePoint has a limitation for the type which represents Single Line Of Text. Most of the properties are short enough (less than ~200 characters), but in some cases, for instance for fields Specification and Features, a Microsoft Dynamics AX attribute might have really long text and for those cases the mapping should be created.</p></td>
</tr>
<tr class="even">
<td><p>Partitioning Schema</p></td>
<td><p>Allows you to force the job to create a dedicated SharePoint list with a specified name for listings that contain a primary category represented by the specified category ID.</p></td>
</tr>
</tbody>
</table>


## Cleanup

The SharePoint cleanup tool can be used to clean up product catalog and publishing portal site collections from the entities that were created at runtime. This tool should only be used by developers.

### ![Dn720291.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720291.collapse_all(en-us,AX.60).gif")Configure the SharePoint cleanup tool

There are several actions that the tool can perform. Typically when you run the SharePoint cleanup tool, all the parameters would be set to true except for DeleteRequiredSchema.


> [!WARNING]
> <P>Consider the consequences before you run the tool while the DeleteRequiredSchema parameter is set to true. If you do, the redeployment (manual creation of ContentType, site columns, search properties) should be performed.</P>



You need to specify which actions for the tool to perform in the configuration file for the tool. To edit the configuration:

1.  Open the debug folder of the tool. For example, \\Retail SDK\\Online Channel\\Tools\\Cleanup\\bin\\Debug.

2.  Open the Microsoft.Dynamics.Retail.SP.Cleanup.exe config file in a text editor.

3.  Set the key values to configure the tool. You can specify whether to perform each cleanup action. For example, if you set the CleanupSearchSchema value to true, the tool will clean the search schema. If you set it to false, it won’t. For example,
    
        <add key=”CleanupSearchSchema” value=”true”/>

The following table shows the key values you can set:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Property</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>ProductCatalogUrl</p></td>
<td><p>The product catalog URL.</p></td>
</tr>
<tr class="even">
<td><p>PublishingPortalUrl</p></td>
<td><p>The URL of the publishing portal.</p></td>
</tr>
<tr class="odd">
<td><p>CleanupCategories</p></td>
<td><p>Set this property to clean up categories.</p></td>
</tr>
<tr class="even">
<td><p>DeleteCatalogConnections</p></td>
<td><p>If there is a problem with the connection between the publishing portal and the product catalog, you might want to delete catalog connections. After you do this, you should republish the catalog with at least one changed product. Otherwise, the connection wil not be created.</p></td>
</tr>
<tr class="odd">
<td><p>CleanupSearchSchema</p></td>
<td><p>If there is a problem with the search schema, you might want to set this property. This step should be followed by republishing a catalog to restore the system.</p></td>
</tr>
<tr class="even">
<td><p>ResetSearchIndex</p></td>
<td><p>If SharePoint Search is not picking up products in the product catalog, you might want to reset the search index. All products will be removed from SharePoint Search and from the publishing portal. To get them back, you must republish the full catalog from Microsoft Dynamics AX or manually initiate a full crawl in SharePoint.</p></td>
</tr>
<tr class="odd">
<td><p>DeleteRequiredSchema</p></td>
<td><p>Set this property to delete required schema.</p></td>
</tr>
<tr class="even">
<td><p>DeleteAllProductLists</p></td>
<td><p>If something is wrong with the products you published to the product catalog, you might want to delete all product lists and publish products again.</p></td>
</tr>
</tbody>
</table>


### ![Dn720291.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720291.collapse_all(en-us,AX.60).gif")Run the SharePoint cleanup tool

You must run the SharePoint cleanup tool on the computer that has SharePoint installed.

1.  Open a command prompt or Windows Powershell. For this example, press **Start + X**, **C** to open a command prompt.

2.  In the command prompt, navigate to the location of the SharePoint cleanup tool. For example, \\Documents\\Retail SDK\\Online Channel\\Tools\\Cleanup\\bin\\Debug.

3.  Type Microsoft.Dynamics.Retail.SP.Cleanup.exe to execute the application.

## ConfigurationUpdater

You can use the configuration updater tool to update the channel against which the online store operates. You might identify the channel that your storefront operates against by using record ID or Operating unit number. You can view the Operating unit number of a channel in the **Online stores** form. To open the form, click **Retail** \> **Retail channels** \> **Online stores**. To view the record ID of a channel, right-click the channel in the Online stores form, and then click **Record info**. In Microsoft Dynamics AX 2012 R3 and later, the Operating unit number is used to identify a channel.

The configuration updater tool can be found in \\Retail SDK\\Online Channel\\Tools\\ConfigurationUpdater\\bin\\Debug after you compile Tools.sln.

The configuration updater tool is a console application-based tool, so you need to run it through a command prompt or Windows Powershell.

### ![Dn720291.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720291.collapse_all(en-us,AX.60).gif")Configure the configuration updater tool

Before you run the configuration updater tool, you must specify which entities on the SharePoint farm you want to update. After you do that, any value you provide to the configuration updater tool will be applied to the entities on the SharePoint farm that you specify in the configuration file of the tool.

1.  Locate the ConfigureationUpdater.exe configuration file in the same folder as the ConfigurationUpdater application. For example, \\Documents\\Retail SDK\\Online Channel\\Tools\\ConfigurationUpdater\\bin\\Debug.

2.  Right-click the config file and open it with a text editor.

3.  In \<appSettings\>, specify the SharePoint web application (SiteNameExternal), the web site (SiteNameInteral), and the publishing job (PublishingJobSettingsName) values to identify which three entities to update on the SharePoint farm.

### ![Dn720291.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720291.collapse_all(en-us,AX.60).gif")Run the configuration updater tool

You must run the configuration updater tool on the computer that has SharePoint installed.

1.  Open a command prompt or Windows Powershell. For this example, press **Start + X**, **C** to open a command prompt.

2.  In the command prompt, navigate to the location of the configuration updater tool. For example, \\Documents\\Retail SDK\\Online Channel\\Tools\\ConfigurationUpdater\\bin\\Debug.

3.  Type ConfigurationUpdater.exe \<parameter1\> \<parameter2\>, where \<parameter1\> is the channel ID to update and \<parameter2\> is the channel operating unit number to update. If you don’t need both parameters, the parameter that isn't applicable to your deployment will be ignored.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

