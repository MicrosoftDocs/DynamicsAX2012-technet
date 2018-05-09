---
title: CommerceRuntimeException Class (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: CommerceRuntimeException Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeException
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.commerceruntimeexception(v=AX.60)
ms:contentKeyID: 49836434
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeException
dev_langs:
- CSharp
- C++
- VB
---

# CommerceRuntimeException Class

Represents the base class for exceptions originating from the Commerce Runtime.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public MustInherit Class CommerceRuntimeException _
    Inherits Exception
'Usage
Dim instance As CommerceRuntimeException
```

``` csharp
public abstract class CommerceRuntimeException : Exception
```

``` c++
public ref class CommerceRuntimeException abstract : public Exception
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [System.Exception](https://technet.microsoft.com/en-us/library/c18k6c59\(v=ax.60\))  
    Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeException  
      [Microsoft.Dynamics.Commerce.Runtime.CommunicationException](communicationexception-class-microsoft-dynamics-commerce-runtime.md)  
      [Microsoft.Dynamics.Commerce.Runtime.ConfigurationException](configurationexception-class-microsoft-dynamics-commerce-runtime.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataValidationException](datavalidationexception-class-microsoft-dynamics-commerce-runtime.md)  
      [Microsoft.Dynamics.Commerce.Runtime.FeatureNotSupportedException](featurenotsupportedexception-class-microsoft-dynamics-commerce-runtime.md)  
      [Microsoft.Dynamics.Commerce.Runtime.HeadquarterTransactionServiceException](headquartertransactionserviceexception-class-microsoft-dynamics-commerce-runtime.md)  
      [Microsoft.Dynamics.Commerce.Runtime.NotificationException](notificationexception-class-microsoft-dynamics-commerce-runtime.md)  
      [Microsoft.Dynamics.Commerce.Runtime.PaymentException](paymentexception-class-microsoft-dynamics-commerce-runtime.md)  
      [Microsoft.Dynamics.Commerce.Runtime.SecurityException](securityexception-class-microsoft-dynamics-commerce-runtime.md)  
      [Microsoft.Dynamics.Commerce.Runtime.StorageException](storageexception-class-microsoft-dynamics-commerce-runtime.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

