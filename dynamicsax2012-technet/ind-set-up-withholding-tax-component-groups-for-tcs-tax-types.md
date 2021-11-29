---
title: (IND) Set up withholding tax component groups for TCS tax types
TOCTitle: (IND) Set up withholding tax component groups for TCS tax types
ms:assetid: 252126d2-d858-48ea-a1ae-abfa9be5d86e
ms:mtpsurl: https://technet.microsoft.com/library/JJ664562(v=AX.60)
ms:contentKeyID: 49385642
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up withholding tax component groups for TCS tax types 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must set up withholding tax component groups for TCS tax types, such as Alcohol and Timber, and create TCS certificates for each TCS component group. The TCS certificates created for TCS component groups are issued to customers or vendors. The date, amount, and the customer or vendor that the TCS certificate is issued for is automatically updated for each TCS component group.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



## Set up withholding tax component groups

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **India** \> **Withholding tax component groups**.

2.  Select **TCS** in the **Tax type** field to set up withholding tax component groups for TCS tax type.

3.  Press CTRL+N to create a new line.

4.  Enter a name for the TCS component group in the **Withholding tax component group** field.

5.  Enter a description for the TCS component group in the **Description** field.

6.  Select the residential status the TCS component group comes under in the **Status** field. The options are **Resident** and **Non-resident**.

7.  Enter the section code that is applied to the TCS component group in the **Section code** field.

## Create TCS certificates

You can create or cancel TCS certificates for the TCS withholding tax component group in the **TCS Certificates** form.

1.  Click **Certificate** on the **Withholding tax component groups** form to open the **Certificates** form.

2.  Click **Create certificates** to open the **Create certificates** form to create TCS certificates.

3.  In the **Prefix** field, enter the prefix to generate the TCS certificate numbers.

4.  In the **From** field, enter the starting number to start the TCS certificate numbers from.

5.  In the **Quantity** field, enter the total number of TCS certificates to be created for the specified range.

6.  Click **OK** to create TCS certificates in the **Certificates** form. You can view the TCS certificate numbers that are created with a specified prefix and a specified quantity in the **Certificate number** field.
    
    For example, if you specify the prefix as Certificate\_TCS\_, starting number as 1, and the quantity as 1, the certificate number is created as Certificate\_TCS\_1.
    
    One of the following statuses is displayed for the TCS certificate in the **Status** field:
    
      - **Created** – This status is displayed for a newly created TCS certificate.
    
      - **Issued** – The certificate status changes from **Created** to **Issued** after the TCS certificate has been issued to a customer or vendor.
    
      - **Canceled** – You can change the status to **Canceled** for a TCS certificate that has **Created** status. The certificates that are canceled will not be issued to customers or vendors. You cannot change the status of TCS certificates with **Canceled** status.
    
      - The customer or vendor account number the TCS certificate is issued for is displayed in the **Customer/Vendor** field.
    
      - The TCS amount the TCS certificate is issued for is displayed in the **Amount** field.

## Delete TCS certificates with Created status

1.  On the **Certificates** form, click **Delete certificates**.
    

    > [!WARNING]
    > <P>You can only delete certificates in the <STRONG>Created</STRONG> status.</P>



2.  Specify the starting and ending range to delete TCS certificates in the **From** and **To** fields.
    

    > [!NOTE]
    > <P>Only the TCS certificates with a <STRONG>Created</STRONG> status are deleted in the specified range.</P>



3.  Click **OK**. The certificates in the specified range no longer appear on the **Certificates** form.

4.  Press CTRL+S or close the **Certificates** form to return to the **Withholding tax component groups** form.

5.  Press CTRL+S or close the form.

## Print duplicate TCS certificates with Created status

1.  On the **Certificates** form, click **Print** and then click **Duplicate certificate** to print duplicate certificates with an **Issued** status.
    

    > [!NOTE]
    > <P>The original Form 27D certificates are generated for the customer in the <STRONG>Certificates</STRONG> form.</P>



2.  Press CTRL+S or close the **Certificates** form to return to the **Withholding tax component groups** form.

3.  Press CTRL+S or close the form.

## See also

[(IND) Withholding tax component groups (form)](https://technet.microsoft.com/library/jj678017\(v=ax.60\))

[(IND) Certificates (form)](https://technet.microsoft.com/library/jj678024\(v=ax.60\))

[(IND) Create certificates (form)](https://technet.microsoft.com/library/jj664655\(v=ax.60\))

[(IND) Delete certificates (form)](https://technet.microsoft.com/library/jj664659\(v=ax.60\))

  


