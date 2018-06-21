---
title: (BRA) Calculate withholding tax for the purchase of services
TOCTitle: (BRA) Calculate withholding tax for the purchase of services
ms:assetid: a54b72ad-618c-4411-bbb5-59598fe9e77a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn126107(v=AX.60)
ms:contentKeyID: 52075265
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BR - 00034
---

# (BRA) Calculate withholding tax for the purchase of services [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Journal voucher** form to enter and post payments that you make to a vendor for the purchase of items or services. When you post a vendor payment journal, the withholding tax group that is set up for the vendor is used to calculate the withholding tax on the transaction.


> [!NOTE]
> <P>To indicate that a vendor is liable to pay withholding tax, you must select the <STRONG>Calculate withholding tax</STRONG> check box and select a withholding tax group for the vendor. For more information, see <A href="bra-set-up-a-withholding-tax-group-and-attach-it-to-a-customer-or-vendor.md">(BRA) Set up a withholding tax group and attach it to a customer or vendor</A>.</P>



Use the following procedures to calculate the withholding tax transactions when you can pay for items or services by using the settlement process.

## Set up withholding tax for services

1.  Click **Product information management** \> **Common** \> **Released products**. Select a product, and then click **Edit**.

2.  On the **Purchase** FastTab, select the **Calculate withholding tax** check box to enable the calculation of withholding tax for an item or service.

3.  In the **Item withholding tax group** field, select the item withholding tax group that is created for Program de Integração Social (PIS), Contribuição para Financiamento da Seguridade Social (COFINS), or Contribuição Social sobre Lucro Líquido (CSLL).

## Create a purchase order

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**. Create a payment journal, and then click **Lines** to open the **Journal voucher** form.

2.  In the **Account** field, select the vendor account that is updated with the withholding tax for a service. The **Withholding tax group** field is updated with the withholding tax group that is assigned to the vendor in the **Vendors** form. For more information, see [(BRA) Journal voucher - Vendor payment journal (modified form)](https://technet.microsoft.com/en-us/library/jj933534\(v=ax.60\)).

3.  Click **Functions** \> **Settlement**.

4.  Select the **Mark** check box for each transaction that you want to settle. The withholding tax amount for those transactions is calculated and displayed on the **Withholding tax** tab.

5.  Click **OK** to close the form.

6.  In the **Journal voucher** form, in the **Tax withhold edit status** field, one of the following statuses is displayed for the payment journal line:
    
      - **Not applicable** – The withholding tax codes with a **Percentage of gross amount in month** origin do not apply to any invoice lines that are selected in the payment journal line.
    
      - **Opened** – The withholding tax code with a **Percentage of gross amount in month** origin applies to any selected invoice in the payment journal line, and the invoice is not considered in the calculation of the withholding tax for other invoices. The payment journal line that is set to **Opened** is available for editing.
    
      - **Closed** – The withholding tax code with a **Percentage of gross amount in month** origin applies to any invoice line of the selected invoice in the payment journal line, and the invoice is considered in the calculation of withholding tax for other invoices. The payment journal line that is set to **Closed** is not available for editing.

7.  In the **Offset account type** field, select **Bank**.

8.  Click **Post** \> **Post** to post the vendor payment journal.

## Calculate withholding tax for service purchases

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**. Create a payment journal, and then click **Lines** to open the **Journal voucher** form.

2.  In the **Account** field, select the vendor account that is updated with the withholding tax for a service. The **Withholding tax group** field is updated with the withholding tax group that is assigned to the vendor in the **Vendors** form. For more information, see [(BRA) Journal voucher - Vendor payment journal (modified form)](https://technet.microsoft.com/en-us/library/jj933534\(v=ax.60\)).

3.  Click **Functions** \> **Settlement**.

4.  Select the **Mark** check box for each transaction that you want to settle. The withholding tax amount for those transactions is calculated and displayed on the **Withholding tax** tab.

5.  Click **OK** to close the form.

6.  In the **Journal voucher** form, in the **Tax withhold edit status** field, one of the following statuses is displayed for the payment journal line:
    
      - **Not applicable** – The withholding tax codes with a **Percentage of gross amount in month** origin do not apply to any invoice lines that are selected in the payment journal line.
    
      - **Opened** – The withholding tax code with a **Percentage of gross amount in month** origin applies to any selected invoice in the payment journal line, and the invoice is not considered in the calculation of the withholding tax for other invoices. The payment journal line that is set to **Opened** is available for editing.
    
      - **Closed** – The withholding tax code with a **Percentage of gross amount in month** origin applies to any invoice line of the selected invoice in the payment journal line, and the invoice is considered in the calculation of withholding tax for other invoices. The payment journal line that is set to **Closed** is not available for editing.

7.  In the **Offset account type** field, select **Bank**.

8.  Click **Post** \> **Post** to post the vendor payment journal.

## See also

[Reverse settlements](reverse-settlements.md)

[(BRA) Reverse a check or Bordero payment](bra-reverse-a-check-or-bordero-payment.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

