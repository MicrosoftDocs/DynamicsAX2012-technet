---
title: SalesOrder Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesOrder Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesorder(v=AX.60)
ms:contentKeyID: 49849054
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrder Class

Sales order class

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DefaultSortOrderAttribute(ColumnName := "ORDERPLACEDDATE", IsDescending := True)> _
<DataContractAttribute> _
Public Class SalesOrder _
    Inherits SalesTransaction
'Usage
Dim instance As SalesOrder
```

``` csharp
[DefaultSortOrderAttribute(ColumnName = "ORDERPLACEDDATE", IsDescending = true)]
[DataContractAttribute]
public class SalesOrder : SalesTransaction
```

``` c++
[DefaultSortOrderAttribute(ColumnName = L"ORDERPLACEDDATE", IsDescending = true)]
[DataContractAttribute]
public ref class SalesOrder : public SalesTransaction
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

