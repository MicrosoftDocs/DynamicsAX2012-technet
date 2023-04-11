---
title: CartLine.ReasonCodeLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReasonCodeLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.ReasonCodeLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.reasoncodelines(v=AX.60)
ms:contentKeyID: 62215030
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.ReasonCodeLines
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodeLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the reason code lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReasonCodeLines As IList(Of ReasonCodeLine)
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As IList(Of ReasonCodeLine)

value = instance.ReasonCodeLines

instance.ReasonCodeLines = value
```

``` csharp
[DataMemberAttribute]
public IList<ReasonCodeLine> ReasonCodeLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<ReasonCodeLine^>^ ReasonCodeLines {
    IList<ReasonCodeLine^>^ get ();
    void set (IList<ReasonCodeLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[ReasonCodeLine](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The reason code lines.  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

