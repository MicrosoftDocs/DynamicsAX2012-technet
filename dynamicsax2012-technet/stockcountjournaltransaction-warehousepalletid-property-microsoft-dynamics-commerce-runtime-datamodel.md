---
title: StockCountJournalTransaction.WarehousePalletId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: WarehousePalletId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.WarehousePalletId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.stockcountjournaltransaction.warehousepalletid(v=AX.60)
ms:contentKeyID: 62202413
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.WarehousePalletId
dev_langs:
- CSharp
- C++
- VB
---

# WarehousePalletId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the warehouse pallet identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("WMSPALLETID")> _
<DataMemberAttribute> _
Public Property WarehousePalletId As String
    Get
    Set
'Usage
Dim instance As StockCountJournalTransaction
Dim value As String

value = instance.WarehousePalletId

instance.WarehousePalletId = value
```

``` csharp
[ColumnAttribute("WMSPALLETID")]
[DataMemberAttribute]
public string WarehousePalletId { get; set; }
```

``` c++
[ColumnAttribute(L"WMSPALLETID")]
[DataMemberAttribute]
public:
property String^ WarehousePalletId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[StockCountJournalTransaction Class](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

