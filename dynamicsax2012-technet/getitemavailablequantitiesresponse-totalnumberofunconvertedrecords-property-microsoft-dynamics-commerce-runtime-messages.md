---
title: GetItemAvailableQuantitiesResponse.TotalNumberOfUnconvertedRecords Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: TotalNumberOfUnconvertedRecords Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailableQuantitiesResponse.TotalNumberOfUnconvertedRecords
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getitemavailablequantitiesresponse.totalnumberofunconvertedrecords(v=AX.60)
ms:contentKeyID: 49850206
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailableQuantitiesResponse.TotalNumberOfUnconvertedRecords
dev_langs:
- CSharp
- C++
- VB
---

# TotalNumberOfUnconvertedRecords Property

Gets the total number of unit of measure uncoverted records.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TotalNumberOfUnconvertedRecords As Integer
    Get
    Private Set
'Usage
Dim instance As GetItemAvailableQuantitiesResponse
Dim value As Integer

value = instance.TotalNumberOfUnconvertedRecords
```

``` csharp
[DataMemberAttribute]
public int TotalNumberOfUnconvertedRecords { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property int TotalNumberOfUnconvertedRecords {
    int get ();
    private: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[GetItemAvailableQuantitiesResponse Class](getitemavailablequantitiesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

