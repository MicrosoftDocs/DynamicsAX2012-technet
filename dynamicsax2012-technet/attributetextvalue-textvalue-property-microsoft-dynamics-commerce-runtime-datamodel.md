---
title: AttributeTextValue.TextValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TextValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeTextValue.TextValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.attributetextvalue.textvalue(v=AX.60)
ms:contentKeyID: 49828459
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeTextValue.TextValue
dev_langs:
- CSharp
- C++
- VB
---

# TextValue Property

Gets or sets the attribute value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TEXTVALUE")> _
Public Property TextValue As String
    Get
    Set
'Usage
Dim instance As AttributeTextValue
Dim value As String

value = instance.TextValue

instance.TextValue = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TEXTVALUE")]
public string TextValue { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TEXTVALUE")]
public:
property String^ TextValue {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The text value.  

## See Also

#### Reference

[AttributeTextValue Class](attributetextvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

