---
title: Shift.RowVersion Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RowVersion Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.RowVersion
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shift.rowversion(v=AX.60)
ms:contentKeyID: 65322150
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.RowVersion
dev_langs:
- CSharp
- C++
- VB
---

# RowVersion Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ROWVERSION")> _
<IgnoreDataMemberAttribute> _
Public Property RowVersion As Byte()
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Byte()

value = instance.RowVersion

instance.RowVersion = value
```

``` csharp
[ColumnAttribute("ROWVERSION")]
[IgnoreDataMemberAttribute]
public byte[] RowVersion { get; set; }
```

``` c++
[ColumnAttribute(L"ROWVERSION")]
[IgnoreDataMemberAttribute]
public:
property array<unsigned char>^ RowVersion {
    array<unsigned char>^ get ();
    void set (array<unsigned char>^ value);
}
```

#### Property Value

Type: [System.Byte](https://technet.microsoft.com/en-us/library/yyb1w04y\(v=ax.60\))\[\]  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

