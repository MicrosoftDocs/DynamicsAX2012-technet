---
title: (BRA) Configure POS files and integration
TOCTitle: (BRA) Configure POS files and integration
ms:assetid: 5220a1a2-932d-4bd2-a5c6-91bab14563da
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497720(v=AX.60)
ms:contentKeyID: 62200234
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (BRA) Configure POS files and integration 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

To apply the Microsoft Dynamics AX for Retail POS solution, you must use build of version 6.2.1000.1608 and an AX32.exe file of file version 6.2.1000.1608. This build is registered by Microsoft with the government of Brazil, and this file version lets you register the proper DLL and EXE files with federal and state governments in Brazil. This build and file version lets you integrate the point of sale (POS) with fiscal printers that are used in POS transactions, and also configure electronic funds transfer (EFT) integration with the third-party software D-TEF Dedicado. After the solution is installed with the required version, you should not install any updates or hotfixes that are not compliant with Programa Aplicativo Fiscal - Emissor Cupom Fiscal (PAF-ECF) law.

Follow the steps in this topic perform the following tasks to set up Microsoft Dynamics AX for Retail POS for the Brazilian market.

  - Configure the POS.exe.config file – The POS.exe.config file is created when you install Retail POS. You must set up the following parameters to make the solution functional for Brazil.
    
      - Set up parameters for fiscal printers
    
      - Specify where the Retail POS client is installed
    
      - Set up parameters for card payments
    
      - Set up the parameter to rebuild the AutorizedECF.xml file
    
      - Amend POS.exe.config file tags

  - Configure Retail POS to use fiscal printers

  - Configure EFT integration with Direção D-TEF

  - Verify the POS file’s MD5 hash code

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Version</strong></p></td>
<td><p>Retail in AX 2012 R2 or AX 2012 R3 is installed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Brazil</p></td>
</tr>
</tbody>
</table>


## Set up parameters for fiscal printers

To handle Daruma or Bematech fiscal printers, ensure that the **FiscalPrinterAssembly\_BR** and **FiscalPrinterClass\_BR** parameters are included in the POS.exe.config file.

  - For Daruma fiscal printers, set up the following parameters:
    
        <setting name="FiscalPrinterAssembly_BR" serializeAs="String">
        <value>Microsoft.Dynamics.Retail.FiscalPrinter.DarumaPrinter.dll</value>
        </setting>
        <setting name="FiscalPrinterClass_BR" serializeAs="String">
        <value>Microsoft.Dynamics.Retail.FiscalPrinter.DarumaPrinter.DarumaPrinter</value>
        </setting>

  - For Bematech fiscal printers, set up the following parameters:
    
        <setting name="FiscalPrinterAssembly_BR" serializeAs="String">
        <value>Microsoft.Dynamics.Retail.FiscalPrinter.BematechPrinter.dll</value>
        </setting>
        <setting name="FiscalPrinterClass_BR" serializeAs="String">
        <value>Microsoft.Dynamics.Retail.FiscalPrinter.BematechPrinter.BematechPrinter</value>
        </setting>

## Specify where the AX 2012 R2 or AX 2012 R3 client is installed

In the **DynamicsAxClientBinFolder** tag, specify the name of the folder where the AX 2012 R2 or AX 2012 R3 client is installed.

## Set up parameters for card payments

Set the **EnableCardPayment** tag to **true** if the POS uses EFT integration; otherwise, set the tag to **false**.

Set the **LogCardPayments** tag to **true** if the POS logs EFT transactions; otherwise, set the tag to **false**.

## Set up the parameter to rebuild the AutorizedECF.xml file

Set the **RebuildAuthorizedEcfXml** tag to **true** if the AutorizedECF.xml file can be rebuilt; otherwise, set the tag to **false**. There is specific legislation that governs how you must set this parameter. For more information, check with your local authorities.

## Amend POS.exe.config file tags

Change the POS.exe.config file tags as follows:

1.  Include a \<sectionGroup\> node before the \</configSections\> tag.

2.  Include an \<applicationSettings\> node before the \</configuration\> tag.

3.  Include the \<setting\> node that you want to set up.

