---
title: Extend a Retail Server OData Controller
TOCTitle: Extend a Retail Server OData Controller
ms:assetid: 5ce0f87f-885d-4c0e-bed7-adfaf94b2c0b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn741447(v=AX.60)
ms:contentKeyID: 62219724
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Extend a Retail Server OData Controller [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

A controller is a mapping for a commerce entity that controls CRUD behaviors and actions for a commerce entity type. Each commerce entity must have a corresponding controller. You can extend a controller that comes with Microsoft Dynamics AX to add new business actions to fulfill business needs.


> [!NOTE]
> <P>You can find the sample code from this topic in the Retail SDK.</P>



## Extend the Customer controller

To extend an existing controller, you need to define a new class that extends an existing controller class. In the new class, you use the ExtendedController attribute to indicate that the new class extends an existing controller, and to indicate which controller it extends. In this example, the new class extends the controller for the Customer entity type. Each entity type is associated with only one controller. When you create a new controller that overrides an existing controller, the new controller that has the ExtendedController attribute is used instead of the original controller.

In the following example, the ExtendedCustomersController class extends the CustomersController class and takes the entity type and the key field of the Customers entity type as parameters.

    namespace Microsoft.Dynamics.RetailServer.ExtensionSamples
    {
        using System;
        using System.Collections.Generic;
        using System.Linq;
        using System.Runtime.InteropServices;
        using Microsoft.Dynamics.Commerce.Runtime.DataModel;
        using Microsoft.Dynamics.Retail.StoreServerServiceLibrary;
        using Microsoft.Dynamics.Retail.StoreServerServiceLibrary.ODataControllers;
    
        [ExtendedController("Customers")]
        [ComVisible(false)]
        public class ExtendedCustomersController : CustomersController
        {
            public override IQueryable<Customer> Get()
            {
                List<Customer> customers = new List<Customer>();
    
                for (int i = 0; i < 10; i++)
                {
                    var customer = new Customer();
                    customer.AccountNumber = "customer" + i;
                    customer.Name = "Name" + i;
                    
                    customers.Add(customer);
                }
    
                return customers.AsQueryable();
            }
        }
    }

## See also

[Retail Modern Point of Sale](retail-modern-point-of-sale.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

