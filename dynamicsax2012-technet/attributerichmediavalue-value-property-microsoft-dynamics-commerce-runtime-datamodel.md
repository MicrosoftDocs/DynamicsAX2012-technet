---
title: AttributeRichMediaValue.Value Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Value Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeRichMediaValue.Value
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributerichmediavalue.value(v=AX.60)
ms:contentKeyID: 62213317
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeRichMediaValue.Value
dev_langs:
- CSharp
- C++
- VB
---

# Value Property

Gets or sets the attribute value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Value As RichMediaLocations
    Get
    Set
'Usage
Dim instance As AttributeRichMediaValue
Dim value As RichMediaLocations

value = instance.Value

instance.Value = value
```

``` csharp
[DataMemberAttribute]
public RichMediaLocations Value { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property RichMediaLocations^ Value {
    RichMediaLocations^ get ();
    void set (RichMediaLocations^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RichMediaLocations](richmedialocations-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The value.  

## See Also

#### Reference

[AttributeRichMediaValue Class](attributerichmediavalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

