---
title: SaveCommerceListServiceRequest.OperationType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: OperationType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCommerceListServiceRequest.OperationType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savecommercelistservicerequest.operationtype(v=AX.60)
ms:contentKeyID: 62208815
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCommerceListServiceRequest.OperationType
dev_langs:
- CSharp
- C++
- VB
---

# OperationType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OperationType As CommerceListOperationType
    Get
    Set
'Usage
Dim instance As SaveCommerceListServiceRequest
Dim value As CommerceListOperationType

value = instance.OperationType

instance.OperationType = value
```

``` csharp
[DataMemberAttribute]
public CommerceListOperationType OperationType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property CommerceListOperationType OperationType {
    CommerceListOperationType get ();
    void set (CommerceListOperationType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListOperationType](commercelistoperationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CommerceListOperationType](commercelistoperationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveCommerceListServiceRequest Class](savecommercelistservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

