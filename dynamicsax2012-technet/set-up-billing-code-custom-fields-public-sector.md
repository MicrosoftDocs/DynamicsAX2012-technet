---
title: Set up billing code custom fields (Public sector)
TOCTitle: Set up billing code custom fields (Public sector)
ms:assetid: 1644b031-3278-4b05-89e1-4becb5119ad4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208513(v=AX.60)
ms:contentKeyID: 36056255
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- custom fields
- public sector
- billing code custom fields
- custom billing code fields
- custom invoice lines
- public sector custom fields
audience: Application User
ms.search.region: Denmark, France
---

# Set up billing code custom fields (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Billing code custom fields allow you to collect values for billing code fields when free text invoices are created. For example, a pet license invoice line can request the type of animal and spay/neuter status.

After you create a billing code custom field, it is assigned to a billing code so that users can access it when the billing code is selected on a free text invoice line. Each billing code custom field can only be assigned to one billing code, and you cannot delete a billing code custom field after it has been used on a free text invoice line.


> [!NOTE]
> <P>Billing code custom fields are available only if the configuration key for Public sector is selected.</P>



## Create billing code custom fields

Complete the steps below to create a custom billing code field.

1.  Click **Accounts receivable** \> **Setup** \> **Billing code custom fields**.

2.  Click **New** to create a line for a new billing code custom field.

3.  Enter a unique code in the **Name** field, such as **PETLIC**.

4.  In the **Type** field, select field type from the list and enter the related data:
    
      - **Currency** – Custom fields of this type will accept currency numbers only with two decimal places stored. You can specify a default value for this field and set minimum and maximum values that are permitted for this field.
    
      - **Decimal** – Custom fields of this type will accept decimal numbers only with four decimal places stored. You can specify a default value for this field and set minimum and maximum values permitted for this field.
    
      - **Text** – Custom fields of this type can hold any kind of text, and any input entered into them will be interpreted as text. You can specify a default value for this field and set a maximum field length that is permitted for this field.
    
      - **Integer** – Custom fields of this type will accept whole numbers only. You can specify a default value for this field and set minimum and maximum values that are permitted for this field.
    
      - **Boolean** – Custom fields of this type allow yes/no selections by the user. You can set the default value to “Yes” or “No.”
    
      - **Date** – Custom fields of this type will accept dates only. The date is stored as mm/dd/yyyy. You can set a default date for this field.

5.  On the **Description** tab, in the **Usage description** field, describe how the custom field should be used. This is for internal purposes only and is not visible to the user.

6.  In the **Help text** field, enter status bar information that will assist users with their data entry.
    

    > [!NOTE]
    > <P>This field is limited to 100 characters.</P>



7.  Close the **Billing code custom fields** form.

## Assign billing code custom fields to billing codes

After you have created a billing code custom field, you must assign it to a billing code and activate it so that it is available to users when the billing code is used on free text invoices.

1.  Click **Accounts receivable** \> **Setup** \> **Billing codes**.

2.  Select the billing code to assign the custom billing code field to.

3.  Click the **Custom fields** tab.

4.  Click **Add**.

5.  Double-click each billing code custom field that you would like to add to the billing code.

6.  Click **OK**.

7.  Select the **Active** checkbox to activate the billing code custom field.

## See also

[Set up billing codes (Public sector)](set-up-billing-codes-public-sector.md)

  


