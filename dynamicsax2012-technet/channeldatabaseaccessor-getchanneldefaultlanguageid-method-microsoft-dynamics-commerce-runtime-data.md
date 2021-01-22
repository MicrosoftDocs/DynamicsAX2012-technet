---
title: ChannelDatabaseAccessor.GetChannelDefaultLanguageId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelDefaultLanguageId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetChannelDefaultLanguageId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatabaseaccessor.getchanneldefaultlanguageid(v=AX.60)
ms:contentKeyID: 62210270
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetChannelDefaultLanguageId
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelDefaultLanguageId Method

Gets the default channel language identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelDefaultLanguageId As String
'Usage
Dim instance As ChannelDatabaseAccessor
Dim returnValue As String

returnValue = instance.GetChannelDefaultLanguageId()
```

``` csharp
public string GetChannelDefaultLanguageId()
```

``` c++
public:
virtual String^ GetChannelDefaultLanguageId() sealed
```

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The default language identifier.  

#### Implements

[IChannelDataManager.GetChannelDefaultLanguageId()](ichanneldatamanager-getchanneldefaultlanguageid-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChannelDatabaseAccessor Class](channeldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

