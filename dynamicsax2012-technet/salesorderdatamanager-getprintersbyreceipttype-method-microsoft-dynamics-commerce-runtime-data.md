---
title: SalesOrderDataManager.GetPrintersByReceiptType Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetPrintersByReceiptType Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.GetPrintersByReceiptType(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salesorderdatamanager.getprintersbyreceipttype(v=AX.60)
ms:contentKeyID: 65322220
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.GetPrintersByReceiptType
dev_langs:
- CSharp
- C++
- VB
---

# GetPrintersByReceiptType Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetPrintersByReceiptType ( _
    terminalId As String, _
    receiptType As ReceiptType, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of Printer)
'Usage
Dim instance As SalesOrderDataManager
Dim terminalId As String
Dim receiptType As ReceiptType
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of Printer)

returnValue = instance.GetPrintersByReceiptType(terminalId, _
    receiptType, settings)
```

``` csharp
public ReadOnlyCollection<Printer> GetPrintersByReceiptType(
    string terminalId,
    ReceiptType receiptType,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<Printer^>^ GetPrintersByReceiptType(
    String^ terminalId, 
    ReceiptType receiptType, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType](receipttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Printer](printer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SalesOrderDataManager Class](salesorderdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

