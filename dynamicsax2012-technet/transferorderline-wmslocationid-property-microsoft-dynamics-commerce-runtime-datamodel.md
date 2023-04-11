---
title: TransferOrderLine.WMSLocationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: WMSLocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.WMSLocationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transferorderline.wmslocationid(v=AX.60)
ms:contentKeyID: 62214786
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.WMSLocationId
dev_langs:
- CSharp
- C++
- VB
---

# WMSLocationId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the WMS location identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property WMSLocationId As String
    Get
    Set
'Usage
Dim instance As TransferOrderLine
Dim value As String

value = instance.WMSLocationId

instance.WMSLocationId = value
```

``` csharp
[DataMemberAttribute]
public string WMSLocationId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ WMSLocationId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TransferOrderLine Class](transferorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

