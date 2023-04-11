---
title: ProductChangeTrackingInformation.RequestedActionValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RequestedActionValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingInformation.RequestedActionValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinginformation.requestedactionvalue(v=AX.60)
ms:contentKeyID: 62209493
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingInformation.RequestedActionValue
dev_langs:
- CSharp
- C++
- VB
---

# RequestedActionValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the PublishingAction enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RequestedActionValue As Integer
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingInformation
Dim value As Integer

value = instance.RequestedActionValue

instance.RequestedActionValue = value
```

``` csharp
[DataMemberAttribute]
public int RequestedActionValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int RequestedActionValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ProductChangeTrackingInformation Class](productchangetrackinginformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