The following example is an amended POS.exe.config file with the changes highlighted as bold.

    <?xml version="1.0" encoding="utf-8" ?> 
    <configuration> 
    
    <configSections><section name="AxRetailPOS" type="LSRetailPosis.Settings.ConfigFile.AppConfiguration, SystemSettings, Version=6.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35" /><sectionGroup name="applicationSettings" type="System.Configuration.ApplicationSettingsGroup, System, Version=2.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089"><section name="Microsoft.Dynamics.Retail.FiscalPrinter.Properties.Settings" type="System.Configuration.ClientSettingsSection, System, Version=2.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089" requirePermission="false"/></sectionGroup></configSections>
    
    
    <AxRetailPOS OfflineDatabaseConnectionString="Data Source=MAUROPS-w8;Initial Catalog=AXRETAILPOSOFFLINE;Integrated Security=True;Persist Security Info=False;Pooling=True;Encrypt=True;TrustServerCertificate=True" 
    StoreDatabaseConnectionString="Data Source=MAUROPS-w8;Initial Catalog=AXRETAILPOS;Integrated Security=True;Persist Security Info=False;Pooling=True;Encrypt=True;TrustServerCertificate=True" 
    StoreId="S0001" TerminalId="0001" DATAAREAID="tst" /> 
    <system.diagnostics> 
    <sources> 
    <!-- this registers the listener with traces from a specific source --> 
    <source name="RetailNetTracer" switchValue="All"> 
    <listeners> 
    <add name="RollingXmlWriterTraceListener" /> 
    </listeners> 
    </source> 
    <source name="RetailNetTracerEventLog" switchValue="All"> 
    <listeners> 
    <add name="EventLogTraceListener" /> 
    </listeners> 
    </source> 
    </sources> 
    <!-- this defines a listener --> 
    <sharedListeners> 
    <!-- initializeData is the file name. If empty, it is going to be created in %TEMP%\RetailLogs\<name of exe> --> <add name="RollingXmlWriterTraceListener" 
    type="Microsoft.Dynamics.Retail.Diagnostics.RollingXmlWriterTraceListener, Microsoft.Dynamics.Retail.Diagnostics" 
    initializeData="" 
    MaxLogFileInBytes="50000000" 
    traceOutputOptions="ProcessId, DateTime, LogicalOperationStack" /> 
    <add name="EventLogTraceListener" type="System.Diagnostics.EventLogTraceListener" initializeData="Dynamics AX Retail" /> 
    </sharedListeners> 
    <!-- this configures tracing --> 
    <trace autoflush="true"> 
    <listeners> 
    <remove name="Default" /> 
    <add name="RollingXmlWriterTraceListener" /> 
    <add name="EventLogTraceListener" /> 
    </listeners> 
    </trace> 
    </system.diagnostics> 
    <system.serviceModel> 
    <bindings> 
    <netTcpBinding> 
    <binding name="TSNetTcpBinding" closeTimeout="00:01:00" openTimeout="00:01:00" 
    receiveTimeout="00:10:00" sendTimeout="00:01:00" transactionFlow="false" 
    transferMode="Streamed" transactionProtocol="OleTransactions" 
    hostNameComparisonMode="StrongWildcard" listenBacklog="32" 
    maxBufferPoolSize="67108864" maxBufferSize="1048576" maxConnections="16" 
    maxReceivedMessageSize="10485760"> 
    <readerQuotas maxDepth="32" maxStringContentLength="1048576" maxArrayLength="16384" 
    maxBytesPerRead="1048576" maxNameTableCharCount="16384" /> 
    <reliableSession ordered="true" inactivityTimeout="00:10:00" 
    enabled="false" /> 
    <security mode="TransportWithMessageCredential"> 
    <transport clientCredentialType="None" protectionLevel="EncryptAndSign" /> 
    <message clientCredentialType="UserName" algorithmSuite="Default" /> 
    </security> 
    </binding> 
    <binding name="TSNetTcpBindingNoSecurity" closeTimeout="00:01:00" openTimeout="00:01:00" 
    receiveTimeout="00:10:00" sendTimeout="00:01:00" transactionFlow="false" 
    transferMode="Streamed" transactionProtocol="OleTransactions" 
    hostNameComparisonMode="StrongWildcard" listenBacklog="32" 
    maxBufferPoolSize="67108864" maxBufferSize="1048576" maxConnections="16" 
    maxReceivedMessageSize="10485760"> 
    <readerQuotas maxDepth="32" maxStringContentLength="1048576" maxArrayLength="16384" maxBytesPerRead="1048576" maxNameTableCharCount="16384" /> 
    <reliableSession ordered="true" inactivityTimeout="00:10:00" 
    enabled="false" /> 
    <security mode="None"> 
    <transport clientCredentialType="None" protectionLevel="EncryptAndSign" /> 
    <message clientCredentialType="UserName" algorithmSuite="Default" /> 
    </security> 
    </binding> 
    </netTcpBinding> 
    <wsHttpBinding> 
    <binding name="TSWsHttpBinding" closeTimeout="00:01:00" openTimeout="00:01:00" 
    receiveTimeout="00:10:00" sendTimeout="00:01:00" bypassProxyOnLocal="false" 
    transactionFlow="false" hostNameComparisonMode="StrongWildcard" 
    maxBufferPoolSize="10485760" maxReceivedMessageSize="1048576" 
    messageEncoding="Text" textEncoding="utf-16" useDefaultWebProxy="true" 
    allowCookies="false"> 
    <readerQuotas maxDepth="32" maxStringContentLength="1048576" maxArrayLength="16384" 
    maxBytesPerRead="1048576" maxNameTableCharCount="16384" /> 
    <reliableSession ordered="true" inactivityTimeout="00:10:00" 
    enabled="false" /> 
    <security mode="TransportWithMessageCredential"> 
    <transport clientCredentialType="None" proxyCredentialType="None" realm="" /> 
    <message clientCredentialType="UserName" negotiateServiceCredential="true" 
    algorithmSuite="Default" /> 
    </security> 
    </binding> 
    <binding name="TSWsHttpBindingNoSecurity" closeTimeout="00:01:00" openTimeout="00:01:00" 
    receiveTimeout="00:10:00" sendTimeout="00:01:00" bypassProxyOnLocal="false" 
    transactionFlow="false" hostNameComparisonMode="StrongWildcard" 
    maxBufferPoolSize="10485760" maxReceivedMessageSize="1048576" 
    messageEncoding="Text" textEncoding="utf-16" useDefaultWebProxy="true" 
    allowCookies="false"> 
    <readerQuotas maxDepth="32" maxStringContentLength="1048576" maxArrayLength="16384" 
    maxBytesPerRead="1048576" maxNameTableCharCount="16384" /> 
    <reliableSession ordered="true" inactivityTimeout="00:10:00" 
    enabled="false" /> 
    <security mode="None"> 
    <transport clientCredentialType="None" proxyCredentialType="None" realm="" /> 
    <message clientCredentialType="UserName" negotiateServiceCredential="true" 
    algorithmSuite="Default" /> 
    </security> 
    </binding> 
    </wsHttpBinding> 
    </bindings> 
    <client> 
    <endpoint address="net.tcp://hostname/RetailTransactionService/Service.svc/Common" 
    binding="netTcpBinding" bindingConfiguration="TSNetTcpBinding" contract="Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ITransactionService" 
    name="TSNetTcpEndpoint"> 
    <identity> 
    <dns /> 
    </identity> 
    </endpoint> 
    <endpoint address="net.tcp://hostname/RetailTransactionService/Service.svc/Common" 
    binding="netTcpBinding" bindingConfiguration="TSNetTcpBindingNoSecurity" contract="Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ITransactionService" 
    name="TSNetTcpEndpointNoSecurity"> 
    <identity> 
    <dns /> 
    </identity> 
    </endpoint> 
    <endpoint address="https://hostname/RetailTransactionService/Service.svc/Common" 
    binding="wsHttpBinding" bindingConfiguration="TSWsHttpBinding" contract="Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ITransactionService" 
    name="TSWsHttpEndpoint"> 
    <identity> 
    <dns /> 
    </identity> 
    </endpoint> 
    <endpoint address="http://hostname/RetailTransactionService/Service.svc/Common" 
    binding="wsHttpBinding" bindingConfiguration="TSWsHttpBindingNoSecurity" contract="Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ITransactionService" 
    name="TSWsHttpEndpointNoSecurity"> 
    <identity> 
    <dns /> 
    </identity> 
    </endpoint> 
    </client> 
    </system.serviceModel> 
    
    <applicationSettings><Microsoft.Dynamics.Retail.FiscalPrinter.Properties.Settings><setting name="FiscalPrinterAssembly_BR" serializeAs="String"><value>Microsoft.Dynamics.Retail.FiscalPrinter.BematechPrinter.dll</value></setting><setting name="FiscalPrinterClass_BR" serializeAs="String"><value>Microsoft.Dynamics.Retail.FiscalPrinter.BematechPrinter.BematechPrinter</value></setting><setting name="WatchDog" serializeAs="String"><value>True</value></setting><setting name="LogCardPayments" serializeAs="String"><value>True</value></setting><setting name="ShowCardPaymentsDiscardMessage" serializeAs="String"><value>True</value></setting><setting name="StartCardPaymentProgramManager" serializeAs="String"><value>False</value></setting><setting name="DynamicsAxClientBinFolder" serializeAs="String"><value>C:\temp\</value></setting><setting name="RebuildAuthorizedEcfXml" serializeAs="String"><value>True</value></setting><setting name="EnableCardPayment" serializeAs="String"><value>False</value></setting></Microsoft.Dynamics.Retail.FiscalPrinter.Properties.Settings></applicationSettings>
    
    
    </configuration> 

