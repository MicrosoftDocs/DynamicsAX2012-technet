---
title: Create a new Retail Server Controller
TOCTitle: Create a new Retail Server Controller
ms:assetid: edc1a279-914b-49c3-90b6-84173e2f828d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn741461(v=AX.60)
ms:contentKeyID: 62219737
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Create a new Retail Server Controller [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

A controller in Microsoft Dynamics AX for Retail is a mapping for a commerce entity that controls CRUD behaviors and actions for a commerce entity type. Each commerce entity must have a corresponding controller. If you introduce your own entity type, you must create a new controller.

The following example demonstrates how to create a new entity and then create a controller for the new entity.


> [!NOTE]
> <P>You can find the sample code from this topic in the Retail SDK.</P>



## Create a new entity

For a new entity, define a class. The class must have a key field. In the following example, there are two properties called Name and Id. Id is the key field.

    namespace Microsoft.Dynamics.RetailServer.Samples.Extensions
    {
        using System.ComponentModel.DataAnnotations;
    
        public class NewEntity
        {
            public string Name { get; set; }
    
            [Key]
            public string Id { get; set; }
        }
    }

## Create a controller for the new entity

After you create the new entity, you must define a new controller for it. In the following example, the controller class extends the CommerceController class and takes the entity type and the key field of the entity type you created as parameters. There is one method called get that uses OData to return a collection of the NewEntity entities that are associated with the NewEntitiesController controller.

    namespace Microsoft.Dynamics.RetailServer.Samples.Extensions
    {
        using System.Collections.Generic;
        using System.Linq;
        using System.Runtime.InteropServices;
        using Retail.StoreServerServiceLibrary.ODataControllers;
    
        [ComVisible(false)]
        public class NewEntitiesController : CommerceController<NewEntity, string>
        {
            public override System.Linq.IQueryable<NewEntity> Get()
            {
                List<NewEntity> newEntities = new List<NewEntity>();
    
                for (int i = 0; i < 10; i++)
                {
                    var newEntity = new NewEntity();
                    newEntity.Id = "Id" + i;
                    newEntity.Name = "Name" + i;
    
                    newEntities.Add(newEntity);
                }
    
                return newEntities.AsQueryable();
            }
        }
    }

## See also

[Retail Modern Point of Sale](retail-modern-point-of-sale.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

