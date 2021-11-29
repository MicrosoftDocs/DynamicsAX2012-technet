---
title: PaymentConnectorConfiguration Constructor (Int64, String, String, Boolean) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PaymentConnectorConfiguration Constructor (Int64, String, String, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentConnectorConfiguration.#ctor(System.Int64,System.String,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paymentconnectorconfiguration.paymentconnectorconfiguration(v=AX.60)
ms:contentKeyID: 65316074
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PaymentConnectorConfiguration Constructor (Int64, String, String, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    recordId As Long, _
    name As String, _
    properties As String, _
    isTestMode As Boolean _
)
'Usage
Dim recordId As Long
Dim name As String
Dim properties As String
Dim isTestMode As Boolean

Dim instance As New PaymentConnectorConfiguration(recordId, _
    name, properties, isTestMode)
```

``` csharp
public PaymentConnectorConfiguration(
    long recordId,
    string name,
    string properties,
    bool isTestMode
)
```

``` c++
public:
PaymentConnectorConfiguration(
    long long recordId, 
    String^ name, 
    String^ properties, 
    bool isTestMode
)
```

#### Parameters

  - recordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - name  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - properties  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isTestMode  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[PaymentConnectorConfiguration Class](paymentconnectorconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[PaymentConnectorConfiguration Overload](paymentconnectorconfiguration-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

