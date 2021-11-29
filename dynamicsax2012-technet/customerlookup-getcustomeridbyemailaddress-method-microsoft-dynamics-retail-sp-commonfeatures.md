---
title: CustomerLookup.GetCustomerIdByEmailAddress Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: GetCustomerIdByEmailAddress Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomerLookup.GetCustomerIdByEmailAddress(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.customerlookup.getcustomeridbyemailaddress(v=AX.60)
ms:contentKeyID: 62204668
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomerLookup.GetCustomerIdByEmailAddress
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerIdByEmailAddress Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customer account number using the specified e-mail address.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetCustomerIdByEmailAddress ( _
    emailAddress As String _
) As String
'Usage
Dim emailAddress As String
Dim returnValue As String

returnValue = CustomerLookup.GetCustomerIdByEmailAddress(emailAddress)
```

``` csharp
public static string GetCustomerIdByEmailAddress(
    string emailAddress
)
```

``` c++
public:
static String^ GetCustomerIdByEmailAddress(
    String^ emailAddress
)
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The customer identifier.  

## See Also

#### Reference

[CustomerLookup Class](customerlookup-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

