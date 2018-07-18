---
title: Install the Microsoft Dynamics AX databases
TOCTitle: Install the Microsoft Dynamics AX databases
ms:assetid: bccedbf4-d5fe-4f2b-9767-31bb82c4f037
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Ee355075(v=AX.60)
ms:contentKeyID: 35132842
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Install the Microsoft Dynamics AX databases 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to install the Microsoft Dynamics AX databases and model files.

There are three database components: the Microsoft Dynamics AX transaction database, the model store, and the baseline model store. The Application Object Server (AOS) connects to the Microsoft Dynamics AX database to process transactions. The AOS connects to the model store to display forms and reports. The baseline model store is used to upgrade X++ code to Microsoft Dynamics AX 2012, and to analyze application updates before they are applied.

In Microsoft Dynamics AX 2012 R3 and Microsoft Dynamics AX 2012 R2, the model store and the transaction data are stored in separate databases. In earlier versions of Microsoft Dynamics AX 2012, the model store and transaction data are stored in a single database.


> [!NOTE]
> <P>If you are upgrading databases between AX 2012, AX 2012 Feature Pack, AX 2012 R2, and AX 2012 R3, you should review <A href="scenario-perform-in-place-upgrade-to-ax-2012-r2-or-ax-2012-r3.md">Scenario: Perform in-place upgrade to AX 2012 R2 or AX 2012 R3</A>.</P>



Model files contain metadata information about application objects and are stored in the model store. For more information about model files, see [Models, Layers, and the Model Store](models-layers-and-the-model-store.md).


> [!WARNING]
> <P>If you plan to enable database mirroring in Microsoft SQL Server, you must enable it after you install the Microsoft Dynamics AX database and AOS. If you enable database mirroring before you install Microsoft Dynamics AX components, warnings are generated when the AOS is installed.</P>



## Before you install the Microsoft Dynamics AX databases

Verify that the following steps are completed before you install the Microsoft Dynamics AX databases.

  - Configure SQL Server. For more information, see [Configure SQL Server and storage settings](configure-sql-server-and-storage-settings.md).

  - On the computer where you plan to install the databases, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

  - Make sure that you have the required permissions to install the database. For more information, see [Verify that you have the required permissions for installation](verify-that-you-have-the-required-permissions-for-installation.md).

  - Make sure that the appropriate firewall ports are open. For more information, see [Firewall settings for Microsoft Dynamics AX components](firewall-settings-for-microsoft-dynamics-ax-components.md).

## Default models

The default models that are available in Setup vary based on the release of Microsoft Dynamics AX 2012 that you are installing.

## Default models in AX 2012 R3 and Microsoft Dynamics AX 2012 R2

If you are installing AX 2012 R3 or AX 2012 R2, the following models are available in Setup by default.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Model</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Foundation</p></td>
<td><p>The base Microsoft Dynamics AX model, which contains the application framework, the core application, extensions for industries, and localizations for countries/regions. This model is required.</p></td>
</tr>
<tr class="even">
<td><p>Foundation Upgrade</p></td>
<td><p>The model that is used to upgrade from Microsoft Dynamics AX 2009 or Microsoft Dynamics AX 4.0.</p></td>
</tr>
<tr class="odd">
<td><p>Foundation Labels</p></td>
<td><p>Application labels for the foundation model. This model includes labels for the following languages:</p>
<ul>
<li><p>Arabic (Saudi Arabia)</p></li>
<li><p>Chinese (China)</p></li>
<li><p>Czech (Czech Republic)</p></li>
<li><p>Danish (Denmark)</p></li>
<li><p>Dutch (Belgium and The Netherlands)</p></li>
<li><p>English (Australia, Canada, India, Ireland, Malaysia, New Zealand, Singapore, South Africa, United Kingdom, and United States)</p></li>
<li><p>Estonian (Estonia)</p></li>
<li><p>Finnish (Finland)</p></li>
<li><p>French (Belgium, Canada, France, and Switzerland)</p></li>
<li><p>German (Austria, Germany, and Switzerland)</p></li>
<li><p>Hungarian (Hungary)</p></li>
<li><p>Icelandic (Iceland)</p></li>
<li><p>Italian (Italy and Switzerland)</p></li>
<li><p>Japanese (Japan)</p></li>
<li><p>Latvian (Latvia)</p></li>
<li><p>Lithuanian (Lithuania)</p></li>
<li><p>Norwegian Bokmal (Norway)</p></li>
<li><p>Polish (Poland)</p></li>
<li><p>Portuguese (Brazil)</p></li>
<li><p>Russian (Russia)</p></li>
<li><p>Spanish (Mexico and Spain)</p></li>
<li><p>Swedish (Sweden)</p></li>
<li><p>Thai (Thailand)</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Default models in Microsoft Dynamics AX 2012 Feature Pack

