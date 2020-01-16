---
title: Deploy Enterprise Portal for vendor registration with Windows Azure Active Directory Access Control
TOCTitle: Deploy Enterprise Portal for vendor registration with Windows Azure Active Directory Access Control
ms:assetid: 2c6e0947-fe25-40da-85e6-1485d2309d9c
ms:mtpsurl: https://technet.microsoft.com/library/Dn715949(v=AX.60)
ms:contentKeyID: 62200022
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Deploy Enterprise Portal for vendor registration with Windows Azure Active Directory Access Control 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to create a claims-aware Enterprise Portal site for vendor registration. The vendor registration process begins when a potential vendor requests registration by using a public Enterprise Portal site that is configured for anonymous authentication. After completing a series of steps in the registration workflow, the registered vendor can access Enterprise Portal outside of your Active Directory domain by using one of the following types of accounts: Microsoft Account, Google, Yahoo, or Facebook.

The claims-aware Enterprise Portal site uses Windows Azure Active Directory Access Control (also known as Access Control Service or ACS). ACS is a cloud-based service that provides user authentication and authorization to web applications and services. Instead of implementing an authentication system with user accounts that are specific to your application, ACS manages user authentication and authorization on the web.

This topic describes how to deploy and configure Enterprise Portal with ACS for a vendor registration portal.

## Before you begin

Complete the following tasks before you deploy Enterprise Portal for vendor registration.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Learn about Windows Azure Active Directory Access Control (ACS)</p></td>
<td><p><a href="http://go.microsoft.com/fwlink/?linkid=390990">Access Control Services 2.0</a> on MSDN.</p></td>
</tr>
<tr class="even">
<td><p>Purchase an Azure subscription so that you can use ACS</p></td>
<td><p><a href="http://go.microsoft.com/fwlink/?linkid=390991">Windows Azure sign-up</a> on the web.</p></td>
</tr>
</tbody>
</table>


## Process flow: Enterprise Portal vendor registration with Access Control Services

The diagrams in this section describe how users complete the vendor on-boarding process by using an Enterprise Portal site that is configured for claims-based authentication with ACS. After you configure Enterprise Portal with ACS, as described in this topic, unsolicited vendors use this process to register with your company for consideration as vendors.

## Unsolicited vendor sign up with an Enterprise Portal public site and ACS

This section describes the process by which an unsolicited vendor authenticates with ACS to use the Enterprise Portal sign up page.

Figure 1: Unsolicited vendor sign up process flow with an Enterprise Portal public site and ACS

![Process flow of public site vendor registration](images/Dn715949.EPACSPublic(AX.60).gif "Process flow of public site vendor registration")

1.  A vendor wants to register with your company and locates the public site. The user is regarded as a **Guest** user with the security role **Vendor anonymous (external)**.

2.  The vendor clicks the **sign-up** button. This button is visible when a guest user has the **Vendor anonymous (external)** security role in Microsoft Dynamics AX. The site redirects the request to ACS.

3.  ACS provides the user with a list of links to registered identity providers. The user enters credentials for a third-party provider such as one of the following: Microsoft Account, Google, Yahoo, or Facebook. The provider authenticates the credentials.

4.  After the user is authenticated, ACS redirects the user’s browser to the URL for the sign up form and includes an identity token.

5.  Enterprise Portal determines that the user’s identity has been verified. Enterprise Portal displays the sign up form. The user completes the form and submits their information.

After the user submits their information in the **Sign up** form, Microsoft Dynamics AX stores the request as an unsolicited vendor requests with a user alias derived from the identity token. This information is used to create a Microsoft Dynamics AX user account. The new user account is assigned to the **Prospective vendor** security role in Microsoft Dynamics AX. The user creation is handled by the Microsoft Dynamics AX New User request workflow. The user is now considered to be a **Prospective Vendor** by the system. The system sends the user a private URL for more information, as described by the next process flow.

## Prospective vendor registration with an Enterprise Portal private site and ACS

