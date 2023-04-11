---
title: (BRA) Set up the CFOP codes
TOCTitle: (BRA) Set up the CFOP codes
ms:assetid: 9441235e-0f15-47bf-8bc9-36c8eb608805
ms:mtpsurl: https://technet.microsoft.com/library/JJ933526(v=AX.60)
ms:contentKeyID: 50935139
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- CFOP
- CFOP codes
- set up CFOP codes
- BR - 00042
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up the CFOP codes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create Código Fiscal de Operações e Prestações (CFOP) codes, or fiscal operation codes, by using the **CFOP codes** form. You can also define the default CFOP code for a transaction type or operation type by using the **CFOP matrix** form.

Fiscal operation codes are set up for transactions based on the location of the customer, location of the vendor, location of the fiscal establishment, the direction of the movement of items, and the operation type.

The default location and direction are updated in the **Location** and **Direction** fields in the **CFOP codes** form based on the first digit of the CFOP code. The following table shows the first digits of CFOP codes, and the corresponding default locations and directions.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 First digit of CFOP code
  </p> </th>
    <th> <p>
   
	 Location
  </p> </th>
    <th> <p>
   
	 Direction
  </p> </th>
  </tr>
  <tr>
    <td> <p>
   
	 1
  </p> </td>
    <td> <p> <strong>Same state</strong> – The customer or vendor is located in the same state as the fiscal establishment.
  </p> </td>
    <td rowspan="3"> <p> <strong>Incoming</strong> – Items are entering the fiscal establishment.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 2
  </p> </td>
    <td> <p> <strong>Other state</strong> – The customer or vendor is located in the same country as the fiscal establishment, but in a different state.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 3
  </p> </td>
    <td> <p> <strong>Outside country</strong> – The customer or vendor is located in a different country than the fiscal establishment.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 5
  </p> </td>
    <td> <p> <strong>Same state</strong> – The customer or vendor is located in the same state as the fiscal establishment.
  </p> </td>
    <td rowspan="3"> <p> <strong>Outgoing</strong> – Items are leaving the fiscal establishment.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 6
  </p> </td>
    <td> <p> <strong>Other state</strong> – The customer or vendor is located in the same country as the fiscal establishment, but in a different state.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 7
  </p> </td>
    <td> <p> <strong>Outside country</strong> – The customer or vendor is located in a different country than the fiscal establishment.
  </p> </td>
  </tr>
</table>



> [!NOTE]
> <P>If the CFOP code starts with 0, 4, 8, 9, or any alphabetic character, the default location is updated to <STRONG>Same state</STRONG>. However, you can enter a different location in the <STRONG>Location</STRONG> field in the <STRONG>CFOP codes</STRONG> form. You can also select <STRONG>Incoming</STRONG> or <STRONG>Outgoing</STRONG> as the direction of the movement of items in the <STRONG>Direction</STRONG> field.</P>



Use the following procedure to create CFOP codes.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **CFOP codes**.

2.  Create a CFOP code.

3.  In the **CFOP** and **Name** fields, enter the CFOP code and the name of the CFOP code. The **Location** and **Direction** fields are updated based on the CFOP code that you enter.
    

    > [!NOTE]
    > <P>If the CFOP code starts with 0, 4, 8, 9, or any alphabetic character, you can select the location and direction in the <STRONG>Location</STRONG> and <STRONG>Direction</STRONG> fields.</P>



4.  In the **Text ID** field, select the identification code of the default fiscal document text for the transactions that you the selected the CFOP code for.

5.  In the **Purpose** field, select one of the following options to indicate the purpose of the CFOP code for transfer orders:
    
      - **None**
    
      - **Shipment** – The CFOP code is for shipments.
    
      - **Fiscal establishment transfer** – The CFOP code is for the transfer of items from one warehouse to another at different fiscal establishments.
    
      - **Return** – The CFOP code is for the return of items.

6.  In the **Delivery CFOP** field, select the CFOP code to use for delivery slips. You can select the CFOP code that starts with the same digit as the CFOP code that you enter in the **CFOP** field.
    

    > [!NOTE]
    > <P>This field is available for CFOP codes that have the <STRONG>Outgoing</STRONG> direction.</P>



7.  Select the **Consider in CIAP** check box to indicate that the fiscal documents that are associated with this CFOP code are added together to form the basis of calculation for the Credit ICMS Control of Permanent Assets Book (CIAP) factor.

8.  Select the **Fiscal reference required** check box to indicate that fiscal reference information is required for the transactions that use the selected CFOP code.

9.  In the **Fiscal document source text** field, select the identification code of the default fiscal document text for the fiscal references of the transactions that use the selected CFOP code.

## See also

[(BRA) CFOP codes (form)](https://technet.microsoft.com/library/jj933522\(v=ax.60\))

[(BRA) Purchase order (modified form)](https://technet.microsoft.com/library/jj911277\(v=ax.60\))

[(BRA) Sales orders (modified form)](https://technet.microsoft.com/library/jj911252\(v=ax.60\))

[(BRA) Fiscal document source texts (form)](https://technet.microsoft.com/library/jj663934\(v=ax.60\))

[(BRA) CFOP matrix (form)](https://technet.microsoft.com/library/jj933496\(v=ax.60\))

[(BRA) Set up the CFOP matrix](bra-set-up-the-cfop-matrix.md)

  


