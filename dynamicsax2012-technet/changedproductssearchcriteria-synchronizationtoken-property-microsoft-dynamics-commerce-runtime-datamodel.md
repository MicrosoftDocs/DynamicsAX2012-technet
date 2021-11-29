---
title: ChangedProductsSearchCriteria.SynchronizationToken Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SynchronizationToken Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchCriteria.SynchronizationToken
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.changedproductssearchcriteria.synchronizationtoken(v=AX.60)
ms:contentKeyID: 62209748
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchCriteria.SynchronizationToken
dev_langs:
- CSharp
- C++
- VB
---

# SynchronizationToken Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SynchronizationToken As Char()
    Get
    Set
'Usage
Dim instance As ChangedProductsSearchCriteria
Dim value As Char()

value = instance.SynchronizationToken

instance.SynchronizationToken = value
```

``` csharp
[DataMemberAttribute]
public char[] SynchronizationToken { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property array<wchar_t>^ SynchronizationToken {
    array<wchar_t>^ get ();
    void set (array<wchar_t>^ value);
}
```

#### Property Value

Type: [System.Char](https://technet.microsoft.com/library/k493b04s\(v=ax.60\))\[\]  

## See Also

#### Reference

[ChangedProductsSearchCriteria Class](changedproductssearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

