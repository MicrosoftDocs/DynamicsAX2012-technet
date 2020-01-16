---
title: HardwareProfile.KeyboardMappingId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KeyboardMappingId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.KeyboardMappingId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.keyboardmappingid(v=AX.60)
ms:contentKeyID: 62204511
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.KeyboardMappingId
dev_langs:
- CSharp
- C++
- VB
---

# KeyboardMappingId Property

Gets or sets the keyboard mapping identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("KEYBOARDMAPPINGID")> _
<DataMemberAttribute> _
Public Property KeyboardMappingId As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.KeyboardMappingId

instance.KeyboardMappingId = value
```

``` csharp
[ColumnAttribute("KEYBOARDMAPPINGID")]
[DataMemberAttribute]
public string KeyboardMappingId { get; set; }
```

``` c++
[ColumnAttribute(L"KEYBOARDMAPPINGID")]
[DataMemberAttribute]
public:
property String^ KeyboardMappingId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The mapping identifier.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

