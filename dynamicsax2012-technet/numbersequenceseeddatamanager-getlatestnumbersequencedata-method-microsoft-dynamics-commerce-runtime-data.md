---
title: NumberSequenceSeedDataManager.GetLatestNumberSequenceData Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetLatestNumberSequenceData Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.NumberSequenceSeedDataManager.GetLatestNumberSequenceData(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.numbersequenceseeddatamanager.getlatestnumbersequencedata(v=AX.60)
ms:contentKeyID: 65322633
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.NumberSequenceSeedDataManager.GetLatestNumberSequenceData
dev_langs:
- CSharp
- C++
- VB
---

# GetLatestNumberSequenceData Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetLatestNumberSequenceData ( _
    terminalId As String _
) As Tuple(Of ReadOnlyCollection(Of Shift), ReadOnlyCollection(Of SalesTransaction), ReadOnlyCollection(Of SalesTransaction))
'Usage
Dim instance As NumberSequenceSeedDataManager
Dim terminalId As String
Dim returnValue As Tuple(Of ReadOnlyCollection(Of Shift), ReadOnlyCollection(Of SalesTransaction), ReadOnlyCollection(Of SalesTransaction))

returnValue = instance.GetLatestNumberSequenceData(terminalId)
```

``` csharp
public Tuple<ReadOnlyCollection<Shift>, ReadOnlyCollection<SalesTransaction>, ReadOnlyCollection<SalesTransaction>> GetLatestNumberSequenceData(
    string terminalId
)
```

``` c++
public:
Tuple<ReadOnlyCollection<Shift^>^, ReadOnlyCollection<SalesTransaction^>^, ReadOnlyCollection<SalesTransaction^>^>^ GetLatestNumberSequenceData(
    String^ terminalId
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: Tuple\<[ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>\>  

## See Also

#### Reference

[NumberSequenceSeedDataManager Class](numbersequenceseeddatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

