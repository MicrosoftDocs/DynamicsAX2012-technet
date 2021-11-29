---
title: ReadChangedProductsSession.NumberOfProductsRead Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NumberOfProductsRead Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession.NumberOfProductsRead
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.readchangedproductssession.numberofproductsread(v=AX.60)
ms:contentKeyID: 62207941
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession.NumberOfProductsRead
dev_langs:
- CSharp
- C++
- VB
---

# NumberOfProductsRead Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets total number of products which was read in this session so far.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NumberOfProductsRead As Integer
    Get
    Set
'Usage
Dim instance As ReadChangedProductsSession
Dim value As Integer

value = instance.NumberOfProductsRead

instance.NumberOfProductsRead = value
```

``` csharp
[DataMemberAttribute]
public int NumberOfProductsRead { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int NumberOfProductsRead {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ReadChangedProductsSession Class](readchangedproductssession-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

