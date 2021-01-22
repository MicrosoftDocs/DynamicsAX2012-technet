---
title: CartLineData.StoreNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StoreNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.StoreNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.storenumber(v=AX.60)
ms:contentKeyID: 62210387
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.StoreNumber
dev_langs:
- CSharp
- C++
- VB
---

# StoreNumber Property

Gets or sets the store number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("STORE")> _
Public Property StoreNumber As String
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As String

value = instance.StoreNumber

instance.StoreNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("STORE")]
public string StoreNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"STORE")]
public:
property String^ StoreNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

