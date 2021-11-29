---
title: SalesTransactionData.Version Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Version Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData.Version
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransactiondata.version(v=AX.60)
ms:contentKeyID: 62213375
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData.Version
dev_langs:
- CSharp
- C++
- VB
---

# Version Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the SQL row version.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ROWVERSION")> _
<IgnoreDataMemberAttribute> _
Public Property Version As Byte()
    Get
    Set
'Usage
Dim instance As SalesTransactionData
Dim value As Byte()

value = instance.Version

instance.Version = value
```

``` csharp
[ColumnAttribute("ROWVERSION")]
[IgnoreDataMemberAttribute]
public byte[] Version { get; set; }
```

``` c++
[ColumnAttribute(L"ROWVERSION")]
[IgnoreDataMemberAttribute]
public:
property array<unsigned char>^ Version {
    array<unsigned char>^ get ();
    void set (array<unsigned char>^ value);
}
```

#### Property Value

Type: [System.Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))\[\]  
Returns [Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransactionData Class](salestransactiondata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

