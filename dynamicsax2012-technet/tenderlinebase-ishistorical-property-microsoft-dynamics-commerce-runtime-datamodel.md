---
title: TenderLineBase.IsHistorical Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsHistorical Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.IsHistorical
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.ishistorical(v=AX.60)
ms:contentKeyID: 62213452
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.IsHistorical
dev_langs:
- CSharp
- C++
- VB
---

# IsHistorical Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether this instance is a historical line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsHistorical As Boolean
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As Boolean

value = instance.IsHistorical

instance.IsHistorical = value
```

``` csharp
[DataMemberAttribute]
public bool IsHistorical { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsHistorical {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true this tender line is a historical line; otherwise, false.  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

