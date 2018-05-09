---
title: SalesTransactionConverter.ConvertToData Method (SalesTransaction, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ConvertToData Method (SalesTransaction, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionConverter.ConvertToData(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.salestransactionconverter.converttodata(v=AX.60)
ms:contentKeyID: 62208429
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ConvertToData Method (SalesTransaction, Boolean)

Converts from a sales transaction to its database representation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ConvertToData ( _
    salesTransaction As SalesTransaction, _
    serializeData As Boolean _
) As SalesTransactionData
'Usage
Dim salesTransaction As SalesTransaction
Dim serializeData As Boolean
Dim returnValue As SalesTransactionData

returnValue = SalesTransactionConverter.ConvertToData(salesTransaction, _
    serializeData)
```

``` csharp
public static SalesTransactionData ConvertToData(
    SalesTransaction salesTransaction,
    bool serializeData
)
```

``` c++
public:
static SalesTransactionData^ ConvertToData(
    SalesTransaction^ salesTransaction, 
    bool serializeData
)
```

#### Parameters

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - serializeData  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData](salestransactiondata-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The sales transaction database representation.  

## See Also

#### Reference

[SalesTransactionConverter Class](salestransactionconverter-class-microsoft-dynamics-commerce-runtime-data.md)

[ConvertToData Overload](salestransactionconverter-converttodata-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

