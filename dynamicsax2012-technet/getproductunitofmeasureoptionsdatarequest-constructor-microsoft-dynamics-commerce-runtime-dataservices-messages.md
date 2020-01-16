---
title: GetProductUnitOfMeasureOptionsDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetProductUnitOfMeasureOptionsDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductUnitOfMeasureOptionsDataRequest.#ctor(System.Collections.Generic.IEnumerable{System.Int64},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductunitofmeasureoptionsdatarequest.getproductunitofmeasureoptionsdatarequest(v=AX.60)
ms:contentKeyID: 65316113
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductUnitOfMeasureOptionsDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetProductUnitOfMeasureOptionsDataRequest Constructor

Initializes a new instance of the [GetProductUnitOfMeasureOptionsDataRequest](getproductunitofmeasureoptionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    productIds As IEnumerable(Of Long), _
    queryResultSettings As QueryResultSettings _
)
'Usage
Dim productIds As IEnumerable(Of Long)
Dim queryResultSettings As QueryResultSettings

Dim instance As New GetProductUnitOfMeasureOptionsDataRequest(productIds, _
    queryResultSettings)
```

``` csharp
public GetProductUnitOfMeasureOptionsDataRequest(
    IEnumerable<long> productIds,
    QueryResultSettings queryResultSettings
)
```

``` c++
public:
GetProductUnitOfMeasureOptionsDataRequest(
    IEnumerable<long long>^ productIds, 
    QueryResultSettings^ queryResultSettings
)
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - queryResultSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetProductUnitOfMeasureOptionsDataRequest Class](getproductunitofmeasureoptionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

