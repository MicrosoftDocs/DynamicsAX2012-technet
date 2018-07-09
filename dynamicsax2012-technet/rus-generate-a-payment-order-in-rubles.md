---
title: (RUS) Generate a payment order in rubles
TOCTitle: (RUS) Generate a payment order in rubles
ms:assetid: 01e8e5b6-4079-4cd5-b6ad-12db3cb93d74
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711346(v=AX.60)
ms:contentKeyID: 49387164
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Generate a payment order in rubles [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  On the **Overview** tab, press CTRL+N to create a new line.

3.  In the **Date** field, select the date of payment.

4.  In the **Account** field, select the vendor account.

5.  In the **Transaction text** field, enter text that describes the transaction.

6.  In the **Debit** field, enter the sum of the payment.

7.  In the **Offset account type** field, select the account type for the selected account.

8.  In the **Offset account** field, select the offset account for the transaction.

9.  In the **Currency** field, select the currency code.

10. In the **Purpose text** field, enter any text that must be reflected in the payment order.
    

    > [!NOTE]
    > <P>If you click <STRONG>VAT in payment order</STRONG>, the text, including the VAT amount in the <STRONG>Purpose text</STRONG> field, will be entered.</P>



11. In the **Method of payment** field, select the method of payment to the vendor.

12. On the **General** tab, in the **Contracts group** field, select the contract group.

13. In the **DVR** field, select the registration number of the contract.

14. In the **Sales tax group** and the **Item sales tax group** fields, select the tax groups for VAT calculation.

15. On the **Bank** tab, in the **Bank transaction type** field, select the transaction type.

16. In the **Account identification** field, select the bank account of the recipient.
    

    > [!NOTE]
    > <P>If the payment order is being generated for a legal representative of the vendor, the code must be entered in the <STRONG>Payment documented on</STRONG> field. Along with this, the payment order slip will refer to the bank of the vendor that is specified in the <STRONG>Payment documented on</STRONG> field, but the transaction will be performed for the vendor that is specified in the <STRONG>Account</STRONG> field.</P>



17. On the **Payment order** tab, in the **Order of payment** field, specify the order of payment.

18. In the **Number status** field, specify the number status of the payment.

19. In the **Origin payment** field, specify the origin of the payment.

20. In the **Payment type** field, specify the type of payment.

21. Click **Functions**, and then select **Generate payments** to open the **Generate payments** form.

22. In the **Method of payment** field, select the method of payment.

23. In the **Export format** field, select **Payment order in RUB**.

24. In the **Bank account** field, select the bank account from which the payment is to be made.

25. Select the **Show format dialog** check box.

26. Click **OK**. The **Payment order setup** form opens.

27. Select the **Document** check box to print the payment document.

28. Select the **Warrant text** check box to print the warrant text.

29. Click **OK**. The payment order is generated, and the payment status of the appropriate payment journal line is changed to **Sent**.

30. Click **Functions**, and then select **Void payment order** to void a payment order from the payment journal lines. The value for the voided payment order in the **Payment status** field is **None** after the voided payment order is deleted from the registry of payment orders.

31. To post a payment journal, click **Post**. A transaction is generated for the bank account, vendor, and accounting transactions to reflect the outgoing payment.
    

    > [!NOTE]
    > <P>If the method of payment is <STRONG>Bridging Posting</STRONG>, the payment will be posted to the bridging accounts. You can view the transactions in the <STRONG>Journal voucher</STRONG> form, <STRONG>Bank transactions</STRONG> form, and <STRONG>Vendor</STRONG> form.</P>

    
    The payment journal can also be used to register an outgoing payment for a cash refund to a customer. In the **Journal voucher** form, select **Customer** in the **Account type** field, the customer code in the **Account** field, and the payment type of the customer in the **Method of payment** field. Click **Accounts receivable** \> **Setup** \> **Payment** \> **Methods of payment**.

32. To reprint a payment order:
    
      - Click **Print**, and then click **Print payment order** in the **Journal voucher** form.
    
      - Payment orders can also be reprinted from the **Bank transactions** form. Select the voucher for the payment order, click **Print**, and then click **Payment order** to print the document.

## Registry of payment orders

Generated payment orders are available in the **Registry of payment orders** form.

1.  Click **Accounts payable** \> **Inquiries** \> **Payment order register**.

2.  View the information in all the fields.

3.  On the **Essential elements** tab, view the attributes of the payer and the recipient.

4.  Close the form.

## See also

[(RUS) Methods of payment (modified form)](https://technet.microsoft.com/en-us/library/jj665379\(v=ax.60\))

[(RUS) Registry of payment orders (form)](https://technet.microsoft.com/en-us/library/jj711545\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

