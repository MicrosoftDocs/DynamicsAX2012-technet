---
title: ChargeLine.Value Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Value Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.Value
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeline.value(v=AX.60)
ms:contentKeyID: 49824371
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.Value
dev_langs:
- CSharp
- C++
- VB
---

# Value Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the charge line value to be used with the charge method.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("VALUE")> _
Public Property Value As Decimal
    Get
    Set
'Usage
Dim instance As ChargeLine
Dim value As Decimal

value = instance.Value

instance.Value = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("VALUE")]
public decimal Value { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"VALUE")]
public:
property Decimal Value {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The value.  

## Remarks

This value can mean different things depending on which charge method is being used by this line.

## See Also

#### Reference

[ChargeLine Class](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