## Configure Retail POS to use fiscal printers

The POS system must compare the fiscal printer’s serial number and grand total (GT) with the data stored in an encrypted XML file. This encrypted file can be provided only by the manufacturer of the POS software, which is Microsoft. If the information doesn’t match, the POS system will not interact with the connected fiscal printer.

You must enable the POS to communicate with fiscal printers when a customer uses this solution along with a new fiscal printer, or when a fiscal printer is used after maintenance is performed on it. You must also follow this procedure if the encrypted file has been damaged or deleted, or if it does not function correctly.

To download the encrypted file, you must request it by using the Microsoft order system on the [Microsoft PartnerSource](https://mbs.microsoft.com/partnersource) website. For more information on how to request for this file, see [November 2012 Hora Dynamics partner newsletter](https://mbs.microsoft.com/downloads/partner/operationslatam/dynamicshournovember2012portuguese.pdf). The encrypted file that you download will have a file name such as 86046463002668\_DR0812BR000000320719\_AuthorizedECF.xml.

To enable the POS to communicate with fiscal printers, follow these steps:

1.  Rename the encrypted file **AuthorizedECF.xml**.

2.  Store the renamed file in the folder c:\\ProgramFiles\\Microsoft Dynamics AX\\60\\Retail POS\\Arquivos PAF-ECF.
    

    > [!NOTE]
    > <P>Depending on the version of Microsoft Windows that you use, the parent folder for the Arquivos PAF-ECF folder might be named Program files or Program files (x86). However, you must be careful when you rename this file, because any change made to its data will invalidate it, and the printer will not be recognized by the POS.</P>



3.  Optional: In some cases and under certain conditions, some states in Brazil allow this encrypted file to be rebuilt automatically by the POS solution. If this is the case, you should set the **RebuildAutorizedEcfXml** parameter in the POS.exe.config file to **true**.

## Configure EFT integration with Direção D-TEF

You must integrate Retail POS with the third-party software D-TEF Dedicado that is commercialized by the EFT provider Direção Processamento de Dados Ltda.

To enable the integration with the EFT provider, you must ensure that the following configuration is set up in the POS.exe.config file:

    </setting> 
    <setting name="EnableCardPayment" serializeAs="String"> 
    <value>True</value> 
    </setting> 9 LOCAL FEATURES FOR BRAZIL – RETAIL AND POINT OF SALE (POS) 
    <setting name="LogCardPayments" serializeAs="String"> 
    <value>True</value> 
    </setting>

The EFT provided by Direção has some configuration requirements that you must set up prior to integration with Retail POS. See the EFT documentation on the [Direção](http://www.direcao.com/) website for details about the requirements.


> [!NOTE]
> <P>You must change only the EFT configuration settings that are described in the D-TEF Dedicado documentation. If you change other EFT configuration settings, the EFT and the Retail POS solution will not function correctly.</P>



You can also access the administrative EFT function through a blank operation. See the EFT documentation to find out which administrative EFT functions are available. To enable access to that function, you can add or configure a button with a blank operation, setting the **Operation number** field to **4** and leaving the **Blank operation param** field blank. For more information about how to use a blank operation, see [How to: Use BlankOperations to Implement Custom Features](use-blankoperations-to-implement-custom-features.md).

## Verify the POS file’s MD5 hash code

You must verify the MD5 hash code for the binary files that are used to fulfill the legal requirements associated with this POS solution. The files that are listed in MD5FileList.txt file can affect the customization of Retail POS. For more information, see “Limitations of POS customization for Brazil” in [(BRA) About POS customization limitations and predefined blank operations](bra-about-pos-customization-limitations-and-predefined-blank-operations.md).

1.  Open the c:\\ProgramFiles\\Microsoft Dynamics AX\\5.0\\Retail POS\\Arquivos PAF-ECF folder, and then double-click the MD5FileList.txt file. The MD5FileList.txt file is created or overwritten whenever the POS is started.

2.  Ensure that the installation is compliant with the certification. The MD5 hash code that is printed at the bottom of a fiscal receipt must be **6488F0010F3095760642950C1FD26FA0**; otherwise, one or more files that are listed in MD5FileList.txt file will not match the original files that are certified by Microsoft. The original MD5FileList.txt files that are certified by Microsoft include the following content.
    
        N160316817000103113256506117 96242809         MICROSOFT INFORMÁTICA LTDA. 
        N2POL5212012MICROSOFT DYNAMICS AX                               62 
        N3POS.exe                                              C4B3BA89CBC6FD249CE0C0AA3F7980DB 
        N3Application.dll                                      77759CFACF0BEC6BAFBDDB086F2A0F79 
        N3ApplicationTriggers.dll                              40F818B5C68BE80DBFF579B6A64ADA6E 
        N3Ax32.exe                                             C2A30BACFB1B2FC195D7CAF8B09941D4 
        N3DataAccess.dll                                       0A7CF3F508BABC188B510F2A83726195 
        N3Dialog.dll                                           68B2F69C640319B96D89C782372B1E97 
        N3Discount.dll                                         6ADC41CD247C36C95E815D70C9A2CF89 
        N3EOD.dll                                              411A095D20654001B2D6D41292377C88 
        N3GiftCard.dll                                         FD0EE529BC13BC1FF0B304D58FFEA3DB 
        N3Microsoft.Dynamics.Retail.FiscalPrinter.BematechPrinter.dll   66DA3385B9AC991CF9234EA6C2B20BD8 
        N3Microsoft.Dynamics.Retail.FiscalPrinter.DarumaPrinter.dll   C1C39E33B8E1B1D6E05D246A81F0AF5F 
        N3Microsoft.Dynamics.Retail.FiscalPrinter.dll          5DF5787B756D8E4914841DD845224BB7 
        N3POSProcesses.dll                                     528580E5AC72200AAA857AA2C7E0707C 
        N3POSResources.dll                                     B0D4D572A90F6FC8E3140669798D2D81 
        N3Peripherals.dll                                      6A56DFACE9CA78C24FD00840586BE9D5 
        N3Printing.dll                                         6C128B5971D81CC825E7FD4939911093 
        N3SystemFramework.dll                                  6678EF6E459D3C84E805D1F648EF3704 
        N3Tax.dll                                              FA0BC8A9D262D6182046B183216FE951 
        N960316817000103113256506117 000018 
        EAD026CDD5268BA4A107722FA31191292EBC8AADC63ACC3184C9441F87920937F11F76EE16F85DD645B10BD81F16508056031303D3DA2A1D73C5327B48B57728DC996EA1BD9BEF7EAA89FE7DC3BD5C3F0E68A01C1E28342E24E682EA9D23863C179A3C37C9BC0AC8ED0767564F59C90617A95E8FBF4C1795B5D04B927EA03D47BBC 

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

