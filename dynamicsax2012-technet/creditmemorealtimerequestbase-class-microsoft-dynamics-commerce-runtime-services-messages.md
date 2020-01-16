---
title: CreditMemoRealtimeRequestBase Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CreditMemoRealtimeRequestBase Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreditMemoRealtimeRequestBase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.creditmemorealtimerequestbase(v=AX.60)
ms:contentKeyID: 65321574
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreditMemoRealtimeRequestBase
dev_langs:
- CSharp
- C++
- VB
---

# CreditMemoRealtimeRequestBase Class

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class CreditMemoRealtimeRequestBase _
    Inherits Request
'Usage
Dim instance As CreditMemoRealtimeRequestBase
```

``` csharp
[DataContractAttribute]
public abstract class CreditMemoRealtimeRequestBase : Request
```

``` c++
[DataContractAttribute]
public ref class CreditMemoRealtimeRequestBase abstract : public Request
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreditMemoRealtimeRequestBase  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueCreditMemoRealtimeRequest](issuecreditmemorealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.LockCreditMemoRealtimeRequest](lockcreditmemorealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PayCreditMemoRealtimeRequest](paycreditmemorealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UnlockCreditMemoRealtimeRequest](unlockcreditmemorealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

