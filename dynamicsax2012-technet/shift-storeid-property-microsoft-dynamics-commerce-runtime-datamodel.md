---
title: Shift.StoreId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StoreId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.StoreId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shift.storeid(v=AX.60)
ms:contentKeyID: 62211219
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.StoreId
dev_langs:
- CSharp
- C++
- VB
---

# StoreId Property

Gets or sets store identifier of shift.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("STOREID")> _
Public Property StoreId As String
    Get
    Set
'Usage
Dim instance As Shift
Dim value As String

value = instance.StoreId

instance.StoreId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("STOREID")]
public string StoreId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"STOREID")]
public:
property String^ StoreId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

