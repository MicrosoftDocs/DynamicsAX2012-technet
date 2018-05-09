---
title: SalesLine.SalesStatus Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.SalesStatus
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.salesstatus(v=AX.60)
ms:contentKeyID: 65318658
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.SalesStatus
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
<IgnoreDataMemberAttribute> _
<ColumnAttribute("SALESSTATUS")> _
Public Property SalesStatus As SalesStatus
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As SalesStatus

value = instance.SalesStatus

instance.SalesStatus = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("SALESSTATUS")]
public SalesStatus SalesStatus { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"SALESSTATUS")]
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

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

