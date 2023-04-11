---
title: CartLine.SalesStatusValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesStatusValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.SalesStatusValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.salesstatusvalue(v=AX.60)
ms:contentKeyID: 65315976
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.SalesStatusValue
dev_langs:
- CSharp
- C++
- VB
---

# SalesStatusValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesStatusValue As Integer
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As Integer

value = instance.SalesStatusValue

instance.SalesStatusValue = value
```

``` csharp
[DataMemberAttribute]
public int SalesStatusValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int SalesStatusValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

