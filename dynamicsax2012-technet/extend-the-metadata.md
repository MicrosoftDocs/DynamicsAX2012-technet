---
title: Extend the metadata
TOCTitle: Extend the metadata
ms:assetid: e9e6043a-b09d-435b-b212-1d6fda8d0308
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn741458(v=AX.60)
ms:contentKeyID: 62219735
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Extend the metadata 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

When you use OData with Microsoft Dynamics AX for Retail, metadata defines the contract between a client and server. It exposes entity definitions and action definitions, so when you make a change on the server side, you can use a tool on the client side to generate proxy code, reducing maintenance effort for developers. To consume new or changed entities and actions, you must extend the metadata.


> [!NOTE]
> <P>You can find the sample code from this topic in the Retail SDK.</P>



## Extend the metadata

Retail Server has a default metadata controller called CommerceModelFactory. To extend the default controller, you create a new class that uses the Export attribute along with the IEdmModelFactory interface. Then you can add and override existing code. For example, you can add new entity sets, new actions, new complex types, or new exception types.

In the following example, the ExtendedEdmModelFactory class extends the CommerceModelFactory metadata controller and creates a new action called NewAction and a new entity set called NewEntities.

    namespace Microsoft.Dynamics.RetailServer.Samples.Extensions
    {
        using System.ComponentModel.Composition;
        using Microsoft.Dynamics.Retail.StoreServerServiceLibrary;
    
        [Export(typeof(IEdmModelFactory))]
        public class ExtendedEdmModelFactory : CommerceModelFactory
        {
            protected override void BuildNonBindableActions()
            {
                base.BuildNonBindableActions();
    
                var NewAction = BindAction("NewAction");
                NewAction.Returns<string>();
            }
    
            protected override void BuildEntitySets()
            {
                base.BuildEntitySets();
    
                BuildEntitySet<NewEntity>("NewEntities");
            }
        }
    }

## See also

[Retail Modern Point of Sale](retail-modern-point-of-sale.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

