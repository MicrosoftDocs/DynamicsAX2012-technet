---
title: ReasonSubCode.TriggerFunctionTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TriggerFunctionTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.TriggerFunctionTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasonsubcode.triggerfunctiontypevalue(v=AX.60)
ms:contentKeyID: 62208711
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.TriggerFunctionTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# TriggerFunctionTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the TriggerFunctionType enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TriggerFunctionTypeValue As Integer
    Get
    Set
'Usage
Dim instance As ReasonSubCode
Dim value As Integer

value = instance.TriggerFunctionTypeValue

instance.TriggerFunctionTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int TriggerFunctionTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int TriggerFunctionTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ReasonSubCode Class](reasonsubcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

