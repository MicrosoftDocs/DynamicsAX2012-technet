---
title: LineDeliveryPreferenceTypeRecord.SalesLineId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesLineId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDeliveryPreferenceTypeRecord.SalesLineId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.linedeliverypreferencetyperecord.saleslineid(v=AX.60)
ms:contentKeyID: 65320244
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDeliveryPreferenceTypeRecord.SalesLineId
dev_langs:
- CSharp
- C++
- VB
---

# SalesLineId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales line identifier that the delivery preference type applies to.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("SALESLINEID")> _
Public Property SalesLineId As String
    Get
    Friend Set
'Usage
Dim instance As LineDeliveryPreferenceTypeRecord
Dim value As String

value = instance.SalesLineId
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("SALESLINEID")]
public string SalesLineId { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"SALESLINEID")]
public:
property String^ SalesLineId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LineDeliveryPreferenceTypeRecord Class](linedeliverypreferencetyperecord-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