If you are installing AX 2012 Feature Pack, the following models are available in Setup by default.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Model</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Foundation</p></td>
<td><p>The base Microsoft Dynamics AX model, which contains the application framework and the application foundation. This model also contains functionality for the discrete manufacturing industry. This model is required.</p></td>
</tr>
<tr class="even">
<td><p>Update for Foundation</p></td>
<td><p>Cumulative update for the Foundation model. If you selected to install the Foundation model, this model is installed automatically.</p></td>
</tr>
<tr class="odd">
<td><p>Foundation Upgrade</p></td>
<td><p>The model that is used to upgrade from Microsoft Dynamics AX 2009 or Microsoft Dynamics AX 4.0.</p></td>
</tr>
<tr class="even">
<td><p>Update for Foundation Upgrade</p></td>
<td><p>Cumulative update for the Foundation Upgrade model. If you selected to install the Foundation Upgrade model, this model is installed automatically.</p></td>
</tr>
<tr class="odd">
<td><p>Foundation Labels</p></td>
<td><p>Application labels for the foundation model. This model includes labels for the following languages:</p>
<ul>
<li><p>Danish (Denmark)</p></li>
<li><p>Dutch (Belgium and The Netherlands)</p></li>
<li><p>English (Australia, Canada, India, Ireland, Malaysia, New Zealand, Singapore, South Africa, United Kingdom, and United States)</p></li>
<li><p>French (Belgium, Canada, France, and Switzerland)</p></li>
<li><p>German (Austria, Germany, and Switzerland)</p></li>
<li><p>Italian (Italy and Switzerland)</p></li>
<li><p>Spanish (Mexico and Spain)</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Foundation Labels II</p></td>
<td><p>Application labels for the foundation model. These labels are for languages that were released after Microsoft Dynamics AX 2012 was made generally available. This model includes labels for the following languages:</p>
<ul>
<li><p>Arabic (Saudi Arabia)</p></li>
<li><p>Finnish (Finland)</p></li>
<li><p>Icelandic (Iceland)</p></li>
<li><p>Norwegian Bokmal (Norway)</p></li>
<li><p>Swedish (Sweden)</p></li>
<li><p>Thai (Thailand)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>SYP labels</p></td>
<td><p>Cumulative update of labels that were added by software updates in the SYP layer.</p></td>
</tr>
<tr class="even">
<td><p>Extensions</p></td>
<td><p>Microsoft Dynamics AX extensions for the following industries:</p>
<ul>
<li><p>Process Manufacturing - Process manufacturing production and logistics for Microsoft Dynamics AX. Allows you to manage production, inventory, and costs in a process-controlled environment, such as in the food, chemical, and pharmaceutical industries.</p></li>
<li><p>Public Sector - Addresses the special controls, rules, and regulations of Public Sector organizations.</p></li>
<li><p>Project Management – Allows you to invoice customers for various billing scenarios, such as billing per unit of delivery and billing when a milestone is completed. You can also create customer and vendor retentions, and manage workers on projects.</p></li>
<li><p>Retail - Provides mid-market and large retailers a complete head office and point of sale (POS) solution.</p></li>
</ul>
<div class="alert">

