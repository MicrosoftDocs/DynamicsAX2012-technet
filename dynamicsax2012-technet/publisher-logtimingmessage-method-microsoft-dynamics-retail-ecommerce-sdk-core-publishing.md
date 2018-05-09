---
title: Publisher.LogTimingMessage Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: LogTimingMessage Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.Publisher.LogTimingMessage(System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.publisher.logtimingmessage(v=AX.60)
ms:contentKeyID: 65316819
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.Publisher.LogTimingMessage
dev_langs:
- CSharp
- C++
- VB
---

# LogTimingMessage Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Sub LogTimingMessage ( _
    format As String, _
    ParamArray args As Object() _
)
'Usage
Dim instance As Publisher
Dim format As String
Dim args As Object()

instance.LogTimingMessage(format, args)
```

``` csharp
public void LogTimingMessage(
    string format,
    params Object[] args
)
```

``` c++
public:
void LogTimingMessage(
    String^ format, 
    ... array<Object^>^ args
)
```

#### Parameters

  - format  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - args  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\[\]  

## See Also

#### Reference

[Publisher Class](publisher-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

