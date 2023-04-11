---
title: Install multiple Microsoft Dynamics AX Retail online stores
TOCTitle: Install multiple online stores
ms:assetid: eaaf0114-934b-4644-8d77-16e39cace6d2
ms:mtpsurl: https://technet.microsoft.com/library/Dn720296(v=AX.60)
ms:contentKeyID: 62221437
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Install multiple Microsoft Dynamics AX Retail online stores 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to create a second Microsoft Dynamics AX Retail online store. You deploy a second online store by using Windows PowerShell after you make changes in the oob-settings.xml and oob-topology.xml files. The second online store shares some components with the first or primary online store. In the context of the Microsoft Dynamics AX Retail online store, these shared components are combined into an entity called Common Global Modules.

This topic includes the following information.

  - Before you begin

  - Install a second online store

  - Walkthrough: Install a second online store for French language users

## Before you begin

You must complete the following tasks before you deploy a second Retail online store.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Install the primary online store</p></td>
<td><p>A second online store shares global components with the primary online store. You must install a primary online store before you install a second store. For more information, see <a href="install-a-retail-online-store-e-commerce.md">Install a Retail online store (e-commerce)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Create a copy of the primary online store XML files</p></td>
<td><p>Locate the oob-settings.xml and oob-topology.xml files for the primary online store in the following folder:</p>
<p>C:\Program Files (x86)\Microsoft Dynamics AX\60\Retail Online Channel\tools</p>
<p>Make a copy of these files so that you have a record of the settings used for the primary online store.</p></td>
</tr>
</tbody>
</table>


## Install a second online store

You must install the second online store by using Windows PowerShell. And you must configure the following parameters in the oob-settings and oob-topology XML files. Because you made a copy of the primary online store XML files, you can update parameters directly in the XML files in the C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Online Channel\\tools folder.

If you installed the primary online store by using Setup.exe, the system creates new copies of the oob-settings.xml and oob-topology.xml files. These files are called oob-settings-updated.xml and oob-topology-updated.xml. The updated files contain the configuration settings you entered in Setup.exe. Make copies of the updated files and store them in a separate location. In the Tools folder, change the names back to oob-settings.xml and oob-topology.xml and configure these again as described in this section.


> [!NOTE]
> <P>This procedure describes how to install a second online store for English language users. If you want to install a second online store for French language users, see Walkthrough: Install a second online store for French language users in this topic.</P>



### ![Dn720296.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720296.collapse_all(en-us,AX.60).gif")Oob-settings.xml

Specify unique values for the following parameters in the oob-settings.xml file.

  - SharepointPackageInstanceIdentifier

  - StoreFrontUrlPort\_Public

  - StoreFrontUrlPort\_SSL\_Public

  - StoreFrontUrlPort\_Internal

  - ProductCatalogUrlPort\_Internal

  - DestinationId

  - ChannelOperatingUnitNumber

The following values must be identical for multiple online stores in a SharePoint web farm.

  - IdentityProviderDatabaseServerName

  - CustomClaimsProviderDatabaseServerName

The following values can be identical or different for multiple online stores in a SharePoint web farm.

  - ChannelDatabaseServerName

  - ChannelDatabaseServerNamedInstanceNam

### ![Dn720296.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720296.collapse_all(en-us,AX.60).gif")Oob-topology.xml

Update the following parameters in the oob-topology.xml file.

1.  Disable deployment for the CommonGlobalModules. These globally shared components were installed with the primary online store deployment. Set the following parameters to false, as shown here:
    
    \<WSPPackage generate="false" deploy="false" retract="false"\> \<RootFolder\>..\\CommonGlobalModules\</RootFolder\>

2.  Disable the custom claims provider feature. These globally shared components were installed and activated with the primary online store deployment. Set the following parameter to false, as shown here:
    
    \<FeatureToActivate activate="false" name="SharePoint.Web.Storefront\_CustomClaimsProviderSettingsFeature\_\[SharepointPackageInstanceIdentifier\]" urlXpath="Settings/SiteCollection\[@id='RetailPublishingPortal'\]/Url" /\>

3.  Disable the TrustedIdentityTokenProvider. You will reuse the identity providers that were installed with the primary online store deployment. Set the following parameters to false, as shown here:
    
    \<TrustedIdentityTokenIssuer id="Facebook" install="false" deleteifexists="false"\>

