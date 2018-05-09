---
title: SalesTransaction.ChargeCalculableSalesLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeCalculableSalesLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ChargeCalculableSalesLines
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.chargecalculablesaleslines(v=AX.60)
ms:contentKeyID: 62203498
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ChargeCalculableSalesLines
dev_langs:
- CSharp
- C++
- VB
---

# ChargeCalculableSalesLines Property

Gets the sales lines that needs to be included in the charge calculations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property ChargeCalculableSalesLines As ReadOnlyCollection(Of SalesLine)
    Get
'Usage
Dim instance As SalesTransaction
Dim value As ReadOnlyCollection(Of SalesLine)

value = instance.ChargeCalculableSalesLines
```

``` csharp
[IgnoreDataMemberAttribute]
public ReadOnlyCollection<SalesLine> ChargeCalculableSalesLines { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ReadOnlyCollection<SalesLine^>^ ChargeCalculableSalesLines {
    ReadOnlyCollection<SalesLine^>^ get ();
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

