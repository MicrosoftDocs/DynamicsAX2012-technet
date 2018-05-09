---
title: TaxLine.TaxCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLine.TaxCode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxline.taxcode(v=AX.60)
ms:contentKeyID: 49844944
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLine.TaxCode
dev_langs:
- CSharp
- C++
- VB
---

# TaxCode Property

Gets or sets the tax code, many per item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TaxCode As String
    Get
    Set
'Usage
Dim instance As TaxLine
Dim value As String

value = instance.TaxCode

instance.TaxCode = value
```

``` csharp
[DataMemberAttribute]
public string TaxCode { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TaxCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxLine Class](taxline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

