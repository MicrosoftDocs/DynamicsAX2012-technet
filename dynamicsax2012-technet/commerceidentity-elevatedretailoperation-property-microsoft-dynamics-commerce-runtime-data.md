---
title: CommerceIdentity.ElevatedRetailOperation Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ElevatedRetailOperation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.ElevatedRetailOperation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.commerceidentity.elevatedretailoperation(v=AX.60)
ms:contentKeyID: 62211029
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.ElevatedRetailOperation
dev_langs:
- CSharp
- C++
- VB
---

# ElevatedRetailOperation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the retail operation identifier - used in elevated mode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ElevatedRetailOperation As RetailOperation
    Get
    Set
'Usage
Dim instance As CommerceIdentity
Dim value As RetailOperation

value = instance.ElevatedRetailOperation

instance.ElevatedRetailOperation = value
```

``` csharp
[DataMemberAttribute]
public RetailOperation ElevatedRetailOperation { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property RetailOperation ElevatedRetailOperation {
    RetailOperation get ();
    void set (RetailOperation value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CommerceIdentity Class](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

