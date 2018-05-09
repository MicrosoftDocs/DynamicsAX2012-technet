---
title: CartLineData.SalesStatus Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.SalesStatus
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.salesstatus(v=AX.60)
ms:contentKeyID: 65317803
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.SalesStatus
dev_langs:
- CSharp
- C++
- VB
---

# SalesStatus Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ReadOnlyAttribute("SALESSTATUS")> _
<ColumnAttribute("SALESSTATUS")> _
<IgnoreDataMemberAttribute> _
Public Property SalesStatus As SalesStatus
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As SalesStatus

value = instance.SalesStatus

instance.SalesStatus = value
```

``` csharp
[ReadOnlyAttribute("SALESSTATUS")]
[ColumnAttribute("SALESSTATUS")]
[IgnoreDataMemberAttribute]
public SalesStatus SalesStatus { get; set; }
```

``` c++
[ReadOnlyAttribute(L"SALESSTATUS")]
[ColumnAttribute(L"SALESSTATUS")]
[IgnoreDataMemberAttribute]
public:
property SalesStatus SalesStatus {
    SalesStatus get ();
    void set (SalesStatus value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesStatus](salesstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

