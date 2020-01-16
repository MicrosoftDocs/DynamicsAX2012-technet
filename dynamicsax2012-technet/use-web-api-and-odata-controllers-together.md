---
title: Use Web API and OData controllers together
TOCTitle: Use Web API and OData controllers together
ms:assetid: 1a8c2ac5-2eff-4e12-ab82-0dd7592d5b6d
ms:mtpsurl: https://technet.microsoft.com/library/Dn741437(v=AX.60)
ms:contentKeyID: 62219715
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Use Web API and OData controllers together 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

By default, all the Retail Server binaries in Microsoft Dynamics AX use OData only. If you want to use a controller that uses a traditional Web API, you can create your own Web API controller and extend the Web API configuration.

## Create a Web API Controller

The following example demonstrates how to create a Web API controller for Retail Server.


> [!NOTE]
> <P>You can find the sample code from this topic in the Retail SDK.</P>



    namespace Microsoft.Dynamics.RetailServer.Samples.Extensions
    {
        using System.Collections.Generic;
        using System.Runtime.InteropServices;
        using System.Web.Http;
        using Commerce.Runtime.DataModel;
        using Retail.StoreServerServiceLibrary;
    
        [ComVisible(false)]
        [ExtendedController("Values")]
        [CommerceAuthorization(AllowedRetailRoles = new string[] { CommerceRoles.Anonymous }, CheckRetailOperation = false)]
        public class ValuesController : ApiController
        {
            // GET /api/values
            public IEnumerable<string> Get()
            {
                return new string[] { "value1", "value2" };
            }
        }
    }

To create the controller, you need to create a new class that uses the Export attribute and specify that the type is the IWebApiConfig interface. The IWebApiConfig interface has one method you can override called Register. After you override the Register method, you can call the base class to get the same mapping as an OData metadata controller.

You must derive from the standard web API controller, and then you can customize the controller to meet your business needs. For more information, see [ASP.NET Web API](https://msdn.microsoft.com/library/hh833994\(v=vs.108\).aspx).

## See also

[Retail Modern Point of Sale](retail-modern-point-of-sale.md)

  


