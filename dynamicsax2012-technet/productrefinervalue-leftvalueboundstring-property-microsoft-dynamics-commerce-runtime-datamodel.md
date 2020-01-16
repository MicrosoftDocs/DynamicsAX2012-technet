---
title: ProductRefinerValue.LeftValueBoundString Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LeftValueBoundString Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue.LeftValueBoundString
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrefinervalue.leftvalueboundstring(v=AX.60)
ms:contentKeyID: 65321125
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue.LeftValueBoundString
dev_langs:
- CSharp
- C++
- VB
---

# LeftValueBoundString Property

Gets or sets the value of the LeftValueBound.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LeftValueBoundString As String
    Get
    Set
'Usage
Dim instance As ProductRefinerValue
Dim value As String

value = instance.LeftValueBoundString

instance.LeftValueBoundString = value
```

``` csharp
[DataMemberAttribute]
public string LeftValueBoundString { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ LeftValueBoundString {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductRefinerValue Class](productrefinervalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

