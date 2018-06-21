---
title: Configuring network load balancing for services
TOCTitle: Configuring network load balancing for services
ms:assetid: 9ecde78e-7da2-4677-b9a2-17f3e7fe16aa
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh397322(v=AX.60)
ms:contentKeyID: 36929813
ms.date: 08/30/2013
mtps_version: v=AX.60
---

# Configuring network load balancing for services [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Clusters of instances of Application Object Server (AOS) for Microsoft Dynamics AX can be load balanced in two ways: the cluster can either include or lack a dedicated load-balancing AOS instance. However, load-balanced AOS clusters cannot load balance network traffic for services. When you use either of the two AOS load-balancing approaches, all traffic for services is routed to the first AOS instance in the list of servers that belong to the cluster. For more information about how to load balance AOS clusters, see [AOS clusters without a dedicated load balancer](aos-clusters-without-a-dedicated-load-balancer.md) and [AOS clusters with a dedicated load balancer](aos-clusters-with-a-dedicated-load-balancer.md). To enable load balancing for services, you must instead use Windows Server Network Load Balancing (NLB). For information about NLB, see the [Network Load Balancing Deployment Guide](http://go.microsoft.com/fwlink/?linkid=225684) on the TechNet website.

## Network Load Balancing considerations for services

When you set up systems to load balance the traffic for Microsoft Dynamics AX services, keep the following points in mind:

  - If load balancing is configured without a load-balancing AOS instance, all AOS computers should also participate in the NLB cluster.

  - If a dedicated load-balancing AOS instance is used, do not include the dedicated AOS instance in the NLB cluster. In this scenario, service calls are routed through NLB, but remote procedure calls (RPCs) continue to be routed to the dedicated load-balancing AOS instance.

  - You must use the same domain user account for all AOS instances when you configure network load balancing for services. For more information about the AOS account, see [Change the account used by AOS](change-the-account-used-by-aos.md).

  - Any client that consumes Microsoft Dynamics AX services must use the virtual name or IP address of the NLB cluster to make service calls. These clients include the following clients:
    
      - The Microsoft Dynamics AX client program.
    
      - Custom client applications.
    
      - Clients that consume Web services over the Internet. These clients include clients that consume Web services through an Internet Information Services (IIS) Web farm. For more information, see [Configuring network load balancing for services](configuring-network-load-balancing-for-services.md). For more information about IIS Web farms, see [Managing Shared Configuration](http://go.microsoft.com/fwlink/?linkid=225687) on the IIS website. For more information about how to work with configuration files in IIS, see [Working with Configuration Files in IIS 7](http://go.microsoft.com/fwlink/?linkid=225688) on the TechNet website.

  - The following Microsoft Dynamics AX features must use NLB as the load-balancing mechanism when high availability of service is required:
    
      - **Kanban schedule board** form
    
      - Microsoft SQL Server Reporting Services
    
      - Office Add-ins for Microsoft Dynamics AX

  - NLB manages host instances, but it does not manage AOS instances. Therefore, when a host instance fails, NLB removes the failed host instance from the cluster. However, when an AOS instance fails, NLB does not remove the host instance from the cluster. Instead, NLB continues to try to route traffic to the failed AOS instance. Therefore, you must implement a monitoring solution to detect when an AOS instance fails, so that you can appropriately deal with the failure. For example, [Microsoft System Center Operations Manager](http://go.microsoft.com/fwlink/?linkid=226205) (SCOM) provides this kind of system management facilities.


> [!WARNING]
> <P>Do not mix calls to RPC and Web services in this environment.</P>



The following diagram shows the topology for load balancing services by using NLB.

![Network Load Balancing topology for services](images/Hh397322.ServicesNLBTopology(AX.60).png "Network Load Balancing topology for services")

## Configuring Network Load Balancing for services

To configure NLB for Microsoft Dynamics AX, follow these general steps:

1.  On each computer that is participating in the load-balancing cluster, install an AOS instance.

2.  On a client computer, install the Microsoft Dynamics AX client program. For information about how to install the Microsoft Dynamics AX client program, see [Install a client](install-a-client.md).

3.  On each server computer in the cluster, configure NLB. For information about how to configure NLB, see the [Microsoft Support website](http://support.microsoft.com/kb/323437).
    

    > [!IMPORTANT]
    > <P>Do not use the same virtual name for the AOS cluster and the NLB cluster.</P>



4.  On the client computer, create a new client configuration by using the Microsoft Dynamics AX Client Configuration Utility. For information about how to use this utility, see [Client operations](client-operations.md).

5.  Save the configuration, and close the utility.

6.  On the client computer, use Regedit to add the two values that are listed in the following table to the registry subkeys at the path \\Software\\Microsoft\\Dynamics\\6.0\\Configuration\\new\_configuration\_name for both HKEY\_CURRENT\_USER and HKEY\_LOCAL\_MACHINE.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Name</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>wcflbservername</p></td>
    <td><p>A string value that contains the virtual name of the NLB cluster.</p></td>
    </tr>
    <tr class="even">
    <td><p>wcflbwsdlport</p></td>
    <td><p>A string value that contains the port number that is used to retrieve Web Services Description Language (WSDL) documents.</p></td>
    </tr>
    </tbody>
    </table>
    

    > [!NOTE]
    > <P>This subkey enables Microsoft Dynamics AX components to work with NLB settings. If you develop a client application that consumes Microsoft Dynamics AX services, and you want to use NLB, you can read these values, and then use them to route your calls appropriately.</P>



7.  On the client computer, reopen the Microsoft Dynamics AX Client Configuration Utility.

8.  Click **Configure Services** to open the Microsoft Service Configuration Editor. This step updates the Windows Communication Foundation (WCF) configuration so that it uses endpoint addresses that point to the virtual name or IP address of the NLB cluster.

9.  Save the WCF configuration file, and close the editor.

10. In the Microsoft Dynamics AX Client Configuration Utility, click **Manage**, and then save the configuration information as an .axc file. You can use this file as the standard file for configuring any client that connects to the NLB cluster to consume services.

11. Install any remaining components.

12. For each new client instance that you install, use the .axc file that you saved to specify the configuration. During setup, you can specify the path of the configuration file on the **Specify a location for configuration settings** page.

## Integration port considerations

When you create a new port, you must restart all AOS instances in the NLB cluster. If you do not restart the AOS instances, the new port will only be available on the AOS on which it was created.

To view the WSDL document for a service through NLB, replace the AOS name in the address that is provided by the port with the NLB name or its IP address.

## Considerations for services that are hosted by IIS

When you activate an integration port that exposes a Web service by using the HTTP adapter, Application Integration Framework (AIF) creates a folder that has a name that matches the name of the integration port. You can find this folder under the root folder of the site on the computer that runs IIS. You specified the name of this computer either during the installation of Web services on IIS or in the **Web sites** form.

The subfolder that AIF creates contains several files that are related to the deployment of the integration port. These files include a file that is named web.config. For IIS servers that connect to NLB clusters that load balance Microsoft Dynamics AX services, you must modify the web.config file for the website of each HTTP integration port. For Web farms, you must copy the configuration file and the associated service assemblies to each IIS server in the cluster. If you do not modify this file, the service URL on the WSDL page does not point to the NLB virtual name. Instead, the service URL contains the name of an individual AOS instance. To modify the web.config files, add or modify the section that is shown in the following example XML code. You must replace the text "IIS\_Port\_Number" with your IIS port number.

    <behaviors>
       <serviceBehaviors>
          <behavior name="routingData">
             <useRequestHeadersForMetadataAddress>
                <defaultPorts>
                  <add scheme="http" port="IIS_Port_Number" />
                </defaultPorts>
              </useRequestHeadersForMetadataAddress>
          </behavior>
       </serviceBehaviors>
    ...
    </behaviors>

For more information about the \<useRequestHeadersForMetadataAddress\> element, see [the MSDN website](http://go.microsoft.com/fwlink/?linkid=226206).

