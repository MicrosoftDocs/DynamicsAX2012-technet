---
title: SalesTransaction.SalesLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.SalesLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.saleslines(v=AX.60)
ms:contentKeyID: 49831787
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.SalesLines
dev_langs:
- CSharp
- C++
- VB
---

# SalesLines Property

Gets or sets the sales lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesLines As Collection(Of SalesLine)
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Collection(Of SalesLine)

value = instance.SalesLines

instance.SalesLines = value
```

``` csharp
[DataMemberAttribute]
public Collection<SalesLine> SalesLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<SalesLine^>^ SalesLines {
    Collection<SalesLine^>^ get ();
    void set (Collection<SalesLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

