---
title: Address.LogisticsLocationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LogisticsLocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.LogisticsLocationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.logisticslocationid(v=AX.60)
ms:contentKeyID: 62212341
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.LogisticsLocationId
dev_langs:
- CSharp
- C++
- VB
---

# LogisticsLocationId Property

Gets or sets the logistics location identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ReadOnlyAttribute("LOGISTICSLOCATIONID")> _
<ColumnAttribute("LOGISTICSLOCATIONID")> _
<DataMemberAttribute> _
Public Property LogisticsLocationId As String
    Get
    Set
'Usage
Dim instance As Address
Dim value As String

value = instance.LogisticsLocationId

instance.LogisticsLocationId = value
```

``` csharp
[ReadOnlyAttribute("LOGISTICSLOCATIONID")]
[ColumnAttribute("LOGISTICSLOCATIONID")]
[DataMemberAttribute]
public string LogisticsLocationId { get; set; }
```

``` c++
[ReadOnlyAttribute(L"LOGISTICSLOCATIONID")]
[ColumnAttribute(L"LOGISTICSLOCATIONID")]
[DataMemberAttribute]
public:
property String^ LogisticsLocationId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The logistics location identifier.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

