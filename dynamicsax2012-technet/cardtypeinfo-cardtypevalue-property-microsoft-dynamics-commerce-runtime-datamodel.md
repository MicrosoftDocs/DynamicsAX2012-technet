---
title: CardTypeInfo.CardTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CardTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo.CardTypeValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cardtypeinfo.cardtypevalue(v=AX.60)
ms:contentKeyID: 62210162
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo.CardTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# CardTypeValue Property

Gets or sets the value of the CardType enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CardTypeValue As Integer
    Get
    Set
'Usage
Dim instance As CardTypeInfo
Dim value As Integer

value = instance.CardTypeValue

instance.CardTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int CardTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int CardTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[CardTypeInfo Class](cardtypeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

