---
title: AddressFormattingInfo.IsDataEntryOnly Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsDataEntryOnly Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.IsDataEntryOnly
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.addressformattinginfo.isdataentryonly(v=AX.60)
ms:contentKeyID: 49841345
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.IsDataEntryOnly
dev_langs:
- CSharp
- C++
- VB
---

# IsDataEntryOnly Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether this instance is data entry only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DATAENTRYONLY")> _
<DataMemberAttribute> _
Public Property IsDataEntryOnly As Boolean
    Get
    Set
'Usage
Dim instance As AddressFormattingInfo
Dim value As Boolean

value = instance.IsDataEntryOnly

instance.IsDataEntryOnly = value
```

``` csharp
[ColumnAttribute("DATAENTRYONLY")]
[DataMemberAttribute]
public bool IsDataEntryOnly { get; set; }
```

``` c++
[ColumnAttribute(L"DATAENTRYONLY")]
[DataMemberAttribute]
public:
property bool IsDataEntryOnly {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true this instance is only for data entry; otherwise, False.  

## See Also

#### Reference

[AddressFormattingInfo Class](addressformattinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

