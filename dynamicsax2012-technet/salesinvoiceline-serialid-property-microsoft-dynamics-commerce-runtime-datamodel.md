---
title: SalesInvoiceLine.SerialId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SerialId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.SerialId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.serialid(v=AX.60)
ms:contentKeyID: 62212956
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.SerialId
dev_langs:
- CSharp
- C++
- VB
---

# SerialId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the serial identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SERIALID")> _
Public Property SerialId As String
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As String

value = instance.SerialId

instance.SerialId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SERIALID")]
public string SerialId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SERIALID")]
public:
property String^ SerialId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The serial identifier.  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

