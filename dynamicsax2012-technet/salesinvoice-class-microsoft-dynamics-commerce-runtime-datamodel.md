---
title: SalesInvoice Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesInvoice Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoice(v=AX.60)
ms:contentKeyID: 62211100
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice
dev_langs:
- CSharp
- C++
- VB
---

# SalesInvoice Class

Represents a customer invoice journal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DefaultSortOrderAttribute(ColumnName := "INVOICEDATE", IsDescending := True)> _
<DataContractAttribute> _
Public Class SalesInvoice _
    Inherits CommerceEntity
'Usage
Dim instance As SalesInvoice
```

``` csharp
[DefaultSortOrderAttribute(ColumnName = "INVOICEDATE", IsDescending = true)]
[DataContractAttribute]
public class SalesInvoice : CommerceEntity
```

``` c++
[DefaultSortOrderAttribute(ColumnName = L"INVOICEDATE", IsDescending = true)]
[DataContractAttribute]
public ref class SalesInvoice : public CommerceEntity
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

