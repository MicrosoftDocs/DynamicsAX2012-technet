---
title: GetOrdersServiceRequest.Criteria Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Criteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetOrdersServiceRequest.Criteria
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getordersservicerequest.criteria(v=AX.60)
ms:contentKeyID: 62211510
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetOrdersServiceRequest.Criteria
dev_langs:
- CSharp
- C++
- VB
---

# Criteria Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the criteria to search for.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Criteria As SalesOrderSearchCriteria
    Get
    Set
'Usage
Dim instance As GetOrdersServiceRequest
Dim value As SalesOrderSearchCriteria

value = instance.Criteria

instance.Criteria = value
```

``` csharp
[DataMemberAttribute]
public SalesOrderSearchCriteria Criteria { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property SalesOrderSearchCriteria^ Criteria {
    SalesOrderSearchCriteria^ get ();
    void set (SalesOrderSearchCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesOrderSearchCriteria](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetOrdersServiceRequest Class](getordersservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