This section describes the process by which a prospective vendor (a user who has completed the sign up form described in the previous process flow) authenticates with ACS to use the Enterprise Portal vendor registration page.

Figure 2: Vendor prospect registration process flow with an Enterprise Portal private site and ACS

![Vendor registration Enterprise Portal private site](images/Dn715949.EPACSPrivate(AX.60).gif "Vendor registration Enterprise Portal private site")

1.  A prospective vendor (a user) who wants to complete the registration process with your company to become a vendor locates the URL sent to their email after they completed the **Sign up** form.

2.  The site determines that the user is not authenticated and redirects to ACS.

3.  ACS provides the user with a list of links to registered identity providers. The user enters credentials for a third-party provider such as one of the following: Microsoft Account, Google, Yahoo, or Facebook. The provider authenticates the credentials.

4.  After the user is authenticated, ACS redirects the user’s browser to the private Enterprise Portal URL and includes an identity token.

5.  SharePoint determines that the user has been authenticated. Microsoft Dynamics AX authorizes the user to access the Prospective vendor registration form. The user completes the form and submits their information.

After the prospective vendor completes the registration form, the request is processed for approval by Microsoft Dynamics AX workflow. If the prospective vendor is accepted as a vendor, they are assigned a vendor security role. The vendor can then access the vendor portal pages.

## Deploy Enterprise Portal sites

A vendor registration portal requires an internal Enterprise Portal site in your Active Directory domain *and* a public Enterprise Portal site configured for anonymous access. See the following procedures to install these sites:

  - **Internal site**: [Install Enterprise Portal on a single server](install-enterprise-portal-on-a-single-server.md) or [Deploy Enterprise Portal in a server farm](deploy-enterprise-portal-in-a-server-farm.md)

  - **Public site**: [Create a public Enterprise Portal site](create-a-public-enterprise-portal-site.md)

After you have deployed the internal site in your Active Directory domain and the public site with anonymous access, you can continue with the procedures in this topic.

## Register a site with Access Control Services (ACS)

This section includes multiple procedures to help you register a site with ACS and then configure the claims-aware site. You must complete each procedure in this section.

## Create an ACS site on the Azure management portal

