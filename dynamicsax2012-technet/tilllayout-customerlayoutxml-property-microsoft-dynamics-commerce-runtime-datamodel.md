---
title: TillLayout.CustomerLayoutXml Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerLayoutXml Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.CustomerLayoutXml
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.customerlayoutxml(v=AX.60)
ms:contentKeyID: 62214888
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.CustomerLayoutXml
dev_langs:
- CSharp
- C++
- VB
---

# CustomerLayoutXml Property

Gets or sets the value of customer layout.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CUSTOMERLAYOUTXML")> _
Public Property CustomerLayoutXml As String
    Get
    Set
'Usage
Dim instance As TillLayout
Dim value As String

value = instance.CustomerLayoutXml

instance.CustomerLayoutXml = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CUSTOMERLAYOUTXML")]
public string CustomerLayoutXml { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CUSTOMERLAYOUTXML")]
public:
property String^ CustomerLayoutXml {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The customer layout xml.  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

