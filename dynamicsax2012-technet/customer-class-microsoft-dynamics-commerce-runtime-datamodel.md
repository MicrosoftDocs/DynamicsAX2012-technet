---
title: Customer Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Customer Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customer(v=AX.60)
ms:contentKeyID: 49849353
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer
dev_langs:
- CSharp
- C++
- VB
---

# Customer Class

Represents a customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DefaultSortOrderAttribute(ColumnName := "NAME", IsDescending := False)> _
<DataContractAttribute> _
Public Class Customer _
    Inherits CommerceEntity
'Usage
Dim instance As Customer
```

``` csharp
[DefaultSortOrderAttribute(ColumnName = "NAME", IsDescending = false)]
[DataContractAttribute]
public class Customer : CommerceEntity
```

``` c++
[DefaultSortOrderAttribute(ColumnName = L"NAME", IsDescending = false)]
[DataContractAttribute]
public ref class Customer : public CommerceEntity
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

