---
title: GetProductCatalogAssociationsDataRequest.ProductIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ProductIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductCatalogAssociationsDataRequest.ProductIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductcatalogassociationsdatarequest.productids(v=AX.60)
ms:contentKeyID: 65322450
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductCatalogAssociationsDataRequest.ProductIds
dev_langs:
- CSharp
- C++
- VB
---

# ProductIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the product identifiers that will be used for catalog search.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductIds As IEnumerable(Of Long)
    Get
    Private Set
'Usage
Dim instance As GetProductCatalogAssociationsDataRequest
Dim value As IEnumerable(Of Long)

value = instance.ProductIds
```

``` csharp
[DataMemberAttribute]
public IEnumerable<long> ProductIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<long long>^ ProductIds {
    IEnumerable<long long>^ get ();
    private: void set (IEnumerable<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetProductCatalogAssociationsDataRequest Class](getproductcatalogassociationsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

