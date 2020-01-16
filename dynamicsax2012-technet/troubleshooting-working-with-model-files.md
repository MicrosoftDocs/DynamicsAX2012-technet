---
title: Troubleshooting working with model files
TOCTitle: Troubleshooting working with model files
ms:assetid: 89a694c2-1640-449b-b659-2337cf0ad14e
ms:mtpsurl: https://technet.microsoft.com/library/JJ152919(v=AX.60)
ms:contentKeyID: 47570509
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Troubleshooting working with model files 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

This topic describes common issues that you may encounter when you work with models. The error message for each issue is listed, and then the cause and resolution are described.

## The network path was not found

You can run commands that return values, but cannot run commands that create new values, such as AXUtil **create model** or **New-AXModel**.

### ![JJ152919.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ152919.collapse_all(en-us,AX.60).gif")Cause

The Remote Registry service is not started in your environment on the Microsoft SQL Server that is running the Microsoft Dynamics AX databases. Many model-related commands require the ability to write event logs to the server that is running the database, and cannot complete the action if the Remote Registry service is not running.

### ![JJ152919.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ152919.collapse_all(en-us,AX.60).gif")Resolution

Start the Remote Registry service on the server that is running the Microsoft Dynamics AX databases.

## Could not load file or assembly 'C:\\Microsoft Dynamics AX\\60\\ManagementUtilities\\ModelName.axmodel' or one of its dependencies. This assembly is built by a runtime newer than the currently loaded runtime and cannot be loaded.

### ![JJ152919.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ152919.collapse_all(en-us,AX.60).gif")Cause

The AXUtil utility and the Windows PowerShell cmdlets for Microsoft Dynamics AX are part of AXUtilLib.dll. This DLL was built by using the Microsoft .NET Framework version 2.0.

### ![JJ152919.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ152919.collapse_all(en-us,AX.60).gif")Resolution

In order to run AXUtil and the Windows PowerShell cmdlets in an environment with Windows PowerShell 3.0 or.NET 4.0, you can choose one of the following options.

  - If you need to use .NET Framework version 4 assemblies, we recommend that you set the .NET Framework \<startup\> element **useLegacyV2RuntimeActivationPolicy** attribute to true. This attribute enables the .NET Framework version 2.0 runtime activation policy for the chosen runtime. It binds legacy runtime activation techniques (such as the CorBindToRuntimeEx function) to the runtime chosen from the configuration file instead of capping them at CLR version 2.0. Thus, if CLR version 4 or later is chosen from the configuration file, mixed-mode assemblies created with earlier versions of the .NET Framework are loaded with the chosen CLR version.
    

    > [!NOTE]
    > <P>Setting this value prevents CLR version 1.1 or CLR version 2.0 from loading into the same process, effectively disabling the in-process side-by-side feature.</P>



  - Create configuration files that set the .NET 4.0 DLLs to be trusted. The configuration files must be placed in the same location as the DLLs that they affect.
    
      - AXUtil.exe.config
    
      - powershell.exe.config
    
      - powershell\_ise.exe.config
    
    Place the following content in each configuration file, and save it in the same location as the DLL.
    
        <?xml version="1.0" encoding="utf-8" ?> 
        <configuration> 
          <startup useLegacyV2RuntimeActivationPolicy="true"> 
            <supportedRuntime version="v4.0.30319" /> 
        <supportedRuntime version="v3.5" /> 
        <supportedRuntime version="v2.0.50727"/>
          </startup> 
        </configuration>

  - Continue to run Windows PowerShell for **MSDAX** as a Windows PowerShell 2.0 application, by running it from the **MSDAX6**Management Shell (**Start** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Management Shell**).

For more information, see [.NET Framework 4.0 \<startup\> Element](http://msdn.microsoft.com/en-us/library/bbx34a2h\(vs.100\).aspx).

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

