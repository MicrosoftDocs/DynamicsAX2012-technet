---
title: ContactInfo.LogisticsLocationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LogisticsLocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.LogisticsLocationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.contactinfo.logisticslocationid(v=AX.60)
ms:contentKeyID: 62213580
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.LogisticsLocationId
dev_langs:
- CSharp
- C++
- VB
---

# LogisticsLocationId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the logistics location identifier for an contact info.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LOGISTICSLOCATIONID")> _
<DataMemberAttribute> _
Public Property LogisticsLocationId As String
    Get
    Set
'Usage
Dim instance As ContactInfo
Dim value As String

value = instance.LogisticsLocationId

instance.LogisticsLocationId = value
```

``` csharp
[ColumnAttribute("LOGISTICSLOCATIONID")]
[DataMemberAttribute]
public string LogisticsLocationId { get; set; }
```

``` c++
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
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ContactInfo Class](contactinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

