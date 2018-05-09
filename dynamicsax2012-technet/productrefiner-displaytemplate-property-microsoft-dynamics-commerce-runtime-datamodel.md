---
title: ProductRefiner.DisplayTemplate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DisplayTemplate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.DisplayTemplate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productrefiner.displaytemplate(v=AX.60)
ms:contentKeyID: 65320954
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.DisplayTemplate
dev_langs:
- CSharp
- C++
- VB
---

# DisplayTemplate Property

Gets or sets the UI interface to be displayed while using this refiner.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("DISPLAYTEMPLATE")> _
Public Property DisplayTemplate As DisplayTemplate
    Get
    Set
'Usage
Dim instance As ProductRefiner
Dim value As DisplayTemplate

value = instance.DisplayTemplate

instance.DisplayTemplate = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("DISPLAYTEMPLATE")]
public DisplayTemplate DisplayTemplate { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"DISPLAYTEMPLATE")]
public:
property DisplayTemplate DisplayTemplate {
    DisplayTemplate get ();
    void set (DisplayTemplate value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DisplayTemplate](displaytemplate-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DisplayTemplate](displaytemplate-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductRefiner Class](productrefiner-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

