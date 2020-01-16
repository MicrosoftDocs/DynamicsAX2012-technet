---
title: TaxViewLine.TaxId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxViewLine.TaxId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxviewline.taxid(v=AX.60)
ms:contentKeyID: 65320397
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxViewLine.TaxId
dev_langs:
- CSharp
- C++
- VB
---

# TaxId Property

Gets or sets the tax identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TaxId As String
    Get
    Set
'Usage
Dim instance As TaxViewLine
Dim value As String

value = instance.TaxId

instance.TaxId = value
```

``` csharp
[DataMemberAttribute]
public string TaxId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TaxId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

TaxId is consist of "tax component" + @ + "tax rate".

## See Also

#### Reference

[TaxViewLine Class](taxviewline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

