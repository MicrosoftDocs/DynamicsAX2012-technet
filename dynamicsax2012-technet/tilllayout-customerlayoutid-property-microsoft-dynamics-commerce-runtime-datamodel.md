---
title: TillLayout.CustomerLayoutId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerLayoutId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.CustomerLayoutId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.customerlayoutid(v=AX.60)
ms:contentKeyID: 62213448
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.CustomerLayoutId
dev_langs:
- CSharp
- C++
- VB
---

# CustomerLayoutId Property

Gets or sets the value of customer layout.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CUSTOMERLAYOUTID")> _
<DataMemberAttribute> _
Public Property CustomerLayoutId As String
    Get
    Set
'Usage
Dim instance As TillLayout
Dim value As String

value = instance.CustomerLayoutId

instance.CustomerLayoutId = value
```

``` csharp
[ColumnAttribute("CUSTOMERLAYOUTID")]
[DataMemberAttribute]
public string CustomerLayoutId { get; set; }
```

``` c++
[ColumnAttribute(L"CUSTOMERLAYOUTID")]
[DataMemberAttribute]
public:
property String^ CustomerLayoutId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The customer layout xml.  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

