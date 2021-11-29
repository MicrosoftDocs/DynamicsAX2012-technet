---
title: GetProductKitDataRequest.KitMasterProductIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: KitMasterProductIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductKitDataRequest.KitMasterProductIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductkitdatarequest.kitmasterproductids(v=AX.60)
ms:contentKeyID: 65320579
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductKitDataRequest.KitMasterProductIds
dev_langs:
- CSharp
- C++
- VB
---

# KitMasterProductIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of product identifiers for the kit masters.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property KitMasterProductIds As IEnumerable(Of Long)
    Get
    Private Set
'Usage
Dim instance As GetProductKitDataRequest
Dim value As IEnumerable(Of Long)

value = instance.KitMasterProductIds
```

``` csharp
public IEnumerable<long> KitMasterProductIds { get; private set; }
```

``` c++
public:
property IEnumerable<long long>^ KitMasterProductIds {
    IEnumerable<long long>^ get ();
    private: void set (IEnumerable<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetProductKitDataRequest Class](getproductkitdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

