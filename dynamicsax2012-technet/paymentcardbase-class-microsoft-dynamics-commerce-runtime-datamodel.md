---
title: PaymentCardBase Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PaymentCardBase Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcardbase(v=AX.60)
ms:contentKeyID: 65321176
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase
dev_langs:
- CSharp
- C++
- VB
---

# PaymentCardBase Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the base class of payment instrument by card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class PaymentCardBase _
    Inherits CommerceEntity
'Usage
Dim instance As PaymentCardBase
```

``` csharp
[DataContractAttribute]
public abstract class PaymentCardBase : CommerceEntity
```

``` c++
[DataContractAttribute]
public ref class PaymentCardBase abstract : public CommerceEntity
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard](tokenizedpaymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

