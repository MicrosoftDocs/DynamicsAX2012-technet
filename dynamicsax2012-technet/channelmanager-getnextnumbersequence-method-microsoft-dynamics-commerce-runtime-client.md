---
title: ChannelManager.GetNextNumberSequence Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetNextNumberSequence Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetNextNumberSequence
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getnextnumbersequence(v=AX.60)
ms:contentKeyID: 65323000
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetNextNumberSequence
dev_langs:
- CSharp
- C++
- VB
---

# GetNextNumberSequence Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetNextNumberSequence As ReadOnlyCollection(Of NumberSequenceSeedData)
'Usage
Dim instance As ChannelManager
Dim returnValue As ReadOnlyCollection(Of NumberSequenceSeedData)

returnValue = instance.GetNextNumberSequence()
```

``` csharp
public ReadOnlyCollection<NumberSequenceSeedData> GetNextNumberSequence()
```

``` c++
public:
ReadOnlyCollection<NumberSequenceSeedData^>^ GetNextNumberSequence()
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[NumberSequenceSeedData](numbersequenceseeddata-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

