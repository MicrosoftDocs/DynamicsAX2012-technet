---
title: TillLayout.CashChangerLayoutXml Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CashChangerLayoutXml Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.CashChangerLayoutXml
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.cashchangerlayoutxml(v=AX.60)
ms:contentKeyID: 62204928
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.CashChangerLayoutXml
dev_langs:
- CSharp
- C++
- VB
---

# CashChangerLayoutXml Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of cash changer layout.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CASHCHANGERLAYOUTXML")> _
Public Property CashChangerLayoutXml As String
    Get
    Set
'Usage
Dim instance As TillLayout
Dim value As String

value = instance.CashChangerLayoutXml

instance.CashChangerLayoutXml = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CASHCHANGERLAYOUTXML")]
public string CashChangerLayoutXml { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CASHCHANGERLAYOUTXML")]
public:
property String^ CashChangerLayoutXml {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The cash changer layout xml.  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

