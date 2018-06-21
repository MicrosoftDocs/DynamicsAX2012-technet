---
title: Create a security file for Retail deployment
TOCTitle: Create a security file for Retail deployment
ms:assetid: a66c81d5-ff04-4ecb-8a89-c38772390d81
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn858397(v=AX.60)
ms:contentKeyID: 63417190
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.retaildeploymentcertificates
- Forms.retaildeploymentcredentials
dev_langs:
- xml
---

# Create a security file for Retail deployment [AX 2012]


This topic describes how to create a security file that can be used by Retail mass deployment tools.

To set up and secure communication among the various Retail components, you must provide credentials and obtain certificates. During deployment, you need a way to provide this information without allowing too many people access to it. You can do this by saving credentials and certificate information in a clear-text xml file that is stored on a secure file share at headquarters. This type of file is called a security file. By allowing only deployment tools and a limited number of users access to security files, you help make your credentials and certificates more secure.


> [!NOTE]
> <P>The deployment tools for Retail components support security files starting in Microsoft Dynamics AX 2012 R3 Cumulative Update 8.</P>



A security file is required when you use mass deployment tools to deploy the following components.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Requires a certificate</p></th>
<th><p>Requires credentials</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Channel database</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Commerce Data Exchange: Real-time Service</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p>Commerce Data Exchange: Async Client</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Commerce Data Exchange: Async Server</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p>Retail POS</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Retail Server</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p>Retail Hardware Station</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
</tbody>
</table>


## Create a security file

Complete the following procedure to create a security file in XML format and its corresponding .xsd file.


> [!IMPORTANT]
> <P>We strongly recommend that you create a different security file for each store.</P>



Outside of stores, it does not matter how you group credentials and certificates in a security file. For example, you could create one security file for credentials and one security file for certificates.

1.  Create a secure shared network folder.
    
    Limit access to this share to only domain users who need the information to complete deployment. A self-service user does not require access to the secured location. A self-service user needs to know only the display name that identifies the credential set or certificate information in the file. The deployment tool accesses the correct file and obtains the necessary information.

2.  Create a new .xml file using a tool such as Notepad.
    
      - You can copy the code from the Example security file in this topic.
    
      - Create a section for each set of credentials and each certificate that will be used in the deployment.
        
        For a set of credentials, the XML should be formatted as in the following example.
        
        ``` xml
        <Credential ID="ExpressDeploymentAdmin">
            <UserName>domain\user</UserName>
            <Password>password2</Password>
        </Credential>
        ```
        
        For a certificate, the XML should be formatted as in the following example.
        
        ``` xml
        <Certificate ID="ExpressDeploymentSSL">
            <Path>AsyncServer/connection.pfx</Path>
            <Password>password1</Password>
        </Certificate>
        ```
    
      - Save the file as \<FileName\>.xml in the secure shared folder.

3.  Optional. Create a corresponding .xsd file by using a tool such as Notepad. Perform this step if you would like to validate your modified XML file using a tool such as Visual Studio.
    
      - You can copy the code from the Example .xsd file in this topic.
    
      - Save the file as \<FileName\>.xsd in the secure shared folder.

## Enter the path to the security file in Microsoft Dynamics AX

To use the security file in a deployment, you must enter information about it in Microsoft Dynamics AX.

If the security file contains information about certificates, complete the following procedure.

1.  Click **Retail** \> **Setup** \> **Retail mass-deployment** \> **Security** \> **Retail deployment certificates**.

2.  Create a new line for each certificate ID. Enter the location of the security file and the identifier for the certificate.
    
    If your certificates are in multiple security files, enter them in this form.

If the security file contains credentials, complete the following procedure.

1.  Click **Retail** \> **Setup** \> **Retail mass-deployment** \> **Security** \> **Retail deployment credentials**.

2.  Create a new line for each credential ID. Enter the location of the security file and the identifier for the credentials.
    
    If your credentials are in multiple security files, enter them in this form.

## Example XML

For an example of XML to use in security files, click **Security file example** in the **Retail deployment certificates** form or the **Retail deployment credentials** form. You can also copy and paste one of the following examples to get started creating a security file or an .xsd file.

### ![Dn858397.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn858397.collapse_all(en-us,AX.60).gif")Example security file

The security file contains the credential and certificate information that is used in Retail deployments.

``` xml
<?xml version="1.0" encoding="utf-8" standalone="yes"?>
<SecurityInformation xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="AXRetail.xsd" xmlns="AXRetail">
     <Certificate ID="ExpressDeploymentSSL">
          <Path>AsyncServer/connection.pfx</Path>
          <Password>password1</Password>
     </Certificate>

     <Credential ID="ExpressDeploymentAdmin">
           <UserName>domain\user</UserName>
           <Password>password2</Password>
     </Credential>

</SecurityInformation>
```

### ![Dn858397.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn858397.collapse_all(en-us,AX.60).gif")Example .xsd file

The .xsd file is used to validate the XML in the security file. The .xsd file defines which elements and attributes are permitted and in which order.

``` xml
<?xml version="1.0" encoding="utf-8">
<xs:schema attributeFormDefault="unqualified" xmlns:xs="http://www.w3.org/2001/XMLSchema" version="6.3.0" xmlns:r="AXRetail">
  <xs:simpleType name="noEmptyString">
    <xs:restriction base="xs:string">
      <xs:length value="1" />
      <xs:whiteSpace value="collapse" />
      <xs:pattern value="[A-Za-z0-9!@#$%‘*+,\\/=?^_‘[|]~-}*[A-Za-z0-9!#@$%‘*+.\\/=?^_‘{|}~-]*"/>
    </xs:restriction>
  </xs:simpleType>

  <xs:simpleType name="relativePath">
    <xs:restriction base="xs:string">
    </xs:restriction>
  </xs:simpleType>
            </xs:schema>
```

## See also

[Set up a self-service Retail deployment](set-up-a-self-service-retail-deployment.md)

[Mass deploy Retail components by using System Center Configuration Manager](mass-deploy-retail-components-by-using-system-center-configuration-manager.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

