---
title: AttributeDateTimeOffsetValue.Value Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Value Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDateTimeOffsetValue.Value
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributedatetimeoffsetvalue.value(v=AX.60)
ms:contentKeyID: 62210786
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDateTimeOffsetValue.Value
dev_langs:
- CSharp
- C++
- VB
---

# Value Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the attribute value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Value As DateTimeOffset
    Get
    Set
'Usage
Dim instance As AttributeDateTimeOffsetValue
Dim value As DateTimeOffset

value = instance.Value

instance.Value = value
```

``` csharp
[DataMemberAttribute]
public DateTimeOffset Value { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTimeOffset Value {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
The value.  

## See Also

#### Reference

[AttributeDateTimeOffsetValue Class](attributedatetimeoffsetvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

