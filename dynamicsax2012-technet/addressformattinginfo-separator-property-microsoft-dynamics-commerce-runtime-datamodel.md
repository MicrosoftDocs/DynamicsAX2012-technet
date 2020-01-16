---
title: AddressFormattingInfo.Separator Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Separator Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.Separator
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.addressformattinginfo.separator(v=AX.60)
ms:contentKeyID: 65321981
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.Separator
dev_langs:
- CSharp
- C++
- VB
---

# Separator Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SEPARATOR")> _
<DataMemberAttribute> _
Public Property Separator As String
    Get
    Set
'Usage
Dim instance As AddressFormattingInfo
Dim value As String

value = instance.Separator

instance.Separator = value
```

``` csharp
[ColumnAttribute("SEPARATOR")]
[DataMemberAttribute]
public string Separator { get; set; }
```

``` c++
[ColumnAttribute(L"SEPARATOR")]
[DataMemberAttribute]
public:
property String^ Separator {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[AddressFormattingInfo Class](addressformattinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

