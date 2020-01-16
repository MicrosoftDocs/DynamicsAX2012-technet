---
title: SalesTransactionData.ByteLength Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ByteLength Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData.ByteLength
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransactiondata.bytelength(v=AX.60)
ms:contentKeyID: 62210957
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData.ByteLength
dev_langs:
- CSharp
- C++
- VB
---

# ByteLength Property

Gets or sets the length of the data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("BYTELENGTH")> _
<IgnoreDataMemberAttribute> _
Public Property ByteLength As Long
    Get
    Set
'Usage
Dim instance As SalesTransactionData
Dim value As Long

value = instance.ByteLength

instance.ByteLength = value
```

``` csharp
[ColumnAttribute("BYTELENGTH")]
[IgnoreDataMemberAttribute]
public long ByteLength { get; set; }
```

``` c++
[ColumnAttribute(L"BYTELENGTH")]
[IgnoreDataMemberAttribute]
public:
property long long ByteLength {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransactionData Class](salestransactiondata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

