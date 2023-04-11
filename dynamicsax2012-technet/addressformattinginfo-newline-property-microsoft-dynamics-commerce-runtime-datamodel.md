---
title: AddressFormattingInfo.NewLine Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NewLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.NewLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.addressformattinginfo.newline(v=AX.60)
ms:contentKeyID: 65319803
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.NewLine
dev_langs:
- CSharp
- C++
- VB
---

# NewLine Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SEPARATORCRLF")> _
Public Property NewLine As Boolean
    Get
    Set
'Usage
Dim instance As AddressFormattingInfo
Dim value As Boolean

value = instance.NewLine

instance.NewLine = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SEPARATORCRLF")]
public bool NewLine { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SEPARATORCRLF")]
public:
property bool NewLine {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[AddressFormattingInfo Class](addressformattinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

