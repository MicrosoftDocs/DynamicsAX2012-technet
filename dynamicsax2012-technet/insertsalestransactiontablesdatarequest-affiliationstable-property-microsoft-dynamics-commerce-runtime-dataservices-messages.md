---
title: InsertSalesTransactionTablesDataRequest.AffiliationsTable Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: AffiliationsTable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertSalesTransactionTablesDataRequest.AffiliationsTable
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.insertsalestransactiontablesdatarequest.affiliationstable(v=AX.60)
ms:contentKeyID: 65318944
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertSalesTransactionTablesDataRequest.AffiliationsTable
dev_langs:
- CSharp
- C++
- VB
---

# AffiliationsTable Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the affiliations table.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property AffiliationsTable As DataTable
    Get
    Private Set
'Usage
Dim instance As InsertSalesTransactionTablesDataRequest
Dim value As DataTable

value = instance.AffiliationsTable
```

``` csharp
public DataTable AffiliationsTable { get; private set; }
```

``` c++
public:
property DataTable^ AffiliationsTable {
    DataTable^ get ();
    private: void set (DataTable^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  
Returns [DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md).  

## See Also

#### Reference

[InsertSalesTransactionTablesDataRequest Class](insertsalestransactiontablesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

