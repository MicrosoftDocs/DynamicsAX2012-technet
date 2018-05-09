---
title: CartLineData.Barcode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Barcode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.Barcode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.barcode(v=AX.60)
ms:contentKeyID: 62210720
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.Barcode
dev_langs:
- CSharp
- C++
- VB
---

# Barcode Property

Gets or sets the barcode value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("BARCODE")> _
Public Property Barcode As String
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As String

value = instance.Barcode

instance.Barcode = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("BARCODE")]
public string Barcode { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"BARCODE")]
public:
property String^ Barcode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

