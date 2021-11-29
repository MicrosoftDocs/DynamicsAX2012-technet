---
title: TokenizedPaymentCard.CardToken Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: CardToken Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TokenizedPaymentCard.CardToken
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.tokenizedpaymentcard.cardtoken(v=AX.60)
ms:contentKeyID: 65316029
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TokenizedPaymentCard.CardToken
dev_langs:
- CSharp
- C++
- VB
---

# CardToken Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CardToken As String
    Get
    Set
'Usage
Dim instance As TokenizedPaymentCard
Dim value As String

value = instance.CardToken

instance.CardToken = value
```

``` csharp
[DataMemberAttribute]
public string CardToken { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CardToken {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TokenizedPaymentCard Class](tokenizedpaymentcard-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

