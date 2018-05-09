---
title: SalesOrderDataManager.GetReceiptLayoutId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetReceiptLayoutId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.GetReceiptLayoutId(Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.salesorderdatamanager.getreceiptlayoutid(v=AX.60)
ms:contentKeyID: 65322182
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.GetReceiptLayoutId
dev_langs:
- CSharp
- C++
- VB
---

# GetReceiptLayoutId Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetReceiptLayoutId ( _
    receiptType As ReceiptType, _
    receiptProfileId As String, _
    settings As QueryResultSettings _
) As String
'Usage
Dim instance As SalesOrderDataManager
Dim receiptType As ReceiptType
Dim receiptProfileId As String
Dim settings As QueryResultSettings
Dim returnValue As String

returnValue = instance.GetReceiptLayoutId(receiptType, _
    receiptProfileId, settings)
```

``` csharp
public string GetReceiptLayoutId(
    ReceiptType receiptType,
    string receiptProfileId,
    QueryResultSettings settings
)
```

``` c++
public:
String^ GetReceiptLayoutId(
    ReceiptType receiptType, 
    String^ receiptProfileId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - receiptType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType](receipttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - receiptProfileId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[SalesOrderDataManager Class](salesorderdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

