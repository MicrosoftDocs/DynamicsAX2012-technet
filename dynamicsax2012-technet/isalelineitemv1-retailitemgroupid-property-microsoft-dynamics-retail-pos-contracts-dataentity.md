---
title: ISaleLineItemV1.RetailItemGroupId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: RetailItemGroupId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.RetailItemGroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.retailitemgroupid(v=AX.60)
ms:contentKeyID: 49835781
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.RetailItemGroupId
dev_langs:
- CSharp
- C++
- VB
---

# RetailItemGroupId Property

**Note: This API is now obsolete.**

The retail group of the item.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("Value is no longer used")> _
Property RetailItemGroupId As String
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As String

value = instance.RetailItemGroupId

instance.RetailItemGroupId = value
```

``` csharp
[ObsoleteAttribute("Value is no longer used")]
string RetailItemGroupId { get; set; }
```

``` c++
[ObsoleteAttribute(L"Value is no longer used")]
property String^ RetailItemGroupId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

