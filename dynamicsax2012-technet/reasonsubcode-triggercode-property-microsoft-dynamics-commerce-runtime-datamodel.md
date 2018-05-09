---
title: ReasonSubCode.TriggerCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TriggerCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.TriggerCode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasonsubcode.triggercode(v=AX.60)
ms:contentKeyID: 62211260
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.TriggerCode
dev_langs:
- CSharp
- C++
- VB
---

# TriggerCode Property

Gets the trigger code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TRIGGERCODE")> _
Public Property TriggerCode As String
    Get
    Friend Set
'Usage
Dim instance As ReasonSubCode
Dim value As String

value = instance.TriggerCode
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TRIGGERCODE")]
public string TriggerCode { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TRIGGERCODE")]
public:
property String^ TriggerCode {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The trigger code.  

## See Also

#### Reference

[ReasonSubCode Class](reasonsubcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