4.  Save your changes.

5.  Run the Windows PowerShell commands to install the second online store. For more information, see [Install a Retail online store (e-commerce)](install-a-retail-online-store-e-commerce.md).

## Walkthrough: Install a second online store for French language users

This walkthrough describes how to install a second online store for French language users. You must install a second online store by using Windows PowerShell. To install a second online store for different languages, change the parameter values below.

### ![Dn720296.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720296.collapse_all(en-us,AX.60).gif")Before you begin

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Download and install the French language pack for SharePoint.</p></td>
<td><p>You can download SharePoint language packs from Microsoft.com.</p></td>
</tr>
<tr class="even">
<td><p>If you have not already done so, make a copy of the primary online store XML files and stores these in a separate location.</p></td>
<td><p>By default, the files are located in the following directory:</p>
<p>C:\Program Files (x86)\Microsoft Dynamics AX\60\Retail Online Channel\tools folder</p></td>
</tr>
</tbody>
</table>


### ![Dn720296.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720296.collapse_all(en-us,AX.60).gif")Configure the XML files

You must install the second online store by using Windows PowerShell. And you must configure the following parameters in the oob-settings and oob-topology XML files. Because you made a copy of the primary online store XML files, you can update parameters directly in the XML files in the C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Online Channel\\tools folder.


> [!IMPORTANT]
> <P>If you installed the primary online store by using Setup.exe, the system creates new copies of the oob-settings.xml and oob-topology.xml files. These files are called oob-settings-updated.xml and oob-topology-updated.xml. The updated files contain the configuration settings you entered in Setup.exe. Make copies of the updated files and store them in a separate location. In the Tools folder, change the names back to oob-settings.xml and oob-topology.xml and configure these again as described in this section.</P>



#### ![Dn720296.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720296.collapse_all(en-us,AX.60).gif")Oob-settings.xml

Open the oob-settings.xml file from the following location and enter the values specified in the table for each parameter. By default, the file is located in the following directory:

C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Online Channel\\tools folder

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>What to enter</p></th>
<th><p>Details</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>SharepointPackageInstanceIdentifier</strong></p></td>
<td><p>2</p></td>
<td><p>This value assumes that you entered 1 for the primary online store. This number must be unique from other online stores.</p></td>
</tr>
<tr class="even">
<td><p><strong>StoreFront_LanguageId</strong></p></td>
<td><p>1036</p></td>
<td><p>Enter a language code identifier (LCID). This ID must match the SharePoint language pack deployed to the server.</p></td>
</tr>
<tr class="odd">
<td><p><strong>StoreFront_DeviceChannelsListName</strong></p></td>
<td><p>Canaux des appareils</p></td>
<td><p>This value is the name of a SharePoint Design Manager list that stores device channels. For more information about device channel lists, see <a href="https://go.microsoft.com/fwlink/?linkid=394743">SharePoint 2013 Design Manager device channels</a>. The name of this value varies based on locale. For example, if you are deploying the online store by using the en-US locale then the name should be Device Channels. If you are deploying for an online store for fr-FR (French) locale then this name should be Canaux des appareils.</p></td>
</tr>
<tr class="even">
<td><p><strong>StoreFrontUrlPort_Public</strong></p></td>
<td><p>60002</p></td>
<td><p><strong>The port for the public online store site</strong>: You can specify any available port.</p></td>
</tr>
<tr class="odd">
<td><p><strong>StoreFrontUrlPort_SSL_Public</strong></p></td>
<td><p>60004</p></td>
<td><p><strong>The port for the public online store site for encrypted communications</strong>: You can specify any available port.</p></td>
</tr>
<tr class="even">
<td><p><strong>StoreFrontUrlPort_Internal</strong></p></td>
<td><p>60003</p></td>
<td><p><strong>The port for the internal online store site</strong>: You can specify any available port. This URL is only accessed by domain users with permission to make changes to the site collection by using SharePoint site settings. It is not required, but you can change this port value if you want the internal online store to use a different port.</p></td>
</tr>
</tbody>
</table>


Save your changes in the file.

#### ![Dn720296.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720296.collapse_all(en-us,AX.60).gif")Oob-topology.xml

Open the oob-settings.xml file from the following location and enter the values specified in the table for each parameter. By default, the file is located in the following directory:

C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Online Channel\\tools folder

