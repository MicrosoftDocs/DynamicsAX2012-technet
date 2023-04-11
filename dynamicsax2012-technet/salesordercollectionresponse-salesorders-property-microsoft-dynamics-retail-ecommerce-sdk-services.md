---
title: SalesOrderCollectionResponse.SalesOrders Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: SalesOrders Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.SalesOrderCollectionResponse.SalesOrders
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.salesordercollectionresponse.salesorders(v=AX.60)
ms:contentKeyID: 65317988
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.SalesOrderCollectionResponse.SalesOrders
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrders Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesOrders As IEnumerable(Of SalesOrder)
    Get
    Set
'Usage
Dim instance As SalesOrderCollectionResponse
Dim value As IEnumerable(Of SalesOrder)

value = instance.SalesOrders

instance.SalesOrders = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<SalesOrder> SalesOrders { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<SalesOrder^>^ SalesOrders {
    IEnumerable<SalesOrder^>^ get ();
    void set (IEnumerable<SalesOrder^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesOrder](salesorder-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[SalesOrderCollectionResponse Class](salesordercollectionresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

