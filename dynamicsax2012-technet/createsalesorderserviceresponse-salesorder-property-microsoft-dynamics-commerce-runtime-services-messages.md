---
title: CreateSalesOrderServiceResponse.SalesOrder Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SalesOrder Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateSalesOrderServiceResponse.SalesOrder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.createsalesorderserviceresponse.salesorder(v=AX.60)
ms:contentKeyID: 62208063
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateSalesOrderServiceResponse.SalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrder Property

Gets the sales order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesOrder As SalesOrder
    Get
    Private Set
'Usage
Dim instance As CreateSalesOrderServiceResponse
Dim value As SalesOrder

value = instance.SalesOrder
```

``` csharp
[DataMemberAttribute]
public SalesOrder SalesOrder { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property SalesOrder^ SalesOrder {
    SalesOrder^ get ();
    private: void set (SalesOrder^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The sales order.  

## See Also

#### Reference

[CreateSalesOrderServiceResponse Class](createsalesorderserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

