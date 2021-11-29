---
title: AddressFormattingInfo.Inactive Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Inactive Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.Inactive
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.addressformattinginfo.inactive(v=AX.60)
ms:contentKeyID: 65321320
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.Inactive
dev_langs:
- CSharp
- C++
- VB
---

# Inactive Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INACTIVE")> _
<DataMemberAttribute> _
Public Property Inactive As Boolean
    Get
    Set
'Usage
Dim instance As AddressFormattingInfo
Dim value As Boolean

value = instance.Inactive

instance.Inactive = value
```

``` csharp
[ColumnAttribute("INACTIVE")]
[DataMemberAttribute]
public bool Inactive { get; set; }
```

``` c++
[ColumnAttribute(L"INACTIVE")]
[DataMemberAttribute]
public:
property bool Inactive {
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

