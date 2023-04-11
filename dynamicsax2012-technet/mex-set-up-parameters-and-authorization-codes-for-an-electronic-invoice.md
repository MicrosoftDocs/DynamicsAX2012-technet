---
title: (MEX) Set up parameters and authorization codes for an electronic invoice
TOCTitle: (MEX) Set up parameters and authorization codes for an electronic invoice
ms:assetid: a05f20e5-456e-4191-af93-93c44bde83e6
ms:mtpsurl: https://technet.microsoft.com/library/Hh209448(v=AX.60)
ms:contentKeyID: 36058768
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- parameters
- (MEX)
- set up
- electronic invoice
- authorization code
audience: Application User
ms.search.region: Mexico
---

# (MEX) Set up parameters and authorization codes for an electronic invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Electronic invoice parameters** form to set up parameters for generating electronic invoices. You can select the digital certificate, XML schema definition (XSD) version, and email template to use to generate electronic invoices and issue them to the Servicio de Administración Tributaria (SAT). You can also select the algorithm to use to generate the digital stamp.

Use the **Authorization numbers** form to set up folio numbers for an electronic invoice. A folio number is an invoice number that consists of the series, number sequences, and authorization numbers of the electronic invoice. You can obtain a list of folio numbers from the Sistema de comprobantes fiscales digitales CFD Plus (SICOFI) program. The Servicio de Administración Tributaria (SAT) uses the folio numbers to identify the issuers of electronic invoices. You can also define a range of invoice numbers that the series, number sequences, and authorization numbers are assigned to. The range of invoice numbers can contain gaps, but the numbers cannot overlap.

## Enable the CFD parameters

If your organization uses Microsoft Dynamics AX to generate electronic invoices and then validates them manually on a government website, use this procedure to set up parameters for electronic invoices.

1.  Click **Organization administration** \> **Setup** \> **EInvoice** \> **Electronic invoice parameters** . In the left pane, click **CFD**, and then select the **Enable CFD (electronic invoices)** check box.

2.  In the **CFD version** field, select the XSD version to use to generate and issue an electronic invoice:
    
      - \<Blank\> – Do not specify an XSD version to use to generate and issue the electronic invoice.
    
      - **2.0** – Use XSD 2.0 to generate and issue the electronic invoice.
    
      - **2.2** – Use XSD 2.2 to generate and issue the electronic invoice.

3.  In the **CFD XML schema file** field, specify the path of the XML schema file that was provided by the SAT.

4.  In the **Certificate** field, select the digital certificate to use to generate and issue an electronic invoice.
    

    > [!NOTE]
    > <P>You must import the digital certificate to the computer where Application Object Server (AOS) is running. For more information, see <A href="mex-configure-the-digital-certificate-in-microsoft-windows-server-2008.md">(MEX) Configure the digital certificate in Microsoft Windows Server 2008</A>.</P>



5.  In the **CFD digest algorithm** field, select the algorithm method:
    
      - \<Blank\> – Do not use an algorithm.
    
      - **SHA-1** – Use the SHA-1 algorithm.

6.  In the **E-mail ID** field, select the identification code of the email template. For more information, see [(MEX) Set up email parameters for an electronic invoice](mex-set-up-email-parameters-for-an-electronic-invoice.md).
    

    > [!NOTE]
    > <P>You can view the status of an outgoing email message in the <STRONG>E-mail sending status</STRONG> form. For more information, see <A href="https://technet.microsoft.com/library/aa584203(v=ax.60)">E-mail sending status (form)</A>.</P>



7.  Select the **Send report file - PDF** check box to attach the .pdf file of an electronic invoice to the email message when the invoice is posted.
    

    > [!NOTE]
    > <P>The .pdf file is attached to the email message only if you select <STRONG>PDF</STRONG> in the <STRONG>File format</STRONG> field in the <STRONG>Printer setup</STRONG> form. For more information, see <A href="mex-set-up-print-management-options-for-an-electronic-invoice.md">(MEX) Set up print management options for an electronic invoice</A>.</P>



8.  Set up authorization numbers. See the “Set up authorization numbers” procedure later in this topic.

## Enable the CFDI parameters

If your organization generates electronic invoices by using Microsoft Dynamics AX and then sends the invoices to be verified and certified by a digital signature service provider (PAC), use this procedure to set up parameters for electronic invoices.

1.  Click **Organization administration** \> **Setup** \> **EInvoice** \> **Electronic invoice parameters** . In the left pane, click **CFDI**, and then select the **Enable CFDI (electronic invoice)** check box.

2.  In the **Certificate** field, select the digital certificate to use to generate and issue an electronic invoice.

3.  In the **CFDI version** field, select **3.2**. This is the XSD version that is used to generate and issue an electronic invoice.

4.  In the **CFDI XML schema file** field, enter the path of the XML schema file that was provided by the SAT.

5.  In the **PAC certificate** field, select the certificate to use to establish a secure connection between Microsoft Dynamics AX and the PAC web service.

6.  In the **Environment** field, select the environment to use to integrate Microsoft Dynamics AX and the PAC service.

7.  In the **PAC account** field, select the PAC name to use to request the digital stamp.

8.  Select the **Send mail** check box to allow other users to send electronic invoice documents by email after the invoices have been approved by the PAC.

9.  Select the type of email message to use when you send electronic invoices by email.

10. Select the **Send report file - PDF** check box to include the electronic invoice as a .pdf file when the invoice is sent by email.

11. Set up authorization numbers. See the “Set up authorization numbers” procedure later in this topic.

## Set up authorization numbers

Use this procedure to set up authorization numbers for electronic invoices. This procedure applies whether you use the CFD method or the CFDI method to generate electronic invoices.

1.  In the **Electronic invoice parameters** form, click **Authorization numbers**.

2.  In the **Authorization numbers** form, create a new line.

3.  In the **Authorization code** field, enter the authorization code that was assigned by the Servicio de Administración Tributaria (SAT) for each set of electronic invoices.

4.  In the **Year** field, enter the year in which the SAT assigned the authorization code for the set.

5.  In the **Series** field, enter the series for the set of electronic invoices.

6.  In the **Number sequence code** field, select the number sequence code for the set. You can set up a number sequence code in the **Number sequences** form.

7.  In the **From number** and **To number** fields, enter the starting sequence number and the ending sequence number for the set.

## Set up the PAC web service

If you enabled the CFDI parameters, use this procedure to set up the PAC web service to use to integrate Microsoft Dynamics AX and the PAC service provider.

1.  In the **Electronic invoice parameters** form, on the left pane, click **CFDI**, and then click **PAC web service**.

2.  In the **Method name** field, select the name of the method to use to generate the XML message.

3.  In the **Web service** field, select to request a digital stamp.

4.  In the **Internet address** field, enter the web address for the PAC service.

5.  Click **Generate** to generate references to the PAC web service.
    
    A reference to the PAC web service is also created in **AOT** \> **References** to allow Microsoft Dynamics AX to connect to the web service.

## See also

[(MEX) About electronic invoices](mex-about-electronic-invoices.md)

[(MEX) Electronic invoice parameters (form)](https://technet.microsoft.com/library/hh242214\(v=ax.60\))

[(MEX) Authorization numbers (form)](https://technet.microsoft.com/library/hh209642\(v=ax.60\))

[Number sequences (form)](https://technet.microsoft.com/library/hh209531\(v=ax.60\))

  