To perform the following procedure you must have an Azure subscription. For more information, see [Windows Azure sign-up](http://go.microsoft.com/fwlink/?linkid=390991) on the web.

1.  Open the [Azure control panel](http://go.microsoft.com/fwlink/?linkid=390995) on the web.

2.  In the left pane, click **Active Directory** and then click **Access control namespace** in the main header.
    
    ![The Windows Azure Active Directory page](images/Dn715949.EPAzureACS1(AX.60).gif "The Windows Azure Active Directory page")

3.  Create a new namespace. Click **New** at the bottom of the Azure web page and complete the steps for **App Services** \> **Active Directory** \> **Access Control** \> **quick create**. When the wizard is completed, you see an ACS URI in this format: https://\<acs\_namespace\>.accesscontrol.windows.net
    

    > [!NOTE]
    > <P>Only the administrator of the Azure subscription can access the ACS Management Portal. This person must configure access for other administrators who need access to the ACS Access Control page. For more information, see <A href="http://go.microsoft.com/fwlink/?linkid=391018">Portal Administrators</A>.</P>



4.  After the namespace is created, select it in the **Access Control Namespaces** list and click **Manage** at the bottom of the page.

5.  In the Access Control Service management portal, click **Identity Providers**. Select the providers that you want to enable for your claims-aware Enterprise Portal site. If you select Microsoft Account, Google, or Yahoo, you can continue with the procedure to **Add a relying party**. If you want to enable Facebook as an identity provider, you must complete the steps in the **Configure Facebook as an ACS identity provider** procedure.

## Configure Facebook as an ACS identity provider

Complete the following procedure to configure Facebook as an ACS identity provider for your claims-aware Enterprise Portal site.

1.  Complete the configuration steps in the following article on MSDN: [Facebook as an ACS Identity Provider](http://go.microsoft.com/fwlink/?linkid=391020). After you complete these steps in the article, continue with this procedure.

2.  In the **Access Control Service** management portal, on the **Basic** page for the Facebook app, enter **windows.net** in the **App Domains** field.
    
    ![ACS Facebook app administration](images/Dn715949.EPACSFacebook(AX.60).gif "ACS Facebook app administration")

3.  In the **Canvas URL** field, enter the namespace URL in the format:
    
    http://*ServerName*.accesscontrol.windows.net/

## Create relying party application \#1

An application in a relying party role acts as a Web service that can request a set of claims from a trusted claims provider. The application also consumes the claims that it receives from its configured claims provider. Use the following procedure to create one of two relying party applications. You will create relaying party application \#2 later in this document.

1.  In the left pane of the ACS Management Portal, click **Relying party applications**.

2.  Click **Add**.

3.  Enter a name for the relying party. For example: *Your\_company\_name* Enterprise Portal. This name is used only in the ACS Management Portal.

4.  Enter the name of a realm. A realm specifies where the authentication request will originate. This name can also be, for example, *Your\_company\_name* Enterprise Portal.

5.  Enter a return URL. ACS redirects to this URL after successful authentication. For this web site, the URL should be in the following format:
    
    https://\<host\_name\>:\<acs\_port\>/\_trust
    
    You can specify any available port. Make a note of this port number because you will specify it again when you create the secure site on the host machine.

6.  (Optional): Enter an error URL. If a user experiences an error, the web browser is redirected to this URL

7.  In the **Token format** field, specify **SAML1.1**.

8.  In the **Token encryption policy** field, specify **None**.

9.  In the Token lifetime (secs) field, enter a large number so that the token does not expire too frequently. For example, specify 86,400 seconds (24 hours).

10. Select the identify providers for this application.

11. In the **Rule group** section, create a new rule group.

12. Click **Save**.

## Configure the group

Use this procedure to configure the new rule group that you created in the previous procedure.

1.  Click **Add**.

2.  Select the Identity providers to configure. You can select one provider or all of the providers.

3.  In the **Input claim type** field, leave the default value of **Any**.

4.  In the **Input claim** field, leave the default value of **Any**.

5.  In the **Output claim type** field, click **Pass through first input claim type**.

6.  In the **Output claim value** field, click **Pass through first input claim value**.

7.  Click **Save**.

## Create a custom token signing certificate for the ACS site

This procedure describes how to create a custom token signing certificate by using Internet Information Services (IIS) manager. The signing certificate is used to encrypt communications between the ACS application and the claims-aware Enterprise Portal site. This procedure creates a self-signed certificate for a developer or test environment. When you deploy a claims-aware Enterprise Portal vendor registration site in a production environment, you must acquire a valid certificate from a certificate authority. In commands throughout this document, this certificate is referred to as the \<ACS\_signing\_cert\>.

1.  In IIS manager, in the center pane, click **Server Certificates**.

2.  In the right pane, click **Create Self-Signed Certificate**.

3.  Specify a friendly name for the certificate and click **OK**.

4.  In the middle pane, right-click the certificate you just created and click **Export**.

5.  Enter a path where you want to export the file and specify a password.

6.  From the Windows Run dialog box, type MMC.exe and press Enter.

7.  In Microsoft Management Console, click **File** \> **Add/Remove Snap-ins**. Add the **Certificates** snap-in.

8.  Click **Computer account** and then click **Local Computer**.

9.  Click **Finish**.

10. In Microsoft Management Console, expand **Certificates (Local Computer)** \> **Trusted Root Certification Authorities** \> **Certificates** and locate the certificate you just created.

11. Right-click the certificate and click **All Tasks\\Export**.

12. In the **Certificate Export Wizard**, select **No, do not export the private key** and retain all default settings. The wizard exports the certificate as a .cer file. Make a note of the path to this file because you will enter this information later in this topic.

13. Verify that with this procedure you have successfully created both the \<acs\_signing\_cert\>.pfx file and the \<acs\_signing\_cert\>.cer file.

14. In the ACS Management Portal, in the left pane, click **Certificate and keys**.

15. Above the **Token Signing** section, click the **Add** link.
    
    ![Windows Azure Certificates and Keys page](images/Dn715949.EPACSCertKeys(AX.60).gif "Windows Azure Certificates and Keys page")

16. In the **Used for** section, click **Relying Party Application** and select the relying party application that you created in the previous procedure.

17. In the **Type** section, verify that **X.509 Certificate** is selected.

18. In the **Certificate** section, browse to the \<acs\_signing\_cert\>.pfx file, enter in the password, and click **Save**.

19. In the **Primary** section, verify that **Make Primary** is selected.

20. Click **Save**.

## Create the claims-aware Enterprise Portal site

Use the procedures in this section to create a new SSL certificate for the claims-aware Enterprise Portal site and then create the site on a new SharePoint web application.

## Create an SSL certificate for the claims-aware site

You created a custom token signing certificate by using IIS manager in the previous section. You must now create a second SSL certificate for the claims-aware Enterprise Portal site. This procedure creates a self-signed certificate for a developer or test environment. When you deploy a claims-aware Enterprise Portal vendor registration site in a production environment, you must acquire a valid certificate from a certificate authority.


> [!IMPORTANT]
> <P>You cannot use the custom token signing certificate that you created earlier. That certificate is specific to ACS. You must create a second SSL certificate, as described below.</P>



1.  In IIS manager, in the center pane, click **Server Certificates**.

2.  In the right pane, click **Create Self-Signed Certificate**.

3.  Specify a friendly name for the certificate and click **OK**.

4.  In the middle pane, right-click the certificate you just created and click **Export**.

5.  Enter a path where you want to export the file and specify a password.

6.  From the Windows Run dialog box, type MMC.exe and press Enter.

7.  In Microsoft Management Console, click **File** \> **Add/Remove Snap-ins**. Add the **Certificates** snap-in.

8.  Click **Computer account** and then click **Local Computer**.

9.  Click **Finish**.

10. In Microsoft Management Console, expand **Certificates (Local Computer)** \> **Trusted Root Certification Authorities** \> **Certificates** and locate the certificate you just created.

11. Right-click the certificate and click **All Tasks\\Export**.

12. In the **Certificate Export Wizard**, select **No, do not export the private key** and retain all default settings. The wizard exports the certificate as a .cer file. Make a note of the path to this file because you will enter this information later in this topic.

## Create a claims-aware site on a new SharePoint web application

This section describes how to create a claims-aware Enterprise Portal site by using a Microsoft Windows PowerShell cmdlet. The cmdlet in this section first creates a claims-aware web application in SharePoint, and then deploys an Enterprise Portal site on that web application. If you are not familiar with Windows PowerShell cmdlets for Microsoft Dynamics AX, see [Administering Microsoft Dynamics AX by using Windows PowerShell](http://go.microsoft.com/fwlink/?linkid=235298) for more information.


> [!NOTE]
> <P>Windows PowerShell includes a security setting called the execution policy that determines how scripts are run. By default, the execution policy is set to <STRONG>Restricted</STRONG>, which prevents any scripts from running. To run the installation scripts for Microsoft Dynamics AX components, we recommend that you set the execution policy to <STRONG>RemoteSigned</STRONG> by using Set-ExecutionPolicy cmdlet. This setting allows you to run scripts that you’ve written and scripts that have been signed by a trusted publisher.</P>



1.  Open the Microsoft Dynamics AX 2012 Management Shell with administrator privileges. Click **Start** \> **Administrative Tools** \> right-click **Microsoft Dynamics AX 2012 Management Shell** and click **Run as administrator**.

2.  Enter the following command and press Enter.
    
    $Cred=Get-Credential

3.  When prompted, enter the credentials for the .NET Business Connector proxy account. The credentials must be the .NET Business Connector proxy account and password that were specified when Enterprise Portal binaries were installed earlier in this document. If you specify an account other than the .NET Business Connector proxy account, then the cmdlet overwrites the existing .NET Business Connector account, which can cause existing Enterprise Portal installations to stop working. Also note, this cmdlet designates the .NET Business Connector proxy account as the Enterprise Portal site administrator.

4.  Execute the following command, replacing “PathToSSLCert.pfx” with the path to the .PFX certificate file that you created in the previous procedure.
    
    $SSLCert = Get-PfxCertificate "PathToSSLCert.pfx"
    
    When prompted, enter the password that you specified when you created the SSL certificate.

5.  On the Enterprise Portal server, execute the **New-AXClaimsAwareEnterprisePortalServer** cmdlet. For descriptions of the required parameters and syntax, see [New-AXClaimsAwareEnterprisePortalServer](http://go.microsoft.com/fwlink/?linkid=217573) on TechNet.
    

    > [!IMPORTANT]
    > <P>The following example shows the cmdlet with the required parameters. For the port value, you must specify the port value of the Relying Party Application.</P>

    
    new-AXClaimsAwareEnterprisePortalServer -Credential $Cred -Port 8000 -SSLCertificate $SSLCert
    
    This cmdlet can take several minutes to be completed. After the cmdlet is completed, you can access a new instance of Enterprise Portal at the following URL: https://*ServerName*:*RelyingPartyAppPortNumber*/sites/DynamicsAx.
    
    The site is also listed on the **System administration** \> **Enterprise Portal** \> **Web sites** form.

Browse this site to verify that the command was executed properly. The site displays a certificate warning. You will not see this warning when you acquire a valid certificate from a certificate authority. You can ignore this warning for now and proceed to the site.

## Establish claims mapping

Use the following PowerShell commands to map three different claims to the ACS service.

1.  From the SharePoint Management Shell, execute the following three commands:
    
    1.  $claim1 = New-SPClaimTypeMapping -IncomingClaimType "http://schemas.xmlsoap.org/ws/2005/05/identity/claims/nameidentifier" -IncomingClaimTypeDisplayName "ACS Name Identifier Claim" -LocalClaimType "http://schemas.microsoft.com/custom/claim/type/2013/07/acs-nameidentifier"
    
    2.  $claim2 = New-SPClaimTypeMapping -IncomingClaimType "http://schemas.microsoft.com/accesscontrolservice/2010/07/claims/identityprovider" -IncomingClaimTypeDisplayName "ACS Identity Provider" -LocalClaimType "http://schemas.microsoft.com/custom/claim/type/2013/07/acs-identityprovider"
    
    3.  $claim3 = New-SPClaimTypeMapping -IncomingClaimType "http://schemas.xmlsoap.org/ws/2005/05/identity/claims/name" -IncomingClaimTypeDisplayName "ACS username" -LocalClaimType "http://schemas.microsoft.com/custom/claim/type/2013/07/acs-username"

2.  Execute the following commands from the SharePoint Management Shell to register a token:
    
    1.  $acscert = Get-PfxCertificate \<ACS\_signing\_cert\>
    
    2.  New-SPTrustedIdentityTokenIssuer -Name \<name\_of\_your\_SP\_Trusted\_Identity\_Provider\> -Description \<description\_of\_your\_SP\_Trusted\_Identity\_Provider\> -Realm \<realm\_of\_your\_SP\_trusted\_identity\_provider\> -ImportTrustCertificate $acscert -SignInUrl "https://\<acs\_namespace\>.accesscontrol.windows.net/v2/wsfederation" -ClaimsMappings $claim1,$claim2,$claim3 -IdentifierClaim $claim1.InputClaimType
        
        The following example shows parameters for Contoso Corporation’s test environment
        
        New-SPTrustedIdentityTokenIssuer -Name “AzureACS” -Description “Azure ACS” -Realm urn:Contoso:AzureACS -ImportTrustCertificate $acscert -SignInUrl "https://ContosoTestServer1.accesscontrol.windows.net/v2/wsfederation" -ClaimsMappings $claim1,$claim2,$claim3 -IdentifierClaim $claim1.InputClaimType
    
    3.  Execute the following commands in the SharePoint Management Shell to import the \<ACS\_signing\_cert\> as trusted root certificate in SharePoint:
        
        1.  $cert = New-Object System.Security.Cryptography.X509Certificates.X509Certificate2($acscert)
        
        2.  $spcert = New-SPTrustedRootAuthority -Certificate $cert -Name "ACSTokenSigningCert"

## Configure the authentication provider in SharePoint Central Administration

Use the following procedure to configure the “Azure ACS” identity provider for your claims-aware Enterprise Portal site.

1.  In SharePoint Central Administration, click Manage web applications and then click the claims-aware Enterprise Portal site you created earlier in this topic.

2.  Click **Authentication providers** and then click **Default**.

3.  In the **Trusted Identity provider** list, verify that **AzureACS** is selected.
    
    ![The Azure authentication provider in SharePoint](images/Dn715949.EPACSSP(AX.60).gif "The Azure authentication provider in SharePoint")

4.  From the SharePoint Central Administration home page, click **Security**.

5.  Under **Users** click **Specify web application user policy**.

6.  Click **Add Users**.

7.  In the **Zones** list, click **Default**, and then click **Next**.

8.  In the **Users** text box, enter: All Users\\All Users (AzureACS).
    
    ![Configure Azure users in SharePoint](images/Dn715949.EPACSUsers(AX.60).gif "Configure Azure users in SharePoint")

9.  Select **Full Read** permissions and then click **Finish**.

## Verify sign in

1.  Enter the ACS URL for your Enterprise Portal site in a web browser. For example: https://ContosoTestServer1:8000/Sites/DynamicsAx.

2.  In the **Sign In** list, select **AzureACS**.
    
    ![EP ACS sign in dialog](images/Dn715949.EPACSSignin(AX.60).gif "EP ACS sign in dialog")

3.  When prompted, specify valid credentials for one of the identity providers listed.

## Create relying party application \#2

Use the following procedure to create a relying party application for the public Enterprise Portal site.

1.  In the left pane of the ACS Management Portal, click **Relying party applications**.

2.  Click **Add**.

3.  Enter a name for the relying party. For example: *Your\_company\_name* Unsolicited Vendor Sign-up. This name is used only in the ACS Management Portal.

4.  Enter the name of a realm. A realm specifies where the authentication request will originate. This name can also be, for example, *Your\_company\_name* Unsolicited Vendor Sign-up.

5.  Enter a return URL. ACS redirects to this URL after successful authentication. For a public web site, the URL should be in the following format:
    
    http://*ServerName*:*Port*/sites/Public/Enterprise%20Portal/VendRequestSignUp.aspx
    
    Specify the port where you deployed the public Enterprise Portal site.

6.  (Optional): Enter an error URL. If a user experiences an error, the web browser is redirected to this URL

7.  In the **Token format** field, specify **SAML1.1**.

8.  In the **Token encryption policy** field, specify **None**.

9.  In the **Token lifetime (secs)** field, enter a large number so that the token does not expire too frequently. For example, specify 86,400 seconds (24 hours).

10. Select the identify providers for this application.

11. In the **Rule group** section, create a new rule group.

12. Click **Save**.

## Configure a rule group for the public site

Use this procedure to configure a rule group for the public Enterprise Portal site.

1.  Click **Add**.

2.  Select the Identity providers to configure. You can select one provider or all of the providers.

3.  In the **Input claim type** field, leave the default value of **Any**.

4.  In the **Input claim** field, leave the default value of **Any**.

5.  In the **Output claim type** field, click **Pass through first input claim type**.

6.  In the **Output claim value** field, click **Pass through first input claim value**.

7.  Click **Save**.

## Configure the login page for the public Enterprise Portal site

1.  On the Azure ACS management portal, click **Development** \> **Application Integration** \> **Login pages**.

2.  Select relaying party application \#1. (The first relaying party application you created in this documented.)

3.  Copy the link in the **Option 1: Link to an ACS-hosted login page** field.

4.  In IIS Manager, select the Enterprise Portal public site web application.

5.  In the center pane under **ASP.NET**, click **Application Settings**.

6.  Click **Add** and specify the following:
    
    **Name**: STSSignInURL
    
    **Value**: The link that you copied in step 2 of this procedure.

7.  Click **OK**.

8.  On the Enterprise Portal server, open the C:\\inetpub\\wwwroot\\wss\\VirtualDirectories\\ directory.

9.  Open the directory for the Enterprise Portal public site. For example, directory 80.

10. Open the web.config file in Visual Studio or in a text editor like Notepad.

11. Choose one of the following options:
    
    1.  For SharePoint 2010, add the following to the \<configSections\> node:
        
            <section name="microsoft.identityModel" type="Microsoft.IdentityModel.Configuration.MicrosoftIdentityModelSection, Microsoft.IdentityModel, Version=3.5.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35" />
            Add the following to the <configuration> node:
            <microsoft.identityModel>
                <service>
                  <securityTokenHandlers>
                    <securityTokenHandlerConfiguration >
                      <audienceUris>
                        <add value="http://<host_name>/" />
                      </audienceUris>
                      <issuerNameRegistry type="Microsoft.IdentityModel.Tokens.ConfigurationBasedIssuerNameRegistry, Microsoft.IdentityModel, Version=3.5.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35">
                        <trustedIssuers>
                          <add thumbprint="<Thumbprint>" name="<Any nonempty string>" />
                        </trustedIssuers>
                      </issuerNameRegistry>
                    </securityTokenHandlerConfiguration>
                  </securityTokenHandlers>
                </service>
              </microsoft.identityModel>
    
    2.  For SharePoint 2013, replace the following parameter:
        
            <issuerNameRegistry type="Microsoft.SharePoint.IdentityModel.SPPassiveIssuerNameRegistry, Microsoft.SharePoint, Version=15.0.0.0, Culture=neutral, PublicKeyToken=71e9bce111e9429c" />
        
        With this parameter:
        
            <issuerNameRegistry type="Microsoft.IdentityModel.Tokens.ConfigurationBasedIssuerNameRegistry, Microsoft.IdentityModel, Version=3.5.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35">
              <trustedIssuers>
                <add thumbprint="<thumbprint>" name="Unsolicited Vendor Request Token Signing Certificate" />
              </trustedIssuers>
            </issuerNameRegistry>
        
        Replace \<Thumbprint\> with the thumbprint of the token signing certificate for the Azure ACS relying party application. To locate the thumbprint, click the certificate at the bottom of the relying party application. Copy the thumbprint.
        
        ![Location to copy the certificate thumbprint](images/Dn715949.EPACSThumbprint(AX.60).gif "Location to copy the certificate thumbprint")

12. Enter the URL of your public Enterprise Portal site a web browser. For example: http://*ServerName*:*Port*/sites/Public/Enterprise%20Portal/VendRequestSignUp.aspx. The web browser redirects you to the ACS sign in page where you can select an identity provider and log in.

## Configure Enterprise Portal parameters

You must configure the following parameters in the Microsoft Dynamics AX client.

1.  Click **System administration** \> **Setup** \> **Enterprise Portal** \> **Enterprise Portal parameters**.

2.  Click the **User provisioning** page.

3.  In the **Unsolicited vendor authentication** list, select **Azure ACS**.

4.  In the **Unsolicited Vendor Domain** field, enter AzureACS.

5.  In the **Vendor authentication method** list, select **Azure ACS**.

## Next steps

You must configure the vendor on-boarding workflow process in the Microsoft Dynamics AX client. The process is described in detail in the following blog [Step-by-step walkthrough of the vendor on-boarding process](http://go.microsoft.com/fwlink/?linkid=392074).

## See also

[Configuring Enterprise Portal for vendor requests](configuring-enterprise-portal-for-vendor-requests.md)

[Deploy a claims-mode Enterprise Portal site](deploy-a-claims-mode-enterprise-portal-site.md)

  


