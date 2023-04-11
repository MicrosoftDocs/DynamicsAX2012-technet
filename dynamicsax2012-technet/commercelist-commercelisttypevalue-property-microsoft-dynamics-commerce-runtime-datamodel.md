---
title: CommerceList.CommerceListTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CommerceListTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList.CommerceListTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercelist.commercelisttypevalue(v=AX.60)
ms:contentKeyID: 62214682
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList.CommerceListTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# CommerceListTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the commerce list type value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CommerceListTypeValue As Integer
    Get
    Set
'Usage
Dim instance As CommerceList
Dim value As Integer

value = instance.CommerceListTypeValue

instance.CommerceListTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int CommerceListTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int CommerceListTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[CommerceList Class](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

