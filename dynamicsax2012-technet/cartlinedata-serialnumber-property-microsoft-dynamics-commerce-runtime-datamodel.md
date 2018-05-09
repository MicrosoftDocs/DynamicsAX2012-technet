---
title: CartLineData.SerialNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SerialNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.SerialNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.serialnumber(v=AX.60)
ms:contentKeyID: 62202888
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.SerialNumber
dev_langs:
- CSharp
- C++
- VB
---

# SerialNumber Property

Gets or sets the serial number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTSERIALID")> _
Public Property SerialNumber As String
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As String

value = instance.SerialNumber

instance.SerialNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTSERIALID")]
public string SerialNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTSERIALID")]
public:
property String^ SerialNumber {
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

