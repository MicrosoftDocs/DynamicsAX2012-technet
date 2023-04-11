---
title: ISaleLineItemV4.ReturnWarehouseText Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ReturnWarehouseText Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV4.ReturnWarehouseText
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv4.returnwarehousetext(v=AX.60)
ms:contentKeyID: 62205327
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV4.ReturnWarehouseText
dev_langs:
- CSharp
- C++
- VB
---

# ReturnWarehouseText Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets warehouse text for printing

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ReturnWarehouseText As String
    Get
    Set
'Usage
Dim instance As ISaleLineItemV4
Dim value As String

value = instance.ReturnWarehouseText

instance.ReturnWarehouseText = value
```

``` csharp
string ReturnWarehouseText { get; set; }
```

``` c++
property String^ ReturnWarehouseText {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV4 Interface](isalelineitemv4-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

