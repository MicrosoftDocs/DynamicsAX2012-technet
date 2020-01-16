---
title: ProductPropertySchema.Item Property (Int32) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Item Property (Int32)
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertySchema.Item(System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productpropertyschema.item(v=AX.60)
ms:contentKeyID: 65323163
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Item Property (Int32)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property Item ( _
    propertyIdx As Integer _
) As String
    Get
    Private Set
'Usage
Dim instance As ProductPropertySchema
Dim propertyIdx As Integer
Dim value As String

value = instance.Item(propertyIdx)
```

``` csharp
[IgnoreDataMemberAttribute]
public string this[
    int propertyIdx
] { get; private set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property String^ Item[int propertyIdx] {
    String^ get (int propertyIdx);
    private: void set (int propertyIdx, String^ value);
}
```

#### Parameters

  - propertyIdx  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ProductPropertySchema Class](productpropertyschema-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Item Overload](productpropertyschema-item-property-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

