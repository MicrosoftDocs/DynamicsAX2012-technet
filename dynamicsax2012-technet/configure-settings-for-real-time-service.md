---
title: Configure settings for Real-time Service
TOCTitle: Configure settings for Real-time Service
ms:assetid: d263b65e-0928-48f6-abb2-81dc3918724b
ms:mtpsurl: https://technet.microsoft.com/library/Dn343753(v=AX.60)
ms:contentKeyID: 56115644
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- xml
---

# Configure settings for Real-time Service 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can modify the logging and binding settings for Real-time Service by changing the web.config file, which is a standard WCF configuration file. By default, the file is located at \<Drive\>:\\inetpub\\DynamicsAxRetail\\CommerceDataExchangeRealtimeService\\Web.config.

## Change the logging level

The logging level for the event log and the trace log is controlled by using the \<system.diagnostics\> element in the configuration file. The default logging level is set to **Warning** for the trace log and **Error** for the event log, as shown in the following example.

``` xml
<system.diagnostics>
     <sources>
       <!-- this registers the listener with traces from a specific source -->
       <source name="RetailNetTracer" switchValue="Warning">
         <listeners>
           <add name="RollingXmlWriterTraceListener" />
         </listeners>
       </source>
       <source name="RetailNetTracerEventLog" switchValue="Error">
         <listeners>
           <add name="EventLogTraceListener" />
         </listeners>
       </source>
 </sources>
 ... </system.diagnostics>
```

If you need more extensive logging, change the logging level to **Information**.

For information about how to use the logs for troubleshooting, see [Troubleshoot issues in Real-time Service](troubleshoot-issues-in-real-time-service.md).

## Change the binding configuration

The default binding for Real-time Service is **netTcpBinding**. The **WSHttp** binding is also supported for https connections.

The following example shows the relevant node from the configuration file. In the endpoint address line, you can see binding=”netTcpBinding”.

``` xml
<services>
       <service behaviorConfiguration="ReleaseBehavior" name="Microsoft.Dynamics.Retail.TransactionServices.TransactionService">
        <endpoint address="Common" binding="netTcpBinding" bindingConfiguration="StreamedTCPBinding" name="Common" contract="Microsoft.Dynamics.Retail.TransactionServices.Contracts.ITransactionService" />
  ...
       </service>
     </services>
```

If you change the binding from **netTcpBinding** to **WSHttp** in the configuration file, you must also update the port number on the Real-time Service profile in Microsoft Dynamics AX. This ensures that the client and server can work together. For information about how to update the profile, see [Set up a Real-time Service profile](set-up-a-real-time-service-profile.md).

  


