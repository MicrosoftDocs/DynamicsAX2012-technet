---
title: AddressFormattingInfo.Expand Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Expand Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.Expand
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.addressformattinginfo.expand(v=AX.60)
ms:contentKeyID: 65321904
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.Expand
dev_langs:
- CSharp
- C++
- VB
---

# Expand Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EXPAND")> _
<DataMemberAttribute> _
Public Property Expand As Boolean
    Get
    Set
'Usage
Dim instance As AddressFormattingInfo
Dim value As Boolean

value = instance.Expand

instance.Expand = value
```

``` csharp
[ColumnAttribute("EXPAND")]
[DataMemberAttribute]
public bool Expand { get; set; }
```

``` c++
[ColumnAttribute(L"EXPAND")]
[DataMemberAttribute]
public:
property bool Expand {
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

