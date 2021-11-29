---
title: ReadChangedProductsSession.NumberOfProductsReadInCurrentPage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NumberOfProductsReadInCurrentPage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession.NumberOfProductsReadInCurrentPage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.readchangedproductssession.numberofproductsreadincurrentpage(v=AX.60)
ms:contentKeyID: 62211396
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession.NumberOfProductsReadInCurrentPage
dev_langs:
- CSharp
- C++
- VB
---

# NumberOfProductsReadInCurrentPage Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets number of products read in current page.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NumberOfProductsReadInCurrentPage As Integer
    Get
    Set
'Usage
Dim instance As ReadChangedProductsSession
Dim value As Integer

value = instance.NumberOfProductsReadInCurrentPage

instance.NumberOfProductsReadInCurrentPage = value
```

``` csharp
[DataMemberAttribute]
public int NumberOfProductsReadInCurrentPage { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int NumberOfProductsReadInCurrentPage {
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

