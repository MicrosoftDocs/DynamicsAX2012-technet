---
title: Firewall settings for Microsoft Dynamics AX components
TOCTitle: Firewall settings for Microsoft Dynamics AX components
ms:assetid: 3874d772-094b-490f-bd89-b288b4585ab6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731780(v=AX.60)
ms:contentKeyID: 35132606
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Firewall settings for Microsoft Dynamics AX components 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you use Windows Firewall to help protect your computers, Microsoft Dynamics AX components require the settings in the following table. For more information about Windows Firewall, see the Windows documentation.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Computer</p></th>
<th><p>Firewall setting</p></th>
<th><p>Notes</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Setup</p></td>
<td><p>Any</p></td>
<td><p>Allow outbound HTTP connections.</p></td>
<td><p>To access the documentation that is available from the Setup wizard, you must be able to connect to the Internet from the computer where you are running Setup.</p></td>
</tr>
<tr class="even">
<td><p>Databases</p></td>
<td><p>Database server</p></td>
<td><p>Exclude the port that is used by Microsoft SQL Server. By default, SQL Server uses port 1433.</p></td>
<td><p>For more information, see the SQL Server documentation.</p></td>
</tr>
<tr class="odd">
<td><p>Application Object Server (AOS)</p></td>
<td><p>AOS server</p></td>
<td><ul>
<li><p>Exclude the TCP/IP port that is used by the AOS instance. By default, AOS uses port 2712.</p>
<p>Setup automatically creates the inbound rule &quot;Dynamics AX 6.0 –MicrosoftDynamicsAX (RPC)&quot; for the TCP/IP port.</p></li>
<li><p>Exclude the services WSDL port that is used by the AOS instance. By default, AOS uses port 8101.</p>
<p>Setup automatically creates the inbound rule &quot;Dynamics AX 6.0 –MicrosoftDynamicsAX (WSDL)&quot; for the WSDL port.</p></li>
<li><p>Exclude the services endpoint port that is used by the AOS instance. By default, AOS uses port 8201.</p>
<p>Setup automatically creates the inbound rule &quot;Dynamics AX 6.0 –MicrosoftDynamicsAX (NetTCP)&quot; for the services endpoint port.</p></li>
</ul></td>
<td><p>Windows Firewall must be enabled on the computer. Each AOS instance must use a different port number.</p>
<div class="alert">

