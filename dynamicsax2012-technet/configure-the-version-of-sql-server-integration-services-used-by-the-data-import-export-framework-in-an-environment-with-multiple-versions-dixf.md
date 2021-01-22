---
title: Specify the version of Integration Services that the Data Import/Export Framework uses
TOCTitle: Specify the version of Integration Services that the Data Import/Export Framework uses
ms:assetid: 42117635-a8e9-48a2-9ec7-175d30e8e07b
ms:mtpsurl: https://technet.microsoft.com/library/Dn878167(v=AX.60)
ms:contentKeyID: 63701236
author: Khairunj
ms.author: daxcpft
ms.date: 09/06/2018
mtps_version: v=AX.60
---

# Specify the version of Integration Services that the Data Import/Export Framework uses


_**Applies To:** Microsoft Dynamics AX 2012 R2_

This topic only applies to environments that are running Microsoft Dynamics AX 2012 R2 with [KB 3018235](https://mbs2.microsoft.com/Knowledgebase/KBDisplay.aspx?scid=kb;en-us;3018235) installed. KB 3018235 is required to use Data Import/Export Framework for AX 2012 R2 CU7 with SQL Server 2014 Integration Services. If you are in an environment in which two versions of Microsoft SQL Server Integration Services are installed on the same computer, by default, the Data Import/Export Framework Windows service will attach to the oldest version of Integration Services that it can find. SQL Server 2008 Integration Services is the oldest supported version. You can force the Data Import/Export Framework to use another version of Integration Services by using redirecting assembly versions. We strongly recommend that you use Data Import/Export Framework in an environment with only one version of SQL Server Integration Services installed. To see which versions of Integration Services are supported with the Data Import/Export Framework, see the [Microsoft Dynamics AX 2012 System Requirements](https://go.microsoft.com/fwlink/?LinkId=165377).

## Force the Data import/export framework to use a version of Integration Services other than the default
You can force the Data Import/Export Framework to use a version of Integration Services other than the default by [redirecting assembly versions](https://msdn.microsoft.com/library/7wd6ex19(v=vs.110).aspx).

| Caution:                                                                                                                                                                                                    |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| If the assembly version redirection is setup incorrectly, for example, by redirecting to a version of Integration Services that is not installed, the Data Import/Export Framework will not work correctly. |

1.  Locate the installation directory of the Data Import/Export Framework service component.
2.  Open the file **Microsoft.Dynamics.AX.DMF.SSISHelperService.exe.config** in a text editor.
3.  Locate the **&lt;runtime&gt;** element in the file. Inside this element, add the following code.
    -   Code to redirect to SQL Server 2012 Integration Services
            <assemblyBinding xmlns="urn:schemas-microsoft-com:asm.v1">
                  <dependentAssembly>
                    <assemblyIdentity name="Microsoft.SqlServer.DTSPipelineWrap"
                      publicKeyToken="89845dcd8080cc91" />
                    <bindingRedirect oldVersion="10.0.0.0" newVersion="11.0.0.0" />
                  </dependentAssembly>
                  <dependentAssembly>
                    <assemblyIdentity name="Microsoft.SqlServer.DTSRuntimeWrap"
                      publicKeyToken="89845dcd8080cc91" />
                    <bindingRedirect oldVersion="10.0.0.0" newVersion="11.0.0.0" />
                  </dependentAssembly>
                  <dependentAssembly>
                    <assemblyIdentity name="Microsoft.SqlServer.ManagedDTS"
                      publicKeyToken="89845dcd8080cc91" />
                    <bindingRedirect oldVersion="10.0.0.0" newVersion="11.0.0.0" />
                  </dependentAssembly>
                  <dependentAssembly>
                    <assemblyIdentity name="Microsoft.SqlServer.PipelineHost"
                      publicKeyToken="89845dcd8080cc91" />
                    <bindingRedirect oldVersion="10.0.0.0" newVersion="11.0.0.0" />
                  </dependentAssembly>
                  <dependentAssembly>
                    <assemblyIdentity name="Microsoft.SqlServer.SQLTask"
                      publicKeyToken="89845dcd8080cc91" />
                    <bindingRedirect oldVersion="10.0.0.0" newVersion="11.0.0.0" />
                  </dependentAssembly>
                  <dependentAssembly>
                    <assemblyIdentity name="Microsoft.SqlServer.XmlSrc"
                      publicKeyToken="89845dcd8080cc91" />
                    <bindingRedirect oldVersion="10.0.0.0" newVersion="11.0.0.0" />
                  </dependentAssembly>
                </assemblyBinding>

    -   Code to redirect to SQL Server 2014 Integration Services
                <assemblyBinding xmlns="urn:schemas-microsoft-com:asm.v1">
                  <dependentAssembly>
                    <assemblyIdentity name="Microsoft.SqlServer.DTSPipelineWrap"
                      publicKeyToken="89845dcd8080cc91" />
                    <bindingRedirect oldVersion="10.0.0.0" newVersion="12.0.0.0" />
                  </dependentAssembly>
                  <dependentAssembly>
                    <assemblyIdentity name="Microsoft.SqlServer.DTSRuntimeWrap"
                      publicKeyToken="89845dcd8080cc91" />
                    <bindingRedirect oldVersion="10.0.0.0" newVersion="12.0.0.0" />
                  </dependentAssembly>
                  <dependentAssembly>
                    <assemblyIdentity name="Microsoft.SqlServer.ManagedDTS"
                      publicKeyToken="89845dcd8080cc91" />
                    <bindingRedirect oldVersion="10.0.0.0" newVersion="12.0.0.0" />
                  </dependentAssembly>
                  <dependentAssembly>
                    <assemblyIdentity name="Microsoft.SqlServer.PipelineHost"
                      publicKeyToken="89845dcd8080cc91" />
                    <bindingRedirect oldVersion="10.0.0.0" newVersion="12.0.0.0" />
                  </dependentAssembly>
                  <dependentAssembly>
                    <assemblyIdentity name="Microsoft.SqlServer.SQLTask"
                      publicKeyToken="89845dcd8080cc91" />
                    <bindingRedirect oldVersion="10.0.0.0" newVersion="12.0.0.0" />
                  </dependentAssembly>
                  <dependentAssembly>
                    <assemblyIdentity name="Microsoft.SqlServer.XmlSrc"
                      publicKeyToken="89845dcd8080cc91" />
                    <bindingRedirect oldVersion="10.0.0.0" newVersion="12.0.0.0" />
                  </dependentAssembly>
                </assemblyBinding>

4.  Save the file.
5.  Restart the Data Import/Export Framework service.
6.  Test that your changes are working as expected.





