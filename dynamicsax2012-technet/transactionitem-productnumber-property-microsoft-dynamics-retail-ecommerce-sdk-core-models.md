---
title: TransactionItem.ProductNumber Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: ProductNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TransactionItem.ProductNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.transactionitem.productnumber(v=AX.60)
ms:contentKeyID: 65317720
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TransactionItem.ProductNumber
dev_langs:
- CSharp
- C++
- VB
---

# ProductNumber Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductNumber As String
    Get
    Set
'Usage
Dim instance As TransactionItem
Dim value As String

value = instance.ProductNumber

instance.ProductNumber = value
```

``` csharp
[DataMemberAttribute]
public string ProductNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ProductNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

