---
title: CartLine.ChargeLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.ChargeLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.chargelines(v=AX.60)
ms:contentKeyID: 62208096
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.ChargeLines
dev_langs:
- CSharp
- C++
- VB
---

# ChargeLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the charge lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChargeLines As IList(Of ChargeLine)
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As IList(Of ChargeLine)

value = instance.ChargeLines

instance.ChargeLines = value
```

``` csharp
[DataMemberAttribute]
public IList<ChargeLine> ChargeLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<ChargeLine^>^ ChargeLines {
    IList<ChargeLine^>^ get ();
    void set (IList<ChargeLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[ChargeLine](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The charge lines.  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

