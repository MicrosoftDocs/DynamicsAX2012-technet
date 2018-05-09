---
title: TenderType.OperationType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OperationType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.OperationType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.operationtype(v=AX.60)
ms:contentKeyID: 62212811
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.OperationType
dev_langs:
- CSharp
- C++
- VB
---

# OperationType Property

Gets or sets the operation type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property OperationType As RetailOperation
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As RetailOperation

value = instance.OperationType

instance.OperationType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public RetailOperation OperationType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property RetailOperation OperationType {
    RetailOperation get ();
    void set (RetailOperation value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

