---
title: Deploy the client by using Microsoft System Center Configuration Manager 2007
TOCTitle: Deploy the client by using Microsoft System Center Configuration Manager 2007
ms:assetid: d071ca02-2f1d-4de0-bd65-35e8cb7a7295
ms:mtpsurl: https://technet.microsoft.com/library/Hh378077(v=AX.60)
ms:contentKeyID: 36870660
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Deploy the client by using Microsoft System Center Configuration Manager 2007 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft System Center Configuration Manager 2007 is a comprehensive solution that is used to assess, deploy, and update servers, clients, and devices across physical, virtual, distributed, and mobile environments. This topic describes how to use Configuration Manager to deploy Microsoft Dynamics AX clients in a medium to large organization.

This topic does not provide information about how to set up the network infrastructure, such as the Active Directory directory service, Microsoft SQL Server, and System Center Configuration Manager.

For more information about how to set up and use Configuration Manager, see the [Configuration Manager 2007 Documentation Library](https://technet.microsoft.com/library/bb680651.aspx) on TechNet.

## Overview of the deployment process

To deploy Microsoft Dynamics AX clients by using Configuration Manager, you must create and define the following objects:

  - **Collections** – A collection is a group of resources, such as users, user groups, or computers. A collection defines the target of a software deployment.
    
    For more information about collections, see [Collections Overview](https://go.microsoft.com/fwlink/?linkid=145870) in the Configuration Manager documentation.

  - **Packages** – A package is the set of installation source files that Configuration Manager manages and distributes for a software deployment. Packages include distribution points and the programs that are used to deploy the software.
    
    For more information about packages, see [About Packages](https://go.microsoft.com/fwlink/?linkid=145871) in the Configuration Manager documentation.

  - **Programs** – Programs contain command-line switches and additional parameters that are used by designated source files in packages, such as Setup.exe.
    
    For more information about programs, see [About Programs](https://go.microsoft.com/fwlink/?linkid=145872) in the Configuration Manager documentation.

  - **Distribution points** – Distribution points are site systems for Configuration Manager that store packages that can be deployed to Configuration Manager clients. When the client receives and processes an advertisement, the client contacts a distribution point to download the package and start the installation process.
    
    For more information about distribution points, see [About Distribution Points](https://go.microsoft.com/fwlink/?linkid=145873) in the Configuration Manager documentation.

  - **Advertisements** – Advertisements let administrators target a software deployment to collections of computers or users. An advertisement specifies a package, a program, and the collection to which the advertisement is sent and deployed.
    
    For more information about advertisements, see [About Advertisements](https://go.microsoft.com/fwlink/?linkid=145875) in the Configuration Manager documentation.

## Example: Deploy Microsoft Dynamics AX clients by using Configuration Manager

This section provides an example of a network environment for the Configuration Manager infrastructure. This section also describes how Configuration Manager is used to deploy Microsoft Dynamics AX clients in this environment.

You can use this example as a guide when you use Configuration Manager to deploy Microsoft Dynamics AX clients in your implementation.

## Network environment

The following illustration shows an example of a network environment.

![Example network diagram](images/Hh378077.MassdeploymentwithSCCM(AX.60).gif "Example network diagram")

All the computers are members of the Contoso.com domain.

Servers A, B, and C run Windows Server 2008. The applications and roles on each computer are as follows:

  - **A** – The domain controller that runs Active Directory, the Domain Name System (DNS) Server role, and the Dynamic Host Configuration Protocol (DHCP) Server role

  - **B** – The database server that runs Microsoft SQL Server 2008

  - **C** – The management point and distribution point that runs System Center Configuration Manager

  - **D** – The client computer that runs Windows 7 Professional and the System Center Configuration Manager client


> [!NOTE]
> <P>In the network environment in this example, server C performs multiple roles in the site system. However, we do not recommend this configuration in production environments that have many resources.</P>



## Create a collection

This section explains how to use direct membership rules to create a collection in System Center Configuration Manager 2007. For more information about membership rules, see [About Membership Rules](https://go.microsoft.com/fwlink/?linkid=145884) in the Configuration Manager documentation.

1.  In the Configuration Manager Console, click **System Center Configuration Manager** \> **Site Database** \> **Computer Management** \> **Collections**.

2.  Right-click **Collections**, and then click **New Collection**. On the **General** page of the New Collection Wizard, enter a name for the collection.

3.  On the **Membership Rules** page, click the computer icon to open the Create Direct Membership Rule Wizard. Click **Next**.

4.  On the **Search for Resources** page, in the **Resource class** field, select **System Resource**. Then, in the **Attribute name** field, select **Name**. In the **Value** field, enter **%**, and then click **Next**.

5.  On the **Collection Limiting** page, click **Browse**, select **All Windows Workstation or Professional Systems**, click **OK**, and then click **Next**.

6.  On the **Select Resources** page, select the check box for each computer resource that you want to target. Click **Next**.

7.  On the **Finished** page, click **Finish**.

8.  On the **Membership Rules** page of the New Collection Wizard, click **Next**.

9.  On the **Advertisements** page, you cannot assign an advertisement, because you have not yet created an advertisement. Click **Next**.

10. On the **Security** page, accept the default values, click **Next**, and then click **Close**.

## Prepare the source directory for the package

The source directory for a package contains all the files and subdirectories that are required to run the programs in a package. For Microsoft Dynamics AX, the source directory must contain a copy of the installation media for Microsoft Dynamics AX.

For more information about source directories for packages, see [How to Set Up a Package Source Directory](https://go.microsoft.com/fwlink/?linkid=145890) in the Configuration Manager documentation.

## Create a package for Microsoft Dynamics AX

This section explains how to create a package that contains the parameters that are used to install the Microsoft Dynamics AX client.

In this example, the Microsoft Dynamics AX client and its prerequisites are contained in one package that has multiple programs. You can also deploy the programs in separate packages.

The location from which the package is distributed is known as the distribution point.

1.  In the Configuration Manager Console, click **System Center Configuration Manager** \> **Site Database** \> **Computer Management** \> **Software Distribution** \> **Packages**.

2.  Right-click **Packages**, point to **New**, and then click **Package**.

3.  On the **General** page of the New Package Wizard, enter the name, version, manufacturer, and language. For example, enter **Microsoft Dynamics AX 2012 EN**. Click **OK**, and then click **Next**.

4.  Click **Next** on all the remaining pages of the wizard to accept the default settings. On the **Wizard Completed** page, click **Close**.

## Determine which parameters are used for a silent installation

Before you create programs that are used to install the Microsoft Dynamics AX client and its prerequisites, you must determine which command-line parameters are required to silently install the software. A silent installation is an installation that does not require user interaction.

To install client components, use parameters for the Microsoft Dynamics AX Setup program. For information about individual parameters, see the [Setup parameters reference](https://go.microsoft.com/fwlink/?linkid=191476) on TechNet. Setup can also configure some required prerequisites, such as operating system features and roles, and redistributable components that are on the installation media for Microsoft Dynamics AX. If you want Setup to automatically configure these prerequisites, include the parameter *ConfigurePrerequisites=1* when you create the program that installs the client.

You can silently install other prerequisites by running the individual programs from the command line. You must create a separate program for each of these prerequisites. To determine the command-line parameters that are required, we recommend that you run the Microsoft Dynamics AX prerequisite verification utility on a representative client. When you use the utility to configure prerequisites, the log file indicates the commands that were used.

For more information about how to find the appropriate command-line parameters for a silent installation, see [Run Setup in silent mode](run-setup-in-silent-mode.md).

## Create programs

Next, you must create the programs that are included in the package.

Create one program that contains the parameters that are used to silently install the Microsoft Dynamics AX client. In addition, create a separate program for every prerequisite of Microsoft Dynamics AX that cannot be configured automatically by the Microsoft Dynamics AX Setup program.

## Create a program to install the Microsoft Dynamics AX client

Use the following procedure to create a program that installs the Microsoft Dynamics AX client.

1.  In the Configuration Manager Console, right-click **Programs**, point to **New**, and then click **Program**.

2.  On the **General** page of the New Program Wizard, enter a name for the package in the **Name** field. In the **Command line** field, enter the Setup parameters that you want to use. For example, type the following command.
    
    setup.exe RunMode=Custom HideUI=1 AcceptLicenseTerms=1 ByPasswarnings=0 InstallClientUI=1 ClientAOSServer=Ax62-AOS01 AOSPort=2712 AOSWsdlPort=8101 ClientLanguage=en-us ConfigurePrerequisites=1 LogDir="c:\\Temp"
    

    > [!IMPORTANT]
    > <P>If you want Setup to automatically configure the prerequisites that it can configure, specify the parameter <EM>ConfigurePrerequisites=1</EM>.</P>

    
    If you do not want the Microsoft Dynamics AX Configuration utility to be installed when clients are installed, specify the parameter *ClientConfig=0*. To set up clients so that they use a shared configuration file, set the *ClientConfigFile* parameter to the path of the configuration file in the shared directory. For example, specify the parameter as follows.
    
    ClientConfigFile="X:\\\<name of configuration file\>.axc"
    
    For more information about whether to install the Configuration Utility, and about using shared configuration files, see [About the Microsoft Dynamics AX 2012 Configuration utility](about-the-microsoft-dynamics-ax-2012-configuration-utility.md).

3.  In the **Run** field, select **Hidden**. In the **After running** field, verify that **No action required** is selected. Click **Next**, and then accept the default values on the **Requirements** page.

4.  On the **Environment** page, in the **Program can run** field, select **Whether or not a user is logged on**. The **Run mode** field is automatically set to **Run with administrative rights**. Make sure that the **Drive mode** field is set to **Runs with UNC name**, and then click **Next**.

5.  On the **Advanced** page, select **Suppress program notifications**, and then click **Next**.
    

    > [!NOTE]
    > <P>If you want a notification about the installation to be displayed on each user's desktop, clear <STRONG>Suppress program notifications</STRONG>.</P>



6.  On the **Summary** page, click **Next**. The **Wizard Completed** page is displayed.

7.  To exit the New Program Wizard, click **Close**.

## Create programs to install prerequisites

You must create a program for every prerequisite that cannot be configured automatically by the Microsoft Dynamics AX Setup program. The following example shows how to create a program that installs Report Viewer 2012.

1.  In the Configuration Manager Console, right-click **Programs**, point to **New**, and then click **Program**.

2.  On the **General** page of the New Program Wizard, enter a name for the package in the **Name** field. For example, enter **Report viewer 2012 installation**. In the **Command line** field, type the command that is used to install the prerequisite. For Report Viewer 2012, type the following command.
    
    Redist\\ReportViewer2010\\ReportViewer /passive

3.  In the **Run** field, select **Hidden**. In the **After running** field, verify that **No action required** is selected. Click **Next**, and then accept the default values on the **Requirements** page.

4.  On the **Environment** page, in the **Program can run** field, select **Whether or not a user is logged on**. The **Run mode** field is automatically set to **Run with administrative rights**. Make sure that the **Drive mode** field is set to **Runs with UNC name**, and then click **Next**.

5.  On the **Advanced** page, select **Suppress program notifications**, and then click **Next**.
    

    > [!NOTE]
    > <P>If you want a notification about the installation to be displayed on each user's desktop, clear <STRONG>Suppress program notifications</STRONG>.</P>



6.  On the **Summary** page, click **Next**. The **Wizard Completed** page is displayed.

7.  To exit the New Program Wizard, click **Close**.

## Select a distribution point

To use a server as a distribution point that distributes packages to client computers, you must first designate a site system as a distribution point. In this example, the site server that is named SCCM is configured as both a management point and a distribution point.

1.  In the Configuration Manager Console, right-click **Distribution Points**, click **New Distribution Points**, click **Next**, and then select the check box for the distribution point. In this example, the new distribution point is server C. Click **Next**.

2.  When you have finished running the New Distribution Points Wizard, click **Close**.

Before you advertise the package, we recommend that you verify that the package is stored on the distribution point. For more information about how to verify the status of a package, see [How to View the Status of a Package](https://go.microsoft.com/fwlink/?linkid=145898) in the Configuration Manager documentation.

## Create an advertisement for the Microsoft Dynamics AX client package

Next, you must advertise the package that contains both the Configuration Manager distribution point and the programs that are used to deploy the Microsoft Dynamics AX client and its prerequisites. This example shows how to create an advertisement of the Microsoft Dynamics AX client package.

1.  In the Configuration Manager Console, right-click **Advertisements**, point to **New**, and then click **Advertisement**.

2.  On the **General** page of the New Advertisement Wizard, enter a name in the **Name** field. Click the **Browse** button for the **Package** field, and then click the package that you want to advertise. Click **OK**. Click the **Browse** button for the **Collection** field, click the collection, click **OK**, and then click **Next**.

3.  On the **Schedule** page, in the **Advertisement start time** fields, enter the date and time when the advertisement becomes available, and then click the asterisk (\*) button for **Mandatory Assignments**.

4.  On the **Assignment Schedule** page, click **Schedule**, and then enter the same date and time that you entered in the **Advertisement start time** fields on the **Schedule** page. Click **OK**.

5.  On the **Schedule** page, select the check boxes for **Enable Wake On LAN**, **Ignore maintenance windows when running program**, and **Allow system restart outside maintenance windows**, and then click **Next**.
    

    > [!NOTE]
    > <P>In your production environment, policies may require that you select different values for the assignment schedule than the values that are shown in this example. For more information about these options, see <A href="https://go.microsoft.com/fwlink/?linkid=145900">Advertisement Name Properties: Schedule Tab</A> in the SCCM documentation.</P>



6.  Accept the default values on the remaining pages. On the **Wizard Completed** page, click **Close**.

The package is advertised to the targeted collection, and the silent installation of Microsoft Dynamics AX client starts.

For information about how to monitor the status of an advertisement, see [How to View the Status of an Advertisement](https://go.microsoft.com/fwlink/?linkid=145901) in the Configuration Manager documentation.

  


