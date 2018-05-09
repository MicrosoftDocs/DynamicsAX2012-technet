---
title: GetProductUnitOfMeasureOptionsDataRequest.ProductIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ProductIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductUnitOfMeasureOptionsDataRequest.ProductIds
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductunitofmeasureoptionsdatarequest.productids(v=AX.60)
ms:contentKeyID: 65319211
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductUnitOfMeasureOptionsDataRequest.ProductIds
dev_langs:
- CSharp
- C++
- VB
---

# ProductIds Property

Gets the collection of product identifiers to retrieve the unit of measure options for.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property ProductIds As IEnumerable(Of Long)
    Get
    Private Set
'Usage
Dim instance As GetProductUnitOfMeasureOptionsDataRequest
Dim value As IEnumerable(Of Long)

value = instance.ProductIds
```

``` csharp
public IEnumerable<long> ProductIds { get; private set; }
```

``` c++
public:
property IEnumerable<long long>^ ProductIds {
    IEnumerable<long long>^ get ();
    private: void set (IEnumerable<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetProductUnitOfMeasureOptionsDataRequest Class](getproductunitofmeasureoptionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

