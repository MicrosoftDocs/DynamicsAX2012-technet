---
title: SalesInvoiceLine.ConfigName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ConfigName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.ConfigName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.configname(v=AX.60)
ms:contentKeyID: 62213284
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.ConfigName
dev_langs:
- CSharp
- C++
- VB
---

# ConfigName Property

Gets or sets the config name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CONFIGNAME")> _
<DataMemberAttribute> _
Public Property ConfigName As String
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As String

value = instance.ConfigName

instance.ConfigName = value
```

``` csharp
[ColumnAttribute("CONFIGNAME")]
[DataMemberAttribute]
public string ConfigName { get; set; }
```

``` c++
[ColumnAttribute(L"CONFIGNAME")]
[DataMemberAttribute]
public:
property String^ ConfigName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The config name.  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

