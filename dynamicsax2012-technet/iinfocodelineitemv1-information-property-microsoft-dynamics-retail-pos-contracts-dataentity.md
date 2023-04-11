---
title: IInfoCodeLineItemV1.Information Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Information Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.Information
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iinfocodelineitemv1.information(v=AX.60)
ms:contentKeyID: 49827733
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.Information
dev_langs:
- CSharp
- C++
- VB
---

# Information Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The information retreived.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Information As String
    Get
    Set
'Usage
Dim instance As IInfoCodeLineItemV1
Dim value As String

value = instance.Information

instance.Information = value
```

``` csharp
string Information { get; set; }
```

``` c++
property String^ Information {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IInfoCodeLineItemV1 Interface](iinfocodelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

