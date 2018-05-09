---
title: ProductRefinerValue.RightValueBoundString Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RightValueBoundString Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue.RightValueBoundString
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productrefinervalue.rightvalueboundstring(v=AX.60)
ms:contentKeyID: 65317332
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue.RightValueBoundString
dev_langs:
- CSharp
- C++
- VB
---

# RightValueBoundString Property

Gets or sets the value of the RightValueBound.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RightValueBoundString As String
    Get
    Set
'Usage
Dim instance As ProductRefinerValue
Dim value As String

value = instance.RightValueBoundString

instance.RightValueBoundString = value
```

``` csharp
[DataMemberAttribute]
public string RightValueBoundString { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ RightValueBoundString {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductRefinerValue Class](productrefinervalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

