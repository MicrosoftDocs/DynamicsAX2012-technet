---
title: CryptoUtilities.GetCertificate Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: GetCertificate Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.CryptoUtilities.GetCertificate(System.Security.Cryptography.X509Certificates.StoreName,System.Security.Cryptography.X509Certificates.StoreLocation,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.common.cryptoutilities.getcertificate(v=AX.60)
ms:contentKeyID: 62204303
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.CryptoUtilities.GetCertificate
dev_langs:
- CSharp
- C++
- VB
---

# GetCertificate Method

Get certificate by thumbprint.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetCertificate ( _
    storeName As StoreName, _
    storeLocation As StoreLocation, _
    thumbprint As String _
) As X509Certificate2
'Usage
Dim storeName As StoreName
Dim storeLocation As StoreLocation
Dim thumbprint As String
Dim returnValue As X509Certificate2

returnValue = CryptoUtilities.GetCertificate(storeName, _
    storeLocation, thumbprint)
```

``` csharp
public static X509Certificate2 GetCertificate(
    StoreName storeName,
    StoreLocation storeLocation,
    string thumbprint
)
```

``` c++
public:
static X509Certificate2^ GetCertificate(
    StoreName storeName, 
    StoreLocation storeLocation, 
    String^ thumbprint
)
```

#### Parameters

  - storeName  
    Type: [System.Security.Cryptography.X509Certificates.StoreName](https://technet.microsoft.com/en-us/library/tk313h1y\(v=ax.60\))  

<!-- end list -->

  - storeLocation  
    Type: [System.Security.Cryptography.X509Certificates.StoreLocation](https://technet.microsoft.com/en-us/library/90tyd6y4\(v=ax.60\))  

<!-- end list -->

  - thumbprint  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Security.Cryptography.X509Certificates.X509Certificate2](https://technet.microsoft.com/en-us/library/ms148409\(v=ax.60\))  
The certificate if found, null otherwise.  

## See Also

#### Reference

[CryptoUtilities Class](cryptoutilities-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

