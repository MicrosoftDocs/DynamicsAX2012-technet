---
title: Deploy the client by using Microsoft System Center 2012 Configuration Manager
TOCTitle: Deploy the client by using Microsoft System Center 2012 Configuration Manager
ms:assetid: 9527b874-0f9d-46cf-acef-3d8b02d659fa
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ841390(v=AX.60)
ms:contentKeyID: 50408939
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deploy the client by using Microsoft System Center 2012 Configuration Manager [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft System Center 2012 Configuration Manager is a comprehensive solution that is used to assess, deploy, and update servers, clients, and devices across physical, virtual, distributed, and mobile environments. This topic describes how to use Configuration Manager to deploy Microsoft Dynamics AX clients in a medium to large organization.

This topic does not provide information about how to set up the network infrastructure, such as the Active Directory directory service, Microsoft SQL Server, or Configuration Manager.

For more information about how to set up and use Configuration Manager, see the [Documentation Library for System Center 2012 Configuration Manager](http://technet.microsoft.com/en-us/library/gg682041.aspx) on TechNet.

## Overview of the deployment process

To deploy Microsoft Dynamics AX clients by using Configuration Manager, you must create and define the following objects:

  - **Collections** – A collection is a group of resources, such as users, user groups, or computers. A collection defines the target of a software deployment.
    
    For more information about collections, see [Collections in Configuration Manager](http://go.microsoft.com/fwlink/?linkid=272071) on TechNet.

  - **Packages** – A package is the set of installation source files that Configuration Manager manages and distributes for a software deployment. Packages include distribution points and the programs that are used to deploy the software.
    
    For more information about packages, see [Packages and Programs in Configuration Manager](http://go.microsoft.com/fwlink/?linkid=272072) on TechNet.

  - **Distribution points** – Distribution points are site systems for Configuration Manager that store packages that can be deployed to Configuration Manager clients. When the client receives a deployment, the client contacts a distribution point to download the package and start the installation process.
    
    For more information about distribution points, see [Introduction to Content Management in Configuration Manager](http://go.microsoft.com/fwlink/?linkid=272073) on TechNet.

## Create a collection

This section explains how to use direct membership rules to create a collection in System Center 2012 Configuration Manager. For more information about membership rules, see [Collections in Configuration Manager](http://go.microsoft.com/fwlink/?linkid=272071) on TechNet.

1.  In the Configuration Manager console, click **Assets and Compliance**.

2.  In the **Assets and Compliance** workspace, click **Device Collections**.

3.  On the **Home** tab, in the **Create** group, click **Create Device Collections**.

4.  On the **General** page of the New Collection Wizard, enter a name and description for the collection. In the **Limiting collection** field, select **All systems**.

5.  On the **Membership Rules** page, in the **Add Rule** list, click **Direct rule**.

6.  On the **Search for Resources** page of the Create Direct Membership Rule Wizard, specify the following information:
    
      - **Resource class** – In the list, select the type of resource to search for and add to the collection. Select **System Resource** to search for inventory data that is returned from client computers. Select **Unknown Computer** to select among values that are returned by unknown computers.
    
      - **Attribute name** – In the list, among the attributes that are associated with the selected resource class, select the attribute to search for. For example, if you want to select computers by their NetBIOS name, select **System Resource** in the **Resource class** list and **NetBIOS name** in the **Attribute name** list.
    
      - **Exclude resources marked as obsolete** – If a client computer is marked as obsolete, do not include this value in the search results.
    
      - **Exclude resources that do not have the Configuration Manager client installed** – If the search results include a resource for which a Configuration Manager client is not installed, do not include this value in the search results.
    
      - **Value** – Enter a value for which to search the selected attribute name. You can use the percent sign (%) as a wildcard character. For example, if you want to search for computers that have a NetBIOS name that starts with ‘M’, enter **M%** in this field.

7.  On the **Select Resources** page of the Create Direct Membership Rule Wizard, in the **Resources** list, select the resources to add to the collection, and then click **Next**.

8.  Complete the Create Direct Membership Rule Wizard.

## Prepare the source directory for the package

The source directory for a package contains all the files and subdirectories that are required to run the programs in the package. For Microsoft Dynamics AX, the source directory must contain a copy of the installation media for Microsoft Dynamics AX.

## Create a command file for installation parameters

Before you create a package to install the Microsoft Dynamics AX client and its prerequisites, you must create a command (.cmd) file that contains the command-line parameters that are used to install the software.

To install client components, use parameters for the Microsoft Dynamics AX Setup program. For information about individual parameters, see [Setup parameters reference](http://go.microsoft.com/fwlink/?linkid=191476) on TechNet. Setup can also configure some required prerequisites, such as operating system features and roles. Additionally, Setup can configure redistributable components that are on the installation media for Microsoft Dynamics AX. If you want Setup to automatically configure these prerequisites, include the parameter *ConfigurePrerequisites=1*.

You can silently install other prerequisites by running the individual programs from the command line. You must create a separate program for each prerequisite. To determine the command-line parameters that are required, we recommend that you run the Microsoft Dynamics AX prerequisite verification utility on a representative client. When you use the utility to configure prerequisites, the log file indicates the commands that were used.

For more information about how to find the appropriate command-line parameters for a silent installation, see [Run Setup in silent mode](run-setup-in-silent-mode.md).

When you have determined which parameters to use, create a parameter file in a text editor, such as Notepad. For example, create a text file that contains the following command:

setup.exe RunMode=Custom HideUI=1 AcceptLicenseTerms=1 ByPasswarnings=0 InstallClientUI=1 ClientAOSServer=Ax62-AOS01 AOSPort=2712 AOSWsdlPort=8101 ClientLanguage=en-us ConfigurePrerequisites=1 LogDir="c:\\Temp"

Save the file so that it has the .cmd file name extension.

## Create a package for the Microsoft Dynamics AX client

This section explains how to create the package that is used to install the Microsoft Dynamics AX client. For more information about how to create packages, see [How to Create Packages and Programs in Configuration Manager](http://technet.microsoft.com/en-us/library/gg682112.aspx) on TechNet.

1.  In the Configuration Manager console, click **Software Library**.

2.  In the **Software Library** workspace, expand **Application Management**, and then click **Packages**.

3.  On the **Home** tab, in the **Create** group, click **Create Package**.

4.  On the **Package** page of the Create Package and Program Wizard, specify the following information:
    
      - **Name** – Specify a name for the package. For example, enter **Microsoft Dynamics AX 2012**.
    
      - **Description** – Optional: Enter a description for the package.
    
      - **Manufacturer** – Optional: Specify a manufacturer name to help you identify the package in the Configuration Manager console. For example, enter **Microsoft**.
    
      - **Language** – Optional: Specify the language version of the package. For example, enter **U.S. English**.
    
      - **Version** – Optional: Specify the version number for the package. For example, enter **R2**.
    
      - **This package contains source files** – Select this option to use distribution points.
    
      - **Source folder** – Click **Browse** to open the **Set Source Folder** dialog box, and then specify the location of the source files for the package.

5.  On the **Program Type** page of the Create Package and Program Wizard, select **Standard Program**, and then click **Next**.

6.  On the **Standard Program** page of the Create Package and Program Wizard, enter a name for the program. In the **Command Line** field, browse to the location of the .cmd file that you created. Optionally, specify a startup folder for the program. For all other options on the **Standard Program** page, accept the default values.
    
    Click **Next**.

7.  On the **Requirements** page of the Create Package and Program Wizard, specify your requirements, or accept the default values. Click **Next**.

8.  On the **Summary** page of the wizard, review the actions that will be taken, and then complete the wizard. The new package and program are displayed in the **Packages** node of the **Software Library** workspace.

## Deploy the package for the Microsoft Dynamics AX client

Next, you must deploy the package that contains both the distribution point and the programs that are used to deploy the Microsoft Dynamics AX client and its prerequisites.

For more information about how to deploy packages, see [How to Deploy Packages and Programs in Configuration Manager](http://technet.microsoft.com/en-us/library/gg682178.aspx) on TechNet.

1.  In the Configuration Manager console, click **Software Library**.

2.  In the **Software Library** workspace, expand **Application Management**, and then click **Packages**.

3.  Select the package to deploy, and then, on the **Home** tab, in the **Deployment** group, click **Deploy**.

4.  On the **General** page of the Deploy Software Wizard, specify the name of the package and program to deploy, the collection to deploy the package and program to, and optional comments for the deployment.

5.  On the **Content** page of the wizard, click **Add**. Select the distribution points to which to deploy the content that is associated with the package and program.

6.  On the **Deployment Settings** page of the wizard, accept the default values.

7.  On the **Scheduling** page of the wizard, specify when this package and program are deployed or made available to client computers.

8.  On the **User Experience** page of the wizard, select the options that are appropriate to your implementation.

9.  On the **Distribution Points** page of the wizard, under **Deployment options**, select **Download content from distribution point and run locally**.

10. On the **Summary** page of the wizard, review the actions that will be taken, and then complete the wizard.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

