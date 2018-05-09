---
title: DropAndDeclareTransaction.TenderDropAndDeclareType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderDropAndDeclareType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction.TenderDropAndDeclareType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.dropanddeclaretransaction.tenderdropanddeclaretype(v=AX.60)
ms:contentKeyID: 62211457
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction.TenderDropAndDeclareType
dev_langs:
- CSharp
- C++
- VB
---

# TenderDropAndDeclareType Property

Gets or sets the tender drop and declare type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TYPE")> _
Public Property TenderDropAndDeclareType As TenderDropAndDeclareType
    Get
    Set
'Usage
Dim instance As DropAndDeclareTransaction
Dim value As TenderDropAndDeclareType

value = instance.TenderDropAndDeclareType

instance.TenderDropAndDeclareType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TYPE")]
public TenderDropAndDeclareType TenderDropAndDeclareType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TYPE")]
public:
property TenderDropAndDeclareType TenderDropAndDeclareType {
    TenderDropAndDeclareType get ();
    void set (TenderDropAndDeclareType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDropAndDeclareType](tenderdropanddeclaretype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TenderDropAndDeclareType](tenderdropanddeclaretype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[DropAndDeclareTransaction Class](dropanddeclaretransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

