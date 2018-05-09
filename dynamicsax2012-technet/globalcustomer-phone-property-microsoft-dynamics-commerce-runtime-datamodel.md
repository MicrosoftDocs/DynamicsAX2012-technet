---
title: GlobalCustomer.Phone Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Phone Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.GlobalCustomer.Phone
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.globalcustomer.phone(v=AX.60)
ms:contentKeyID: 62207995
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.GlobalCustomer.Phone
dev_langs:
- CSharp
- C++
- VB
---

# Phone Property

Gets or sets the phone number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PHONE")> _
<DataMemberAttribute> _
Public Property Phone As String
    Get
    Set
'Usage
Dim instance As GlobalCustomer
Dim value As String

value = instance.Phone

instance.Phone = value
```

``` csharp
[ColumnAttribute("PHONE")]
[DataMemberAttribute]
public string Phone { get; set; }
```

``` c++
[ColumnAttribute(L"PHONE")]
[DataMemberAttribute]
public:
property String^ Phone {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GlobalCustomer Class](globalcustomer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

