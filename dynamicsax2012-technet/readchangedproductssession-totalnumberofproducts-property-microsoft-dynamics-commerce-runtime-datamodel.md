---
title: ReadChangedProductsSession.TotalNumberOfProducts Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TotalNumberOfProducts Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession.TotalNumberOfProducts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.readchangedproductssession.totalnumberofproducts(v=AX.60)
ms:contentKeyID: 62214892
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession.TotalNumberOfProducts
dev_langs:
- CSharp
- C++
- VB
---

# TotalNumberOfProducts Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets total number of products which can be read in this session.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TotalNumberOfProducts As Integer
    Get
    Private Set
'Usage
Dim instance As ReadChangedProductsSession
Dim value As Integer

value = instance.TotalNumberOfProducts
```

``` csharp
[DataMemberAttribute]
public int TotalNumberOfProducts { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property int TotalNumberOfProducts {
    int get ();
    private: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ReadChangedProductsSession Class](readchangedproductssession-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

