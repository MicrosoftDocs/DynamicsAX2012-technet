---
title: ReasonCode.InputTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InputTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.InputTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.inputtypevalue(v=AX.60)
ms:contentKeyID: 62206724
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.InputTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# InputTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the ReasonCodeInputType enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InputTypeValue As Integer
    Get
    Set
'Usage
Dim instance As ReasonCode
Dim value As Integer

value = instance.InputTypeValue

instance.InputTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int InputTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int InputTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

