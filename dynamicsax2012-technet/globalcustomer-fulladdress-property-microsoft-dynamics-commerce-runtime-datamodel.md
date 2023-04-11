---
title: GlobalCustomer.FullAddress Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FullAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.GlobalCustomer.FullAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.globalcustomer.fulladdress(v=AX.60)
ms:contentKeyID: 62210837
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.GlobalCustomer.FullAddress
dev_langs:
- CSharp
- C++
- VB
---

# FullAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("FULLADDRESS")> _
Public Property FullAddress As String
    Get
    Set
'Usage
Dim instance As GlobalCustomer
Dim value As String

value = instance.FullAddress

instance.FullAddress = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("FULLADDRESS")]
public string FullAddress { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"FULLADDRESS")]
public:
property String^ FullAddress {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GlobalCustomer Class](globalcustomer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