1.  Disable deployment for the CommonGlobalModules. These globally shared components were installed with the primary online store deployment. Set the following parameters to false, as shown here:
    
    \<WSPPackage generate="false" deploy="false" retract="false"\> \<RootFolder\>..\\CommonGlobalModules\</RootFolder\>

2.  Disable the custom claims provider feature. These globally shared components were installed and activated with the primary online store deployment. Set the following parameter to false, as shown here:
    
    \<FeatureToActivate activate="false" name="SharePoint.Web.Storefront\_CustomClaimsProviderSettingsFeature\_\[SharepointPackageInstanceIdentifier\]" urlXpath="Settings/SiteCollection\[@id='RetailPublishingPortal'\]/Url" /\>

3.  Disable deployment for the publishing job. This deployment will share a publishing job with the primary deployment. Set the following parameter to false, as shown here:
    
    \<WSPPackage generate="false" deploy="false" retract="false"\>\<RootFolder\>..\\RetailJobs\</RootFolder\>

4.  Disable web app deployment. This site will share a web application with the primary deployment. Set the following parameter to false, as shown here:
    
    \<WebApplication id="RetailC1Webapplication" install="false" deleteifexists="false"\>

5.  Disable Product Catalog site collection deployment. This site will share a product catalog site collection with the primary deployment. Set the following parameter to false, as shown here:
    
    \<SiteCollection id="RetailProductCatalog" install="false" deleteifexists="false"\>

6.  Disable the TrustedIdentityTokenProvider. You will reuse the identity providers that were installed with the primary online store deployment. Set the following parameters to false, as shown here:
    
    \<TrustedIdentityTokenIssuer id="Facebook" install="false" deleteifexists="false"\>

7.  Save your changes.

### ![Dn720296.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720296.collapse_all(en-us,AX.60).gif")Run Windows PowerShell scripts

Use this procedure to run the Windows PowerShell commands to install the second online store. For more detailed information about these scripts, see “Run PowerShell scripts to create and configure the online store” in [Install a Retail online store (e-commerce)](install-a-retail-online-store-e-commerce.md).


> [!NOTE]
> <P>Windows PowerShell includes a security setting called the execution policy that determines how scripts are run. By default, the execution policy is set to <STRONG>Restricted</STRONG>, which prevents any scripts from running. To run the installation scripts for Microsoft Dynamics AX components, we recommend that you set the execution policy to <STRONG>RemoteSigned</STRONG> by using Set-ExecutionPolicy cmdlet. This setting allows you to run scripts that you’ve written and scripts that have been signed by a trusted publisher.</P>



1.  On the server where you want to run the scripts, open the tools folder where the PowerShell scripts are installed. By default, they are located here:
    
    C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Online Channel\\tools folder

2.  If you’re using Windows Server 2012 or a later operating system, use Windows Explorer to open the folder where the scripts are installed. Then click File \> Open Windows PowerShell \> Open Windows PowerShell as administrator.
    
    If you’re using Windows Server 2008 R2 or an earlier operating system, start pw\_wps as the administrator. Then, change the directory by using the following command: CD “\<Path to directory\>”.

3.  Run the following command to verify and install prerequisites for the online store:
    
        .\InstallPrereqs-SPFarm.ps1 oob-topology.xml oob-settings.xml
    
    When the system finishes the operation, you can execute the next script.

4.  In the Windows PowerShell console, run the following command to generate the WSP file for the online store:
    
        .\Generate-WSP.ps1 oob-topology.xml oob-settings.xml
    

    > [!IMPORTANT]
    > <P>Due to a known issue, the following script can fail with a file access error. If the script fails, re-run it. It should finish successfully the second time.</P>



5.  In the Windows PowerShell console, run the following command to deploy the solution to SharePoint.
    
        .\Deploy-FarmSolutions.ps1 oob-topology.xml oob-settings.xml

### ![Dn720296.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720296.collapse_all(en-us,AX.60).gif")Configure the channel for French language users

Use the following procedures to configure language settings for the channel. You must complete each procedure in this section.

#### ![Dn720296.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720296.collapse_all(en-us,AX.60).gif")Update StorefrontResources.js

Update the StorefrontResources.js file by replacing the English language (en-us) parameter with the French language (fr-fr) parameter.