> [!IMPORTANT]
> <P>This model is required when you install AX 2012 Feature Pack. If the model includes functionality that you do not plan to use, turn off the appropriate license codes and configuration keys. Do not uninstall this model to remove unwanted functionality. Uninstalling models that are released by Microsoft will put the system in an unsupported state. If you have uninstalled this model, you must reinstall it using the instructions found in <A href="how-to-export-and-import-a-model.md">How to: Export and Import a Model</A>.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Extensions Upgrade</p></td>
<td><p>The model that is used to upgrade Process Manufacturing, Public Sector, Project Management, or Retail from Microsoft Dynamics AX 2009 or Microsoft Dynamics AX 4.0.</p></td>
</tr>
</tbody>
</table>


## Default models in Microsoft Dynamics AX 2012

If you are installing the original release of Microsoft Dynamics AX 2012, the following models are available in Setup by default.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Model</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Foundation</p></td>
<td><p>The base Microsoft Dynamics AX model, which contains the application framework and the application foundation. This model also contains functionality for the discrete manufacturing industry. This model is required.</p></td>
</tr>
<tr class="even">
<td><p>Foundation Upgrade</p></td>
<td><p>The model that is used to upgrade from Microsoft Dynamics AX 2009 or Microsoft Dynamics AX 4.0.</p></td>
</tr>
<tr class="odd">
<td><p>Foundation Labels</p></td>
<td><p>Application labels for the foundation model. This model includes labels for the following languages:</p>
<ul>
<li><p>Danish (Denmark)</p></li>
<li><p>Dutch (Belgium and The Netherlands)</p></li>
<li><p>English (Australia, Canada, Ireland, Malaysia, New Zealand, Singapore, South Africa, United Kingdom, and United States)</p></li>
<li><p>French (Belgium, Canada, France, and Switzerland)</p></li>
<li><p>German (Austria, Germany, and Switzerland)</p></li>
<li><p>Italian (Italy and Switzerland)</p></li>
<li><p>Spanish (Mexico and Spain)</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Process Manufacturing</p></td>
<td><p>The model that contains features for Process manufacturing production and logistics for Microsoft Dynamics AX. You can use these features to manage production, inventory, and costs in a process-controlled environment, such as in the food, chemical, and pharmaceutical industries.</p></td>
</tr>
<tr class="odd">
<td><p>Process Manufacturing Upgrade</p></td>
<td><p>The model that is used to upgrade Process manufacturing production and logistics from Microsoft Dynamics AX 2009 or Microsoft Dynamics AX 4.0.</p></td>
</tr>
<tr class="even">
<td><p>Public Sector</p></td>
<td><p>The Public Sector model for Microsoft Dynamics AX. This model addresses the special controls, rules, and regulations of Public Sector organizations.</p></td>
</tr>
<tr class="odd">
<td><p>Project Management</p></td>
<td><p>The model that contains additional project-related features for Microsoft Dynamics AX. You can use these features to invoice customers for various billing scenarios, such as billing per unit of delivery and billing when a milestone is completed. You can also use these features to create customer and vendor retentions, and to manage workers on projects.</p></td>
</tr>
<tr class="even">
<td><p>Project Management Upgrade</p></td>
<td><p>The model that is used to upgrade Project Management from Microsoft Dynamics AX 2009 or Microsoft Dynamics AX 4.0.</p></td>
</tr>
</tbody>
</table>


## Include additional model files in the installation (optional)

When you install the databases, you must identify any additional model files that are required for your environment.

During installation, Setup displays models from the CD\\Models\\ folder and all its subfolders. To import additional layers or customizations, you can add other model files to this folder.

Follow these steps to include additional models in the installation:

1.  Browse to the directory where the files from the Microsoft Dynamics AX DVD are shared. For more information, see [Create a shared directory for installation](create-a-shared-directory-for-installation.md).

