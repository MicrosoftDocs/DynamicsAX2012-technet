---
title: ReasonSubCode.TriggerFunctionType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TriggerFunctionType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.TriggerFunctionType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasonsubcode.triggerfunctiontype(v=AX.60)
ms:contentKeyID: 62209189
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.TriggerFunctionType
dev_langs:
- CSharp
- C++
- VB
---

# TriggerFunctionType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the type of the trigger function.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TRIGGERFUNCTION")> _
Public Property TriggerFunctionType As TriggerFunctionType
    Get
    Friend Set
'Usage
Dim instance As ReasonSubCode
Dim value As TriggerFunctionType

value = instance.TriggerFunctionType
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TRIGGERFUNCTION")]
public TriggerFunctionType TriggerFunctionType { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TRIGGERFUNCTION")]
public:
property TriggerFunctionType TriggerFunctionType {
    TriggerFunctionType get ();
    internal: void set (TriggerFunctionType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TriggerFunctionType](triggerfunctiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The type of the trigger function.  

## See Also

#### Reference

[ReasonSubCode Class](reasonsubcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

