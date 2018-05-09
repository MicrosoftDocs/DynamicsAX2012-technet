---
title: SaveNonSaleTenderServiceResponse.NonSalesTenderOperation Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: NonSalesTenderOperation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveNonSaleTenderServiceResponse.NonSalesTenderOperation
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.savenonsaletenderserviceresponse.nonsalestenderoperation(v=AX.60)
ms:contentKeyID: 62204126
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveNonSaleTenderServiceResponse.NonSalesTenderOperation
dev_langs:
- CSharp
- C++
- VB
---

# NonSalesTenderOperation Property

Gets the non sale tender operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NonSalesTenderOperation As NonSalesTransaction
    Get
    Private Set
'Usage
Dim instance As SaveNonSaleTenderServiceResponse
Dim value As NonSalesTransaction

value = instance.NonSalesTenderOperation
```

``` csharp
[DataMemberAttribute]
public NonSalesTransaction NonSalesTenderOperation { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property NonSalesTransaction^ NonSalesTenderOperation {
    NonSalesTransaction^ get ();
    private: void set (NonSalesTransaction^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveNonSaleTenderServiceResponse Class](savenonsaletenderserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