1.  By using WebDAV, navigate to the folder that corresponds to the French Publishing Portal. For example: Y:\\\_catalogs\\masterpage\\Display Templates\\Language Files. For more information, see [Map a network drive to the SharePoint 2013 files for online stores](map-a-network-drive-to-the-sharepoint-2013-files-for-online-stores.md).

2.  Copy **StorefrontResources.js** from the **en-us** folder into the **fr-fr** folder.

3.  In the **fr-fr** folder, open the **StorefrontResources.js** file. Search for the following line:
    
    $registerResourceDictionary("en-us", {

4.  Replace **en-us** in this line with **fr-fr**, as shown:
    
    $registerResourceDictionary("fr-fr", {

5.  Save your changes.

6.  Open a web browser and view the French version of the Publishing Portal to verify that it is available. If you specified 600002 for the port, enter the server name into the following URL to view it in a browser:
    
    http://ServerName:60002/sites/RetailPublishingPortal

#### ![Dn720296.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn720296.collapse_all(en-us,AX.60).gif")Translate categories in the Microsoft Dynamics AX client

1.  **Navigation Path Not Found**

2.  In the Retail channel navigation hierarchies list, double-click the hierarchy for your channel.

3.  In the toolbar, click Edit category hierarchy

4.  In the left pane, click a category and then click the Translations button in the toolbar.

5.  Select French in the Language drop-down list

6.  Click "Plus" button and add French language

7.  Provide translations in all 3 boxes and then click Close

8.  Repeat this process for all categories.

## Configure the publishing job

1.  In SharePoint Central Administration, under **System Settings**, click **Manage Farm Features**.

2.  Find Retail Publishing Job 1 in the list and click **Deactivate**.

3.  In Windows Explorer, locate the following file and open it in Notepad:
    
    C:\\Program Files\\Common Files\\microsoft shared\\Web Server Extensions\\15\\TEMPLATE\\FEATURES\\SharePoint.Services.RetailJobs\_RetailPublishingJobFeature\_1\\Assets\\RetailPublishingJob.App.config

4.  Search for the \<PublishingPortals\> section. Replace the existing section with the following:
    
        <PublishingPortals>
        <add Name ="Main Publishing Portal" Value="[PublishingPortalInternalUrl]" />
        <!-- specify the list of additional publishing portals -->
        <add Name ="French Publishing Portal" Value="<http://ServerName:60002/sites/RetailPublishingPortal>" />
        </PublishingPortals>

5.  Save your changes.

6.  In SharePoint Central Administration, click **Activate** to reactivate Retail Publishing Job 1.

7.  After the publishing job completes, view the French publishing portal in a web browser and verify that the navigational hierarchy matches the translated hierarchy you configured in the previous procedure.

8.  View the English publishing portal and verify that its navigation hierarchy is still displayed in English. By default, the English portal URL could be http://*ServerName*:40002/sites/RetailPublishingPortal or http://*ServerName*:50002/sites/RetailPublishingPortal.

9.  In the English publishing portal, click **Product information management** \> **Released Products**.

10. In the search textbox type SP10101 and then click the \[Enter\] button. You should see just one item displayed and selected.

11. Click **Translations** and then select **French** from the **Language** drop-down list.

12. Provide French translations for the Description and Product name then click **Close**.

13. Edit the catalog, validate it, submit for approval, approve, publish, and then execute job 1150. For more information about approving and publishing a catalog, see [Key tasks: Create retail product catalogs](key-tasks-create-retail-product-catalogs.md).

14. 

29\. Wait until catalog is published and crawler finished its workNow we need to verify that the listing with French translation is available in French Publishing Portal30. By using Windows Auth Url navigate to the French Publishing Portal's product gallery31. Edit product gallery's CBS by editing its query by adding the line below into the text box "Ajouter des filtres supplémentaires"ProductCatalogLanguageTagOWSCHCS:frSave the page.32. In similar way as for \#8 - edit the CBS on Product Details page by editing value in the same combobox, there you need to replace ProductCatalogGroupNumberOWSTEXT:{UrlToken.2} ProductCatalogLanguageTagOWSCHCS:{CurrentDisplayLanguage}withProductCatalogGroupNumberOWSTEXT:{UrlToken.2} ProductCatalogLanguageTagOWSCHCS:fr　33. Go to Product Gallery page and make sure that items contains the French translation you specified in AX.34. Repeat the step 10 but this time apply it against the Product Details page.

## See also

[Online Store](online-store.md)

  


