---
title: Shift.DeclareTenderAmountTotal Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeclareTenderAmountTotal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.DeclareTenderAmountTotal
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shift.declaretenderamounttotal(v=AX.60)
ms:contentKeyID: 62207968
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.DeclareTenderAmountTotal
dev_langs:
- CSharp
- C++
- VB
---

# DeclareTenderAmountTotal Property

Gets or sets total of counted amounts (Closing amounts).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Overridable Property DeclareTenderAmountTotal As Decimal
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Decimal

value = instance.DeclareTenderAmountTotal

instance.DeclareTenderAmountTotal = value
```

``` csharp
[DataMemberAttribute]
public virtual decimal DeclareTenderAmountTotal { get; set; }
```

``` c++
[DataMemberAttribute]
public:
virtual property Decimal DeclareTenderAmountTotal {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

