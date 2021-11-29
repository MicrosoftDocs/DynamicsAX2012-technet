---
title: PurchaseOrderLine.DeliveryMethod Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveryMethod Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.DeliveryMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.purchaseorderline.deliverymethod(v=AX.60)
ms:contentKeyID: 62212606
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.DeliveryMethod
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryMethod Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the delivery method.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DELIVERYMETHOD")> _
<DataMemberAttribute> _
Public Property DeliveryMethod As String
    Get
    Set
'Usage
Dim instance As PurchaseOrderLine
Dim value As String

value = instance.DeliveryMethod

instance.DeliveryMethod = value
```

``` csharp
[ColumnAttribute("DELIVERYMETHOD")]
[DataMemberAttribute]
public string DeliveryMethod { get; set; }
```

``` c++
[ColumnAttribute(L"DELIVERYMETHOD")]
[DataMemberAttribute]
public:
property String^ DeliveryMethod {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PurchaseOrderLine Class](purchaseorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

