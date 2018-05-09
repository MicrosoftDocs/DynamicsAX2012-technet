---
title: ProductRefiner.DisplayTemplateValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DisplayTemplateValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.DisplayTemplateValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productrefiner.displaytemplatevalue(v=AX.60)
ms:contentKeyID: 65317151
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.DisplayTemplateValue
dev_langs:
- CSharp
- C++
- VB
---

# DisplayTemplateValue Property

Gets or sets the value of the display template enumeration. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DisplayTemplateValue As Integer
    Get
    Set
'Usage
Dim instance As ProductRefiner
Dim value As Integer

value = instance.DisplayTemplateValue

instance.DisplayTemplateValue = value
```

``` csharp
[DataMemberAttribute]
public int DisplayTemplateValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int DisplayTemplateValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ProductRefiner Class](productrefiner-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

