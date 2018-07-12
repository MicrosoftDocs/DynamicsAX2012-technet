---
title: Authenticating users in Retail online sample stores
TOCTitle: Authenticating users in Retail online sample stores
ms:assetid: 2dbd6c13-9154-493a-bf28-011d70409c3e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn741226(v=AX.60)
ms:contentKeyID: 62219115
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Authenticating users in Retail online sample stores 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The Microsoft Dynamics AX 2012 for Retail online sample stores authenticate customers and site administrators by using the two authentication types supported by Microsoft SharePoint Server 2013:

  - Forms-based authentication for customers.

  - Windows classic mode authentication for site administrators.

For more information about Windows and forms-based authentication with SharePoint Server 2013, see [Authentication overview for SharePoint 2013](http://go.microsoft.com/fwlink/?linkid=394056&clcid=0x409) and [Authentication, authorization, and security in SharePoint 2013](http://go.microsoft.com/fwlink/?linkid=394057&clcid=0x409).

## Configuration and authentication

Site administrators configure how site users are authenticated by specifying publishing portal settings in PowerShell deployment scripts. For more information, see [Install a Retail online store (e-commerce)](install-a-retail-online-store-e-commerce.md). The PowerShell deployment scripts create web applications in Internet Information Services (IIS) and SharePoint. For example, the deployment scripts can create the following two web applications for the Contoso sample online store:

  - For SharePoint, the web application is called **Out of box Store front – Public 1**.

  - For IIS, the web application is called **RetailC2WebApplication-1**.

The deployment scripts also create site collections on the SharePoint web application. The default settings for the site collections configure port 40003 for site administrators and port 40002 for customers. For example, the Contoso online sample store can authenticate users who access the site URLs as shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>URL</p></th>
<th><p>Authentication method</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>http:// <em>computername</em>:40003/sites/RetailPublishingPortal</p></td>
<td><p>Windows authentication. When you sign in your current Windows user ID is used for authentication.</p></td>
</tr>
<tr class="even">
<td><p>http:// <em>computername</em>:40002/sites/RetailPublishingPortal</p></td>
<td><p>Forms-based authentication that includes external logon providers such as Facebook. Users may remain anonymous if they decide not to log on.</p></td>
</tr>
</tbody>
</table>


## Authenticating customers by using forms-based authentication

The Retail online sample stores use three types of authentication for store customers. Customers can remain anonymous, create a new user ID, or log on as a returning user. Anonymous users may purchase products, but their identifying information and credentials are not stored permanently. When a customer creates a new user ID, a customer record is created in the CustTable table in AX 2012. Credentials for returning customers are validated by using forms-based authentication.

When you install and deploy the sample sites, you configure the default validation for customers’ credentials. You can configure the SharePoint database as the membership and role provider or you can configure Facebook as an external logon provider. The Dynamics custom claims provider implements the mapping of a customer in the AX 2012 database to a customer of the Retail online sample store.

### ![Dn741226.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741226.collapse_all(en-us,AX.60).gif")Authentication process

The following diagram illustrates the components and databases involved in authenticating a user who signs in to the Contoso site on port 40002.

![Authentication process flow in Retail online store](images/Dn741226.RetailOnlineStoreAuthenticationFlow(en-us,AX.60).jpg "Authentication process flow in Retail online store")

The following numbered steps describe the processes in the diagram.

1.  The user clicks **Sign In** on the store home page or accesses a page that requires authentication.

2.  The user is redirected to the Login.aspx page.

3.  The user enters an e-mail address and password. Data is sent to the SharePoint Secure Token Service (STS). The STS calls the forms-based identity provider, which is based on the ASP.NET forms-base authentication provider and the AX 2012 Retail custom claims provider.

4.  The identity provider uses the forms-based membership database **SpFBA** to validate the user name and password.

5.  The STS may invoke other identity providers, such as Facebook.

6.  After authentication, the Dynamics custom claims provider queries the customer mapping database **SpSQLAuthZ**, returns the AX 2012 customer ID for the user, and adds it to the claim set.

7.  The STS returns the claim set back to the page.

8.  The page is sent to the user’s browser.

### ![Dn741226.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741226.collapse_all(en-us,AX.60).gif")Authenticating a new customer

A new customer who does not decide to register an account receives a temporary token that SharePoint uses to authenticate the session. The new customer can check out as a guest or click **Register a New Account** on the **Sign In** page to create a customer record in the AX 2012 database. Registering a new account sets up the user as a customer in the AX 2012 database and creates a mapping between the customer’s credentials and the record for the customer in AX 2012.

### ![Dn741226.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741226.collapse_all(en-us,AX.60).gif")Authenticating a returning customer

After a returning customer is authenticated, the custom claims provider adds the customer information from the AX 2012 database to the claim.

### ![Dn741226.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741226.collapse_all(en-us,AX.60).gif")Extending user authentication by adding a logon provider

You can configure Facebook as an external logon provider when you [install the Retail online store](install-a-retail-online-store-e-commerce.md). Source code for integrating Facebook authentication is provided in the Retail SDK as an example for extending user authentication. To find the sample code, open the file Retail SDK\\Online Channel\\Storefront.sln in Visual Studio. The source code for Facebook integration is found in the **SharePoint.Web.Common** project under the **Facebook** folder.

## See also

[Plan for user authentication methods in SharePoint 2013](http://go.microsoft.com/fwlink/?linkid=394053&clcid=0x409)

[Incoming claims: Signing into SharePoint 2013](http://go.microsoft.com/fwlink/?linkid=394114&clcid=0x409)

[Forms authentication in ASP.NET](http://go.microsoft.com/fwlink/?linkid=394082&clcid=0x409)

  


