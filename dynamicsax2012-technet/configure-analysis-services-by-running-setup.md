---
title: Configure Analysis Services by running Setup
TOCTitle: Configure Analysis Services by running Setup
ms:assetid: 300442b3-886e-450f-8f79-6285a26fb459
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg751377(v=AX.60)
ms:contentKeyID: 35132594
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Configure Analysis Services by running Setup 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to configure Microsoft SQL Server Analysis Services for use with Microsoft Dynamics AX. You must complete this procedure on the computer that is running Analysis Services.

This procedure assumes that you are configuring Analysis Services on a dedicated server where no Microsoft Dynamics AX components are installed. If you are installing other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the initial wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, select **Custom installation**. Click **Next**.

6.  On the **Select components** page, follow these steps:
    
    1.  Select the **Analysis Services configuration** check box.
    
    2.  A message is displayed that states that you must complete the code upgrade checklist if you are upgrading. Click **OK**.
    
    3.  We recommend that you select the **Management utilities** check box so that you can deploy cubes by using Windows PowerShell commands.
    
    4.  Click **Next**.

7.  On the **Prerequisite Validation** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Select a file location** page, select the location in which to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Specify a location for configuration settings** page, specify whether you want the cubes to access configuration information from the registry on the local computer or from a shared configuration file. If you select to use a shared configuration file, you must enter the network location of the file. Click **Next**.

10. On the **Connect to an AOS instance** page, enter the name of the computer that is running the Application Object Server (AOS) instance that you want to connect to. You can optionally specify the name of the AOS instance, the TCP/IP port number, and the WSDL port for services. Click **Next**.
    

    > [!NOTE]
    > <P>If you entered AOS connection information for other Microsoft Dynamics AX components that are installed on this computer, this page is not displayed. Subsequent installations on this computer reuse the existing AOS connection.</P>



11. On the **Specify Business Connector proxy account information** page, enter the password for the proxy account that is used by Business Connector. Click **Next**.

12. On the **Specify an Analysis Services instance** page, select an instance of Analysis Services. Click **Next**.

13. On the **Connect to a SQL Server Database** page, follow these steps:
    
    1.  Select the computer that hosts your Microsoft Dynamics AX online transaction processing (OLTP) database.
    
    2.  Select the Microsoft Dynamics AX OLTP database.
    
    3.  Click **Next**.

14. The domain account that the Analysis Services service runs as must have access to the Microsoft Dynamics AX OLTP database in order to process the cubes. The **Specify user accounts** page lists the accounts that currently have access to the OLTP database. If the account that the Analysis Services service runs as is not listed, click **Add user** to add it.
    
    Click **Next**.

15. On the **Prerequisite Validation** page, resolve any errors. When no errors remain, click **Next**.

16. On the **Ready to install** page, click **Install**.

17. Click **Finish** to close the Setup wizard.

18. The **Microsoft Dynamics AX 2012 Setup Summary Report** is displayed. This report lists additional procedures that you must complete to integrate Microsoft Dynamics AX and Analysis Services. For more information about the procedures, see [Complete the Analysis Services integration](complete-the-analysis-services-integration.md).

  


