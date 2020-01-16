---
title: 'Walkthrough: Calling the User Session Service'
TOCTitle: 'Walkthrough: Calling the User Session Service'
ms:assetid: f72707ae-a02a-44f3-8146-da3e0b9f50da
ms:mtpsurl: https://technet.microsoft.com/library/Gg865119(v=AX.60)
ms:contentKeyID: 35253634
author: Khairunj
ms.date: 07/15/2013
mtps_version: v=AX.60
dev_langs:
- csharp
---

# Walkthrough: Calling the User Session Service 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The user session service is one of the Windows Communication Foundation (WCF) system services exposed by Microsoft Dynamics AX. This service enables you to retrieve information about the current Windows user. Such information includes the user’s default language, default company, default company time zone, and so on. In this walkthrough, you will call the user session service from a C\# console application and display the user’s information.

This walkthrough illustrates the following tasks:

  - Add a reference to the user session service.

  - Call the service and retrieve the user data.

## Prerequisites

To complete this walkthrough you will need:

  - Microsoft Dynamics AX 2012

  - Visual Studio 2010

## Add a Reference to the User Session Service

In order to call the user session service, you must first create a project in Visual Studio and add a reference to the service.

### To add a reference to the user session service

1.  Open Visual Studio and create a new project by selecting **File** \> **New**\> **Project**.

2.  In the **Installed Templates** tree, select **Visual C\#** \> **Windows** and then click the **Console Application** template.

3.  Type a project name such as UserSessionServiceTest and then click **OK**.

4.  In Solution Explorer, right-click **References** and select **Add Service Reference**.

5.  In the **Address** Field, enter the URL of the service. For example, http://\<servername\>:8101/DynamicsAx/Services/UserSessionService.

6.  Click **Go**. In the **Services** tree, you should see the **UserSessionService**.

7.  Type UserSessionService in the **Namespace** field and then click **OK**.

## Call the Service and Retrieve the User Data

Write the code that calls the user session service and returns the current user information as follows:

### To call the user session service

1.  In the Program.cs file, add the following using statements.
    
    ``` csharp
    using System;
    using UserSessionService.UserSessionService;
    ```

2.  In the Program.cs Main method, add the code to call the service. The contents of the Program.cs file should look as follows:
    
    ``` csharp
    using System;
    using UserSessionServiceTest.UserSessionService;
    
    
    
    namespace UserSessionServiceTest
    {
        class Program
        {
            static void Main(string[] args)
            {
                UserSessionServiceClient client = new UserSessionServiceClient();
    
                // Set CallContext to Null to use the default values
                CallContext Context = null; 
    
                // Call the User Session service
                UserSessionInfo userSessionInfo = client.GetUserSessionInfo(Context);
    
                Console.WriteLine("AOS Locale:  " + userSessionInfo.AOSLocaleName); 
                Console.WriteLine("Language: " + userSessionInfo.AXLanguage);
                Console.WriteLine("Default Company: " + userSessionInfo.Company);
                Console.WriteLine("Company Time Zone: " + userSessionInfo.CompanyTimeZone);
                Console.WriteLine("Default Currency: " + userSessionInfo.CurrencyInfo.CurrencyCode);
                Console.WriteLine("UserID: " + userSessionInfo.UserId);
                Console.WriteLine("Preferred Calendar: " + userSessionInfo.UserPreferredCalendar);
                Console.WriteLine("Preferred Time Zone: " + userSessionInfo.UserPreferredTimeZone);
                Console.ReadKey(true);
          
            }
        }
    }
    ```

3.  Run the program. The program writes the current user data to the console window. The output resembles the following:
    
    AOS Locale: en-US
    
    Language: EN-US
    
    Default Company: CEU
    
    Company Time Zone: GMTMINUS0800PACIFICTIME
    
    Default Currency: USD
    
    UserID: YourNameHere
    
    Preferred Calendar: Gregorian
    
    Preferred Time Zone: GMTMINUS0800PACIFICTIME

## See also

[Using the Call Context](using-the-call-context.md)

[User Session Service](user-session-service.md)

[AIF System Services](aif-system-services.md)

