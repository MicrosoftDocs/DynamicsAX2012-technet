---
title: SalesTransaction.TenderLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.TenderLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.tenderlines(v=AX.60)
ms:contentKeyID: 62206024
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.TenderLines
dev_langs:
- CSharp
- C++
- VB
---

# TenderLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tender lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderLines As Collection(Of TenderLine)
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Collection(Of TenderLine)

value = instance.TenderLines

instance.TenderLines = value
```

``` csharp
[DataMemberAttribute]
public Collection<TenderLine> TenderLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<TenderLine^>^ TenderLines {
    Collection<TenderLine^>^ get ();
    void set (Collection<TenderLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

