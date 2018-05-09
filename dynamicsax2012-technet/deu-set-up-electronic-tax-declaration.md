---
title: (DEU) Set up electronic tax declaration
TOCTitle: (DEU) Set up electronic tax declaration
ms:assetid: 411dea33-8b5d-4d05-a6a7-03f1244c2def
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231361(v=AX.60)
ms:contentKeyID: 36056727
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TaxElectronicDeclarationSetup
- Forms.TaxElectronicCertificates
- DE - 00003
- Forms.TaxElectronicHTTPServer
- MsDynAx060.Forms.TaxElectronicCertificates
- MsDynAx060.Forms.TaxElectronicDeclarationSetup
- MsDynAx060.Forms.TaxElectronicHTTPServer
---

# (DEU) Set up electronic tax declaration 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create several types of tax documents such as payroll tax declarations, income tax declarations, and value added tax (VAT) statements that include Sales VAT Advance Notification information, and submit them electronically. The tax documents contain monthly or quarterly VAT sales or purchase information.

Use the **Electronic tax declaration setup** form to set up information about authentication, the use of a proxy server, and tax server IP addresses for the electronic tax declaration.

In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: The default tax server IP addresses that are used for VAT reports are updated in the **Electronic tax declaration server addresses** form. You can modify the default tax server IP addresses.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Electronic tax declaration setup**.

2.  Select the **Authentication** check box to require authentication when you submit the electronic tax declaration.

3.  Select the **Use of proxy server** check box to use a proxy server to submit the electronic tax declaration. You can specify the following values for the proxy server:
    
    1.  Select the **Proxy server authentication required** check box to require authentication for the proxy server.
    
    2.  In the **Proxy server IP address** field, enter the IP address of the proxy server.
    
    3.  In the **Proxy server port number** field, enter the port number to use for the proxy server.
    

    > [!NOTE]
    > <P>The <STRONG>Proxy server authentication required</STRONG>, <STRONG>Proxy server IP address</STRONG>, and <STRONG>Proxy server port number</STRONG> fields are available only if you select the <STRONG>Use of proxy server</STRONG> check box.</P>



4.  Click **Electronic tax certificates** to open the **Electronic tax certificates** form.

5.  Press CRTL+N to create a record.

6.  In the **User ID** field, select an identification code for the Microsoft Dynamics AX user to set up the certificate reference that is used to create and register the tax certificate.

7.  In the **Certificates reference** field, enter the friendly name of the certificate, and then close the form.

8.  In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: Click **HTTP servers** to open the **Electronic tax declaration server addresses** form, and then in the **Internet address** field, modify the default tax server IP addresses for VAT reports.
    

    > [!NOTE]
    > <P>If you delete all of the server IP addresses in the <STRONG>Electronic tax declaration server addresses</STRONG> form, you can reopen the <STRONG>Electronic tax declaration setup</STRONG> form to restore the default server IP addresses.</P>



## See also

[(DEU) Create and submit an electronic tax declaration](deu-create-and-submit-an-electronic-tax-declaration.md)

[(DEU) Electronic tax declaration setup (form)](https://technet.microsoft.com/en-us/library/aa598009\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

