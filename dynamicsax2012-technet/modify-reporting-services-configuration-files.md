---
title: Modify Reporting Services configuration files
TOCTitle: Modify Reporting Services configuration files
ms:assetid: 42ffe10a-7536-41e8-b8de-d45179b15fca
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh389762(v=AX.60)
ms:contentKeyID: 36899741
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Modify Reporting Services configuration files [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Complete the following procedures to modify the configuration files that are used by the new instance of Microsoft SQL Server Reporting Services.


> [!TIP]
> <P>We recommend that you make a backup of each configuration file before you modify it.</P>



## Modify the Report Manager Web.config file

Complete the following procedure to modify the Web.config file that is used by Report Manager.

1.  Open the Web.config file.
    
      - If you are using SQL Server 2008, the default location of this file is: \\Program Files\\Microsoft SQL Server\\MSRS10.\[SSRSInstanceName\]\\Reporting Services\\ReportManager.
    
      - If you are using SQL Server 2008 R2, the default location of this file is: \\Program Files\\Microsoft SQL Server\\MSRS10\_50.\[SSRSInstanceName\]\\Reporting Services\\ReportManager.
    
      - If you are using SQL Server 2012, the default location of this file is: \\Program Files\\Microsoft SQL Server\\MSRS11.\[SSRSInstanceName\]\\Reporting Services\\ReportManager.
    
      - If you are using SQL Server 2014, the default location of this file is: \\Program Files\\Microsoft SQL Server\\MSRS12.\[SSRSInstanceName\]\\Reporting Services\\ReportManager.

2.  Search for **httpRuntime**.

3.  Add **maxRequestLength="100000"** to the line of code so that the line looks like this:
    
        <httpRuntime maxRequestLength="100000" executionTimeout="90000" />

## Modify the report server RsReportServer.config file

Complete the following procedure to modify the RsReportServer.config file.

1.  Open the RsReportServer.config file.
    
      - If you are using SQL Server 2008, the default location of this file is: \\Program Files\\Microsoft SQL Server\\MSRS10.\[SSRSInstanceName\]\\Reporting Services\\ReportServer.
    
      - If you are using SQL Server 2008 R2, the default location of this file is: \\Program Files\\Microsoft SQL Server\\MSRS10\_50.\[SSRSInstanceName\]\\Reporting Services\\ReportServer.
    
      - If you are using SQL Server 2012, the default location of this file is: \\Program Files\\Microsoft SQL Server\\MSRS11.\[SSRSInstanceName\]\\Reporting Services\\ReportServer.
    
      - If you are using SQL Server 2014, the default location of this file is: \\Program Files\\Microsoft SQL Server\\MSRS12.\[SSRSInstanceName\]\\Reporting Services\\ReportServer.

2.  Find the **\<AuthenticationTypes\>** element.

3.  In the **\<AuthenticationTypes\>** element, remove the following line of code if it is present:
    
        <RSWindowsNegotiate>

4.  Find the **\<Service\>** element.

5.  In the **\<Service\>** element, add the following line of code:
    
        <IsRdceEnabled>True</IsRdceEnabled>

6.  Find the **\<Data\>** element.

7.  In the **\<Data\>** element, add the following lines of code. If you are using Microsoft Dynamics AX 2012, use **6.0.0.0** as the version number. If you are using Microsoft Dynamics AX 2012 R2, use **6.2.0.0** as the version number. If you are using Microsoft Dynamics AX 2012 R3, use **6.3.0.0**.
    
        <Extension Name="AXQUERY" Type="Microsoft.Dynamics.Framework.Reports.AxQueryConnection,Microsoft.Dynamics.Framework.ReportsExtensions, Version=6.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35"/>
        <Extension Name="AXDATAMETHOD" Type="Microsoft.Dynamics.Framework.Reports.AxDataMethodConnection,Microsoft.Dynamics.Framework.ReportsExtensions, Version=6.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35"/>
        <Extension Name="AXREPORTDATAPROVIDER" Type="Microsoft.Dynamics.Framework.Reports.AxReportProviderConnection,Microsoft.Dynamics.Framework.ReportsExtensions, Version=6.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35"/>
        <Extension Name="AXADOMD" Type="Microsoft.Dynamics.Framework.Reports.AxAdomdConnection,Microsoft.Dynamics.Framework.ReportsExtensions, Version=6.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35"/>
        <Extension Name="AXENUMDATAPROVIDER" Type="Microsoft.Dynamics.Framework.Reports.EnumProviderConnection,Microsoft.Dynamics.Framework.ReportsExtensions, Version=6.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35"/>

8.  Find the **\<Extensions\>** element.

9.  In the **\<Extensions\>** element, add the following lines of code. If you are using Microsoft Dynamics AX 2012, use **6.0.0.0** as the version number. If you are using Microsoft Dynamics AX 2012 R2, use **6.2.0.0** as the version number. If you are using Microsoft Dynamics AX 2012 R3, use **6.3.0.0**.
    
        <ReportDefinitionCustomization>
        <Extension Name="AXRDCE" Type="Microsoft.Dynamics.Framework.Reports.AxRdce.CustomizationExtension,Microsoft.Dynamics.Framework.ReportsExtensions, Version=6.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35"/>
        </ReportDefinitionCustomization>

## Modify the report server RsSrvPolicy.config file

Complete the following procedure to modify the RsSrvPolicy.config file.

1.  Open the RsSrvPolicy.config file.
    
      - If you are using SQL Server 2008, the default location of this file is: \\Program Files\\Microsoft SQL Server\\MSRS10.\[SSRSInstanceName\]\\Reporting Services\\ReportServer.
    
      - If you are using SQL Server 2008 R2, the default location of this file is: \\Program Files\\Microsoft SQL Server\\MSRS10\_50.\[SSRSInstanceName\]\\Reporting Services\\ReportServer.
    
      - If you are using SQL Server 2012, the default location of this file is: \\Program Files\\Microsoft SQL Server\\MSRS11.\[SSRSInstanceName\]\\Reporting Services\\ReportServer.
    
      - If you are using SQL Server 2014, the default location of this file is: \\Program Files\\Microsoft SQL Server\\MSRS12.\[SSRSInstanceName\]\\Reporting Services\\ReportServer.

2.  Find the **\<SecurityClasses\>** element.

3.  In the **\<SecurityClasses\>** element, add the following line of code. If you are using Microsoft Dynamics AX 2012, use **6.0.0.0** as the version number. If you are using Microsoft Dynamics AX 2012 R2, use **6.2.0.0** as the version number. If you are using Microsoft Dynamics AX 2012 R3, use **6.3.0.0**.
    
        <SecurityClass Name="AxSessionPermission" Description="Microsoft.Dynamics.Framework.Reports.AxSessionPermission, Microsoft.Dynamics.Framework.Reports, Version=6.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35" />

4.  Find the **\<NamedPermissionSets\>** element.

5.  In the **\<NamedPermissionSets\>** element, add the following lines of code:
    
    ``` 
              <PermissionSet class="NamedPermissionSet" version="1" Name="AxSessionPermissionSet">
                  <IPermission class="AxSessionPermission" version="1" Unrestricted="true" />
                  <IPermission class="SecurityPermission" version="1" Flags="Assertion" />
                </PermissionSet>
    ```

6.  Find the **\<CodeGroup class="FirstMatchCodeGroup" version="1" PermissionSetName="Execution" Description="This code group grants MyComputer code Execution permission. "\>** element.

7.  Directly after the **\<CodeGroup class="FirstMatchCodeGroup" version="1" PermissionSetName="Execution" Description="This code group grants MyComputer code Execution permission. "\>** element, you’ll find the **\<IMembershipCondition\>** element. Add the following lines of code after the **\<IMembershipCondition\>** element:
    
        <CodeGroup class="UnionCodeGroup" version="1" PermissionSetName="FullTrust" Name="AX_Reports_Strong_Name" Description="This code group grants Dynamics AX Reports code full trust. ">
                     <IMembershipCondition class="StrongNameMembershipCondition" version="1" PublicKeyBlob="0024000004800000940000000602000000240000525341310004000001000100B5FC90E7027F67871E773A8FDE8938C81DD402BA65B9201D60593E96C492651E889CC13F1415EBB53FAC1131AE0BD333C5EE6021672D9718EA31A8AEBD0DA0072F25D87DBA6FC90FFD598ED4DA35E44C398C454307E8E33B8426143DAEC9F596836F97C8F74750E5975C64E2189F45DEF46B2A2B1247ADC3652BF5C308055DA9" />
                  </CodeGroup>

## Modify the report server Web.config file

Complete the following procedure to modify the Web.config file that is used by the report server instance.

1.  Open the Web.config file.
    
      - If you are using SQL Server 2008, the default location of this file is: \\Program Files\\Microsoft SQL Server\\MSRS10.\[SSRSInstanceName\]\\Reporting Services\\ReportServer.
    
      - If you are using SQL Server 2008 R2, the default location of this file is: \\Program Files\\Microsoft SQL Server\\MSRS10\_50.\[SSRSInstanceName\]\\Reporting Services\\ReportServer.
    
      - If you are using SQL Server 2012, the default location of this file is: \\Program Files\\Microsoft SQL Server\\MSRS11.\[SSRSInstanceName\]\\Reporting Services\\ReportServer.
    
      - If you are using SQL Server 2014, the default location of this file is: \\Program Files\\Microsoft SQL Server\\MSRS12.\[SSRSInstanceName\]\\Reporting Services\\ReportServer.

2.  Find the **\<httpModules\>** element.

3.  In the **\<httpModules\>** element, add the following line of code. If you are using Microsoft Dynamics AX 2012, use **6.0.0.0** as the version number. If you are using Microsoft Dynamics AX 2012 R2, use **6.2.0.0** as the version number. If you are using Microsoft Dynamics AX 2012 R3, use **6.3.0.0**.
    
        <add name="AxReportsHttpModule" type="Microsoft.Dynamics.Framework.Reports.AxReportsHttpModule,Microsoft.Dynamics.Framework.ReportsExtensions, Version=6.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35" />

4.  Search for **httpRuntime**.

5.  Add **maxRequestLength="100000"** to the line of code so that the line looks like this:
    
        <httpRuntime maxRequestLength="100000" executionTimeout="90000" />

6.  Find the **\<system.web\>** element.

7.  In the **\<system.web\>** element, add the following line of code if it does not already exist:
    
        <hostingEnvironment shadowCopyBinAssemblies="true" />

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