2.  Create a subfolder in the CD\\Models\\ folder. We recommend that you create different folders to store the models that are received from different sources. For example, create a folder for each independent software vendor (ISV) or each value-added reseller (VAR).

3.  Copy the additional .axmodel files to the folders that you created.
    

    > [!WARNING]
    > <P>Do not copy your model files to the Standard folder. The Standard folder must be used only for models that are mandatory, such as the Foundation model (Foundation.axmodel).</P>



## Install the Microsoft Dynamics AX databases

Use this procedure to install the Microsoft Dynamics AX databases and model files. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on the computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Enter a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, on the **Select an installation option** page, click **Microsoft Dynamics AX**, and then click **Next**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Databases**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Select databases** page, select whether you want to create new databases by using Setup, or whether you want to configure existing databases. If you are upgrading, you should select to configure existing databases.

9.  If you want Setup to create the databases, on the **Create new databases** page, in the **Server name** list, select the name of the computer that runs SQL Server. Provide database names or accept the default database names. By default, the transaction database is named MicrosoftDynamicsAX. The baseline database is optional. By default, the baseline database is named MicrosoftDynamicsAX\_baseline.
    
    If you created the databases manually, or if you are upgrading a database, on the **Configure existing databases** page, select the name of the computer that runs SQL Server, and then select the names of the existing databases that you want to configure.
    

    > [!IMPORTANT]
    > <P>The database name must not include any spaces or any of the following characters: backslashes (\), slashes (/), periods (.), commas (,), colons (:), brackets ([ ]), parentheses (( )), or hyphens (-). For more information about characters that are allowed by SQL Server, see the <A href="http://go.microsoft.com/fwlink/?linkid=214698">Identifiers</A> topic on MSDN.</P>

    
    Click **Next**.

10. On the **Select additional models** page, select models in the **Available Models** list. Setup lists all the models that are contained in the Models folder and its subfolders. Required models are selected by default, and you cannot clear the selection.
    
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
    <td><p>You may have models, or .axmodel files, that are not electronically signed. The Setup program cannot verify the publisher of an unsigned model file. If you import an unsigned model file into the model store, you create a security risk. Setup displays an error message if a selected model file does not have a digital signature. Before you decide whether you want to continue or cancel the installation, carefully review the models that you have selected.</p></td>
    </tr>
    </tbody>
    </table>
    
    If you install models other than the Foundation models, you must complete the **Compile application** task when you run the initialization checklist. If you do not complete the **Compile application** task, you encounter errors when you run the **Synchronize database** task in the initialization checklist. For more information about the initialization checklist, see [Initialize Microsoft Dynamics AX](initialize-microsoft-dynamics-ax.md).
    
    Click **Next** to continue.

11. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

12. On the **Ready to install** page, click **Install**.

13. After the installation is completed, click **Finish** to close the wizard.

## Create a Microsoft Dynamics AX database manually

If you want to create databases manually for Microsoft Dynamics AX, you must first create databases using Setup as a template.

1.  Follow the procedure above to create business and model store databases using Setup.

2.  Manually create a second business database using SQL Server Management Studio.

3.  Copy all objects, users, and user permissions from the template database to the new database.

4.  Manually create a second model database using SQL Server Management Studio. It must have the same name as the new business database that you created in step 2, with \_model at the end of the name.

5.  Copy all objects, users, and user permissions from the template database to the new database.

6.  Configure an AOS instance to connect to the new business database. Installing an AOS instance sets the appropriate rights for the AOS service account on the selected database server and creates stored procedures used for session management.

7.  If you want an existing AOS instance to connect to the manually created database, you must set the appropriate rights for the AOS account. Set the following permissions in the database:
    
    1.  Make the account a login on the database server. (This login already exists if you are installing on the same SQL Server computer as the first database.)
    
    2.  Assign the user to the db\_ddladmin, db\_datareader, and db\_datawriter database roles.
    
    3.  Grant the user execute rights on the createserversessions and createusersessions stored procedures.

  


