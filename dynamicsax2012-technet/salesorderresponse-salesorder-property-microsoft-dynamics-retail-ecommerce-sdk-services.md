---
title: SalesOrderResponse.SalesOrder Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: SalesOrder Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.SalesOrderResponse.SalesOrder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.salesorderresponse.salesorder(v=AX.60)
ms:contentKeyID: 65317125
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.SalesOrderResponse.SalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrder Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesOrder As SalesOrder
    Get
    Set
'Usage
Dim instance As SalesOrderResponse
Dim value As SalesOrder

value = instance.SalesOrder

instance.SalesOrder = value
```

``` csharp
[DataMemberAttribute]
public SalesOrder SalesOrder { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property SalesOrder^ SalesOrder {
    SalesOrder^ get ();
    void set (SalesOrder^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SalesOrder](salesorder-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[SalesOrderResponse Class](salesorderresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

