---
title: ChargeLine.Keep Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Keep Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.Keep
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeline.keep(v=AX.60)
ms:contentKeyID: 62209815
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.Keep
dev_langs:
- CSharp
- C++
- VB
---

# Keep Property

Gets or sets Keep Flag.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Keep As Integer
    Get
    Set
'Usage
Dim instance As ChargeLine
Dim value As Integer

value = instance.Keep

instance.Keep = value
```

``` csharp
[DataMemberAttribute]
public int Keep { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int Keep {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## Remarks

Indicates whether needs to keep charges transaction after invocing.

## See Also

#### Reference

[ChargeLine Class](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

