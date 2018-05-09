---
title: ProductRefinerValue.RefinerSourceValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RefinerSourceValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue.RefinerSourceValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productrefinervalue.refinersourcevalue(v=AX.60)
ms:contentKeyID: 65321558
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue.RefinerSourceValue
dev_langs:
- CSharp
- C++
- VB
---

# RefinerSourceValue Property

Gets or sets the value of the ProductRefinerSource enumeration. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RefinerSourceValue As Integer
    Get
    Set
'Usage
Dim instance As ProductRefinerValue
Dim value As Integer

value = instance.RefinerSourceValue

instance.RefinerSourceValue = value
```

``` csharp
[DataMemberAttribute]
public int RefinerSourceValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int RefinerSourceValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ProductRefinerValue Class](productrefinervalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