> [!NOTE]
> <P>By default, every time that you install an additional AOS instance on a computer, the TCP/IP port number and the services endpoint port numbers are incremented by 1. For example, by default, the second AOS instance on a computer is assigned to TCP/IP port 2713.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Client</p></td>
<td><p>Client workstation</p></td>
<td><p>Exclude Ax32.exe.</p></td>
<td><p>The client uses a TCP port to connect to the AOS instance.</p></td>
</tr>
<tr class="odd">
<td><p>Microsoft SQL Server Reporting Services extensions</p></td>
<td><p>Report server</p></td>
<td><p>Exclude the port that is used by Reporting Services virtual directories, if Reporting Services uses a port other than port 80.</p></td>
<td><p>If you are installing Reporting Services extensions in a perimeter network, you may need to add a firewall policy that enables you to connect to the Microsoft Dynamics AX database. For example, if you are using Forefront Threat Management Gateway (TMG), you must add a <strong>Non-Web Server Protocol Rule</strong>. For more information, see <a href="http://technet.microsoft.com/en-us/library/cc441596.aspx">Configuring SQL Server publishing</a> in the Forefront TMG documentation.</p></td>
</tr>
<tr class="even">
<td><p>Microsoft SQL Server Analysis Services integration</p></td>
<td><p>Analysis server</p></td>
<td><ul>
<li><p>Exclude the port that is used by Analysis Services. By default, Analysis Services uses port 2383.</p></li>
<li><p>If you are using SQL Server Browser, you must also exclude port 2382.</p></li>
</ul></td>
<td><p>For more information about how to configure access to Analysis Services through Windows Firewall, see the SQL Server documentation on MSDN.</p></td>
</tr>
<tr class="odd">
<td><p>Management Reporter</p></td>
<td><p></p></td>
<td><p>Exclude the port that is used by the Management Reporter application server. By default, the application server uses port 4712.</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Debugger</p></td>
<td><p>Developer workstation</p></td>
<td><p>Exclude AxDebug.exe and its target programs, such as Ax32.exe and AxServ32.exe.</p></td>
<td><p>The debugger uses a dynamically allocated TCP port.</p></td>
</tr>
<tr class="odd">
<td><p>Enterprise Portal for Microsoft Dynamics AX</p></td>
<td><p>Web server</p></td>
<td><ul>
<li><p>Enable the Web Server (HTTP).</p></li>
<li><p>Exclude the port that is used by the Enterprise Portal website, if the site uses a port other than port 80.</p></li>
</ul></td>
<td><p>If you do not enable the Web Server in Windows Firewall, you can view the site only from the local server.</p></td>
</tr>
<tr class="even">
<td><p>Help Server</p></td>
<td><p>Web server</p></td>
<td><p>Exclude the port that is used by the Help Server web site, if the site uses a port other than port 80.</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Enterprise Search</p></td>
<td><p>Web server</p></td>
<td><p>Exclude the port that is used by the Search web site, if the site uses a port other than port 80.</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Web services</p></td>
<td><p>Web server</p></td>
<td><p>Exclude the port that is used by the services web site, if the site uses a port other than port 80.</p></td>
<td><p>External programs use this port to consume the Microsoft Dynamics AX web services that are based on Internet Information Services (IIS).</p></td>
</tr>
<tr class="odd">
<td><p>Management utilities</p></td>
<td><p>Remotely managed computer</p></td>
<td><p>Enable Remote Administration.</p></td>
<td><p>You must enable Remote Administration on computers that are administered remotely by using Windows PowerShell. For example, enable Remote Administration on a computer if you deploy reports to that computer from another computer where Windows PowerShell is installed.</p></td>
</tr>
<tr class="even">
<td><p>Synch Service</p></td>
<td><p>Head-office communications server</p></td>
<td><ul>
<li><p>Exclude the port that is used by Microsoft SQL Server. By default, SQL Server uses port 1433.</p></li>
<li><p>Exclude the port that is used by Synch Service. By default, Synch Service uses port 16750.</p></li>
<li><p>Exclude the port that is used by Real-time Service. By default, Real-time Service uses port 1239.</p></li>
</ul></td>
<td><p>For instructions, see the <a href="http://go.microsoft.com/fwlink/?linkid=237283">PCI Implementation Guide for Microsoft Dynamics AX 2012 Feature Pack</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Synch Service</p></td>
<td><p>Store communications server</p></td>
<td><ul>
<li><p>Enable Internet Protocol security (IPsec).</p></li>
<li><p>Exclude the port that is used by Microsoft SQL Server. By default, SQL Server uses port 1433.</p></li>
<li><p>Exclude the port that is used by Synch Service. By default, Synch Service uses port 16750.</p></li>
</ul></td>
<td><p>For more information, see the <a href="http://go.microsoft.com/fwlink/?linkid=237283">PCI Implementation Guide for Microsoft Dynamics AX 2012 Feature Pack</a>.</p></td>
</tr>
<tr class="even">
<td><p>Real-time Service</p></td>
<td><p></p></td>
<td><p>Exclude the port that is used by Real-time Service, if the site uses a port other than port 80.</p></td>
<td><p>For more information, see the <a href="http://go.microsoft.com/fwlink/?linkid=237283">PCI Implementation Guide for Microsoft Dynamics AX 2012 Feature Pack</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Async Server</p></td>
<td><p></p></td>
<td><p>Exclude the HTTPS port that is used by Async Server.</p>
<p>Exclude the TCP port, if Async Server uses the TCP protocol.</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Retail POS</p></td>
<td><p>Store communications server</p></td>
<td><p>Exclude the port that is used by Microsoft SQL Server. By default, SQL Server uses port 1433.</p>
<p>Exclude the port that is used by Synch Service. By default, Synch Service uses port 16750.</p></td>
<td><p>For more information, see the <a href="http://go.microsoft.com/fwlink/?linkid=237283">PCI Implementation Guide for Microsoft Dynamics AX 2012 Feature Pack</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Retail POS</p></td>
<td><p>Store database server</p></td>
<td><p>Exclude the port that is used by Microsoft SQL Server. By default, SQL Server uses port 1433.</p>
<p>On a register that has its own local database, you only need to open the firewall to SQL Server if Synch Service is on a computer other than the register.</p></td>
<td><p>For more information, see the <a href="http://go.microsoft.com/fwlink/?linkid=237283">PCI Implementation Guide for Microsoft Dynamics AX 2012 Feature Pack</a>.</p></td>
</tr>
<tr class="even">
<td><p>Retail Server</p></td>
<td><p>Retail Server</p></td>
<td><p>Exclude the port that is used by the Retail Server web site.</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Retail Hardware Station</p></td>
<td><p>Retail Server</p></td>
<td><p>Exclude the port that is used by the Hardware Station web site.</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Retail online store</p></td>
<td><p>Web server</p></td>
<td><p>Exclude the ports that are used by the Retail online store web site. For a production environment, the online store uses ports 80 and 443, by default. For a developer environment, the online store uses the following ports, by default.</p>
<ul>
<li><p>40002: The online store (this is the port 80 site in production environments)</p></li>
<li><p>40004: The online store (this is the port 443 site in production environments with encrypted communications)</p></li>
<li><p>40003: The internal online store site (for changing site settings in SharePoint</p></li>
<li><p>40001: The internal product catalog site</p></li>
</ul></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Microsoft Dynamics ERP RapidStart Connector</p></td>
<td><p>Microsoft Dynamics ERP RapidStart Services host machine</p></td>
<td><ul>
<li><p>Exclude the executable file for the Microsoft Dynamics ERP RapidStart Connector service. By default, the file is installed in this location:</p>
<p>%SystemDrive%\Program Files\Microsoft Dynamics AX\60\RapidStartConnectorService\Microsoft.Dynamics.AX.AppConfig.ConnectorLoaderService.exe</p></li>
<li><p>Exclude the endpoint port that is used by the Microsoft Dynamics ERP RapidStart Connector service. By default, the service communicates with the Windows Azure Service Bus on ports 9350-9354, 80, and 443.</p></li>
<li><p>Exclude the Windows Azure Cloud Services Protocols.</p></li>
</ul></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  


