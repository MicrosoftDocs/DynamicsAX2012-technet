---
title: Product.ChangeTrackingInformation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChangeTrackingInformation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.ChangeTrackingInformation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.changetrackinginformation(v=AX.60)
ms:contentKeyID: 62203411
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.ChangeTrackingInformation
dev_langs:
- CSharp
- C++
- VB
---

# ChangeTrackingInformation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets information regarding the change tracking aspects of the product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChangeTrackingInformation As ProductChangeTrackingInformation
    Get
    Set
'Usage
Dim instance As Product
Dim value As ProductChangeTrackingInformation

value = instance.ChangeTrackingInformation

instance.ChangeTrackingInformation = value
```

``` csharp
[DataMemberAttribute]
public ProductChangeTrackingInformation ChangeTrackingInformation { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ProductChangeTrackingInformation^ ChangeTrackingInformation {
    ProductChangeTrackingInformation^ get ();
    void set (ProductChangeTrackingInformation^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingInformation](productchangetrackinginformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductChangeTrackingInformation](productchangetrackinginformation-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

