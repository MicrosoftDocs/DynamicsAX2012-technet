---
title: SaveCustomerServiceRequest.CustomerToSave Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CustomerToSave Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerServiceRequest.CustomerToSave
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savecustomerservicerequest.customertosave(v=AX.60)
ms:contentKeyID: 49841401
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerServiceRequest.CustomerToSave
dev_langs:
- CSharp
- C++
- VB
---

# CustomerToSave Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customer to save.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerToSave As Customer
    Get
    Private Set
'Usage
Dim instance As SaveCustomerServiceRequest
Dim value As Customer

value = instance.CustomerToSave
```

``` csharp
[DataMemberAttribute]
public Customer CustomerToSave { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Customer^ CustomerToSave {
    Customer^ get ();
    private: void set (Customer^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveCustomerServiceRequest Class](savecustomerservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

