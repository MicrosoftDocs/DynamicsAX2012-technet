---
title: GiftCardRealtimeRequestBase Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GiftCardRealtimeRequestBase Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GiftCardRealtimeRequestBase
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.giftcardrealtimerequestbase(v=AX.60)
ms:contentKeyID: 65317895
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GiftCardRealtimeRequestBase
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardRealtimeRequestBase Class

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class GiftCardRealtimeRequestBase _
    Inherits Request
'Usage
Dim instance As GiftCardRealtimeRequestBase
```

``` csharp
[DataContractAttribute]
public abstract class GiftCardRealtimeRequestBase : Request
```

``` c++
[DataContractAttribute]
public ref class GiftCardRealtimeRequestBase abstract : public Request
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GiftCardRealtimeRequestBase  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AddToGiftCardRealtimeRequest](addtogiftcardrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueGiftCardRealtimeRequest](issuegiftcardrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.LockGiftCardRealtimeRequest](lockgiftcardrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PayGiftCardRealtimeRequest](paygiftcardrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.VoidGiftCardPaymentRealtimeRequest](voidgiftcardpaymentrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

