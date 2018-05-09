---
title: Transaction.ChargeAmountWithCurrency Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: ChargeAmountWithCurrency Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Transaction.ChargeAmountWithCurrency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.transaction.chargeamountwithcurrency(v=AX.60)
ms:contentKeyID: 65316334
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Transaction.ChargeAmountWithCurrency
dev_langs:
- CSharp
- C++
- VB
---

# ChargeAmountWithCurrency Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChargeAmountWithCurrency As String
    Get
    Set
'Usage
Dim instance As Transaction
Dim value As String

value = instance.ChargeAmountWithCurrency

instance.ChargeAmountWithCurrency = value
```

``` csharp
[DataMemberAttribute]
public string ChargeAmountWithCurrency { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ChargeAmountWithCurrency {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Transaction Class](transaction-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

