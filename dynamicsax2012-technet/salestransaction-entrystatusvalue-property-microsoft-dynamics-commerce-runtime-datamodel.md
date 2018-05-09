---
title: SalesTransaction.EntryStatusValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EntryStatusValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.EntryStatusValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.entrystatusvalue(v=AX.60)
ms:contentKeyID: 62209585
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.EntryStatusValue
dev_langs:
- CSharp
- C++
- VB
---

# EntryStatusValue Property

Gets or sets the value of the EntryStatus. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EntryStatusValue As Integer
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Integer

value = instance.EntryStatusValue

instance.EntryStatusValue = value
```

``` csharp
[DataMemberAttribute]
public int EntryStatusValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int EntryStatusValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

