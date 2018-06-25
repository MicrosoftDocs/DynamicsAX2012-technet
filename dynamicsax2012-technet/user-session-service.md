---
title: User Session Service
TOCTitle: User Session Service
ms:assetid: d2f9fc07-3a66-46a5-9cc9-1d9c91309caf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg881307(v=AX.60)
ms:contentKeyID: 35251953
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# User Session Service [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, the user session service returns information about the calling user such as the user’s default language, default company, default company time zone, and so on. The user session service is:

  - automatically installed

  - by default, hosted by the Application Object Server (AOS)

  - always available

  - a Windows Communication Foundation (WCF) service that adheres to WCF protocols and standards

## How the User Session Service Works

The user session service has two service operations:

  - GetAccessRights – returns an AccessRight array that contains the permissions that the calling user has to a specified access controlled item. For example, you can use this service operation to return the permissions that the calling user has to menus, tables, and so on.

  - GetUserSessionInfo - returns a UserSessionInfo class. This class contains properties that return the actual user information for the current user as shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Property</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="https://technet.microsoft.com/en-us/library/hh153252(v=ax.60)">AXLanguage</a></p></td>
<td><p>Returns a string that specifies the user’s default language as defined in the <strong>User options</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><a href="https://technet.microsoft.com/en-us/library/hh152233(v=ax.60)">Company</a></p></td>
<td><p>Returns a string that specifies the user’s default company as defined in the <strong>User options</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p><a href="https://technet.microsoft.com/en-us/library/hh153400(v=ax.60)">CompanyTimeZone</a></p></td>
<td><p>Returns a <a href="https://technet.microsoft.com/en-us/library/hh153353(v=ax.60)">TimeZone</a> class that specifies the time zone for the user’s default company as defined in the <strong>User options</strong> form. The company time zone is in the <strong>Company information</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><a href="https://technet.microsoft.com/en-us/library/hh131129(v=ax.60)">CurrencyInfo</a></p></td>
<td><p>Returns a <a href="https://technet.microsoft.com/en-us/library/hh153397(v=ax.60)">ICurrencyInfo</a> class that specifies the default currency code associated with the user’s default company as defined in the <strong>User options</strong> form. The company currency code is in the <strong>Ledger</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p><a href="https://technet.microsoft.com/en-us/library/hh151937(v=ax.60)">UserPreferredCalendar</a></p></td>
<td><p>Returns a <a href="https://technet.microsoft.com/en-us/library/hh186599(v=ax.60)">PreferredCalendar</a> class that specifies the user’s preferred calendar as defined in the <strong>User options</strong> form. In the <strong>User options</strong> form, the <strong>User preferred calendar</strong> field is only visible if the user’s language is set to Arabic.</p></td>
</tr>
<tr class="even">
<td><p><a href="https://technet.microsoft.com/en-us/library/hh152984(v=ax.60)">UserPreferredTimeZone</a></p></td>
<td><p>Returns a <a href="https://technet.microsoft.com/en-us/library/hh153353(v=ax.60)">TimeZone</a> class that specifies the time zone for the user as defined in the <strong>User options</strong> form.</p></td>
</tr>
</tbody>
</table>


### User Session Service Architecture

The user session service is a Windows Communication Foundation (WCF) service that is contained in the Microsoft.Dynamics.AX.Services.Metadata.Service.dll assembly. This assembly is located in the server Bin directory. Depending on your configuration, the assembly is located in a directory such as C:\\Program Files\\Microsoft Dynamics AX\\\<version\>\\Server\\MicrosoftDynamicsAX\\Bin.

The user session service has the following configuration default values:

  - It is hosted by the AOS on port 8201 and the URL is net.tcp://\<servername\>:8201/DynamicsAx/Services/UserSessionService.

  - The service WSDL URL is http://\<servername\>:8101/DynamicsAx/Services/UserSessionService

  - It uses the netTcpBinding binding.

These settings will vary depending on what port number the service port and the WSDL port have been configured to use.

The service configuration settings are found in the Ax32Serv.exe.config file which is also located in the server Bin directory.

The user session service returns session information for only the user calling the service. The service retrieves the current user as defined in Windows. The service returns the default company, company time zone, and default currency for the user’s default company as specified in the **User options** form. You can open this form by navigating to **Administration** \> **Places** \> **Users** and clicking **Options**. The company information for the default company is found on the **Legal entities** form. You can open this form by navigating to **Basic** \> **Setup** \> **Organization** \> **Legal entities**. Currency information for the default company is found on the **Ledger** form. You can open this form by navigating to **General ledger** \> **Setup** \> **Ledger**.

## See also

[Walkthrough: Calling the User Session Service](walkthrough-calling-the-user-session-service.md)

[AIF System Services](aif-system-services.md)

