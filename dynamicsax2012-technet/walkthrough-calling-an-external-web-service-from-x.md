---
title: 'Walkthrough: Calling an External Web Service from X++'
TOCTitle: 'Walkthrough: Calling an External Web Service from X++'
ms:assetid: 022c7efe-c7c5-4270-896c-7e536ae88221
ms:mtpsurl: https://technet.microsoft.com/library/Hh500185(v=AX.60)
ms:contentKeyID: 37820252
author: tonyafehr
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Calling an External Web Service from X++ 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the Bing ™ Search service API to include search functionality in your Microsoft Dynamics AX application. You use the Application ID from Bing to create a service reference in a project in Visual Studio and then add the project to the AOT. Then you call the search service from X++ with a search string to view the search results. The example in this topic issues a search request and returns the results that are shown in an **Infolog** window.

This walkthrough illustrates the following tasks:

  - Creating a service reference

  - Calling the service from a job to view the results


> [!NOTE]
> <P>Code that consumes a Web service must run on the server. Otherwise you will receive an error.</P>



## Prerequisites

To complete this walkthrough you will need:

  - Microsoft Visual Studio 2010.

  - Visual Studio Tools for Microsoft Dynamics AX 2012. For more information, see [Install Visual Studio Tools](install-visual-studio-tools.md).

  - A Bing application ID for your application. For information about how to obtain an application ID, see the [Bing Developer Center](http://www.bing.com/toolbox/bingdeveloper/).

## Create and Add the Service Reference

You create the service reference and add it to the AOT in Visual Studio by using the Visual Studio Tools for Microsoft Dynamics AX 2012.

### To create the service reference

1.  Open Visual Studio 2010 and then create a new Visual C\# **Class Library** project.

2.  Type **BingSearch.ServiceReferences** for the project name.

3.  In the Solution Explorer window, right-click the project name and then click **Add Service Reference**.

4.  Type the URL for the web service in the **Address** field.
    
    The URL for the Bing API web services is http://api.bing.net/search.wsdl?AppID=\[YOUR\_BING\_APPID\]\&version=2.2, where \[YOUR\_BING\_APPID\] is the Application ID you received from the <http://www.bing.com/developers> site.

5.  Click **Go** to locate the service and then click **Ok**.
    
    The following screenshot illustrates the **Add Service Reference** window after locating the service.
    
    ![AddServiceReferenceDialogScreenshot](images/Hh500185.AddServiceReference(AX.60).jpg "AddServiceReferenceDialogScreenshot")

6.  Right-click the project name and then click **Add BingSearch.ServiceReferences to AOT**.

7.  Select the **BingSearch.ServiceReferences** project. In the **Properties**, verify that the properties are set as shown in the following table.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p></p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Deploy to Client</p></td>
    <td><p><strong>Yes</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>Deploy to EP</p></td>
    <td><p><strong>No</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>Deploy to Server</p></td>
    <td><p><strong>Yes</strong></p></td>
    </tr>
    </tbody>
    </table>


### To verify the service reference

1.  In the Microsoft Dynamics AX client, open the Developer Workspace.

2.  In the AOT, move to **Visual Studio Projects** \> **C Sharp Projects** to view **BingSearch.ServiceReferences**.
    
    The service reference is available when the project has been added successfully to the AOT.

## Creating a Job to Run the Service

By default, jobs run on the Microsoft Dynamics AX client. When you use a web service from an X++ class, remember to use the client or server method modifiers. Alternatively you can set the RunOn property for the class to specify the location where the code is to be executed.

### To create and run the job

1.  In the AOT, right-click the **Jobs** node and then click **New Job** to open the **Jobs Editor**.

2.  The following example code creates a job called **CallBingService**.
    
        // This job uses an external service to run a Bing search 
        // The search string is “Dynamics AX” 
        static void CallBingService(Args _args) 
        { 
        // Replace the string [YOUR_BING_APPID] with your Application ID.
        #define.AppId([YOUR_BING_APPID])
        
        // This is the variable for the service client. 
        ClrObject clientType; 
        
        // This is the variable for the service client type. 
        BingSearch.ServiceReferences.BingV2ServiceReference.BingPortTypeClient _client;
        
        // These are the variables for web query objects. 
        BingSearch.ServiceReferences.BingV2ServiceReference.SearchRequest request; 
        BingSearch.ServiceReferences.BingV2ServiceReference.SourceType[] sourceTypes; 
        BingSearch.ServiceReferences.BingV2ServiceReference.SearchResponse response; 
        BingSearch.ServiceReferences.BingV2ServiceReference.WebResponse webResponse; 
        BingSearch.ServiceReferences.BingV2ServiceReference.WebResult[] webResults; 
        BingSearch.ServiceReferences.BingV2ServiceReference.WebResult webResult;
        int integer; 
        str string; 
        System.Exception ex; 
        new InteropPermission(InteropKind::ClrInterop).assert();
        
        // Use a try/catch block to catch errors immediately as CLR exceptions in the job.
           try 
           { 
               //Construct and configure the service client by retrieving the X++ type for the service and using the AifUtil class/
        
                 // Retrieve the X++ type for the Bing service client object. 
               clientType = CLRInterop::getType("BingSearch.ServiceReferences.BingV2ServiceReference.BingPortTypeClient"); 
        
                 // Use the AifUtil class to create an instance of the service client object. 
               _client = AifUtil::CreateServiceClient(clientType); 
        
               // Create the search request. 
               request = new BingSearch.ServiceReferences.BingV2ServiceReference.SearchRequest(); 
               request.set_AppId(#AppId); 
        
               // Note the search request string is “Dynamics AX”
               request.set_Query("Dynamics AX"); 
               sourceTypes = new BingSearch.ServiceReferences.BingV2ServiceReference.SourceType[1](); 
               sourceTypes.SetValue(BingSearch.ServiceReferences.BingV2ServiceReference.SourceType::Web, 0); 
               request.set_Sources(sourceTypes);
        
               // Configure the response for output.
               response = _client.Search(request); 
               webResponse = response.get_Web(); 
        
               // Get the search results. 
               webResults = webResponse.get_Results(); 
               webResult = webResults.GetValue(0); 
        
               // Display the first result in the InfoLog. 
               integer = webResponse.get_Total(); 
               info(strFmt("%1 total web results.", integer)); 
               integer = webResults.get_Count(); 
               info(strFmt("%1 results in response.", integer)); 
               info(""); 
               info("First result:"); 
               string = webResult.get_Title(); 
               info(strFmt("Title: %1", string)); 
               string = webResult.get_Description(); 
               info(strFmt("Description: %1", string)); 
               string = webResult.get_Url(); 
               info(strFmt("Url: %1", string)); 
           } 
           // Catch any exceptions.
           catch(Exception::CLRError) 
           {
             // Handle the exception and display message in the InfoLog.
             ex = CLRInterop::getLastException(); 
             info(ex.ToString()); 
           } 
        }
    

    > [!IMPORTANT]
    > <P>Replace the string [YOUR_BING_APPID] in the #define statement with the application ID you received from the Bing developer site.</P>



3.  Click **Go** to run the job.
    
    The following illustration shows the search results that appear in the **Infolog** window.
    
    ![Infolog Results](images/Hh500185.Infolog(AX.60).jpg "Infolog Results")

## Creating an Instance of a Service Client

The following example code shows how to construct and configure a service client object for the Bing service. To use the web service, you must use this code in your Microsoft Dynamics AX program to enable the service reference to construct and configure an instance of a service client.
```X++
    // Retrieve the X++ type for the Bing service client object. 
    clientType = CLRInterop::getType("BingSearch.ServiceReferences.BingV2ServiceReference.BingPortTypeClient"); 
    
    // Use the AifUtil class to create an instance of the service client object. 
    
    _client = AifUtil::CreateServiceClient(clientType);
    
```


> [!IMPORTANT]
> <P>Creating an instance of the service client makes the service configuration (in the Visual Studio project’s application configuration file) available to Microsoft Dynamics AX. Your code to run the service must include this call to AifUtil.</P>




> [!NOTE]
> <P>To use or modify the application configuration file in a C# project by using C# code to consume external web services, you should use the .NET Framework class ConfigurationChannelFactory. For more information, see <A href="https://msdn.microsoft.com/library/ee960149(v=vs.110).aspx">Configuration Channel Factory</A>.</P>



## See also

[Consuming External Web Services](consuming-external-web-services.md)

