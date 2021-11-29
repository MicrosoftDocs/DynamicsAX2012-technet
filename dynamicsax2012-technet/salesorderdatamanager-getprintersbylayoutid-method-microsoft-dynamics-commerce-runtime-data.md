---
title: SalesOrderDataManager.GetPrintersByLayoutId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetPrintersByLayoutId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.GetPrintersByLayoutId(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salesorderdatamanager.getprintersbylayoutid(v=AX.60)
ms:contentKeyID: 65319978
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.GetPrintersByLayoutId
dev_langs:
- CSharp
- C++
- VB
---

# GetPrintersByLayoutId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetPrintersByLayoutId ( _
    terminalId As String, _
    layoutId As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of Printer)
'Usage
Dim instance As SalesOrderDataManager
Dim terminalId As String
Dim layoutId As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of Printer)

returnValue = instance.GetPrintersByLayoutId(terminalId, _
    layoutId, settings)
```

``` csharp
public ReadOnlyCollection<Printer> GetPrintersByLayoutId(
    string terminalId,
    string layoutId,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<Printer^>^ GetPrintersByLayoutId(
    String^ terminalId, 
    String^ layoutId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - layoutId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Printer](printer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SalesOrderDataManager Class](salesorderdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

