---
title: (BRA) Set up fiscal information
TOCTitle: (BRA) Set up fiscal information
ms:assetid: 4a551efc-e3aa-4828-9b46-e0003addcb94
ms:mtpsurl: https://technet.microsoft.com/library/JJ910998(v=AX.60)
ms:contentKeyID: 52075248
author: tfehr
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.CustTableListPage
- Forms.VendTableListPage
- Forms.OMLegalEntity
- Forms.CustTable
- Forms.VendTable
- Forms.EcoResProductDetailsExtended
- Forms.EcoResProductPerCompanyListPage
- BRA
- Brazil
- fiscal information
- BR - 00013
- BR-00043
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up fiscal information 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up fiscal information for legal entities, customers, and vendors. You can also set up fiscal information for a product that is released to a Brazilian legal entity.

## Set up fiscal information for a legal entity

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Select or create a legal entity. For more information, see [Create or modify a legal entity](create-or-modify-a-legal-entity.md).

3.  On the **Statutory reporting** FastTab, in the **CNAE** field, enter the Classificação Nacional de Atividades Econômicas (CNAE), or the national classification of the economic activities of the legal entity.
    

    > [!NOTE]
    > <P>You can set up the Cadastro Nacional de Pessoa Jurídica (CNPJ), Cadastro de contribuinte mobiliário (CCM), and Inscrição Estadual (IE) in the <STRONG>CNPJ/CPF</STRONG>, <STRONG>CCM</STRONG>, and <STRONG>IE</STRONG> fields in the <STRONG>Fiscal establishments</STRONG> form when you create the fiscal establishment that is related to the primary address of the legal entity. CNPJ is the taxpayer registration number for Brazilian companies, CPF is the taxpayer registration number for Brazilian individuals, CCM is the municipal registration number of the city where the customer or vendor is based, and IE is the state registration number of the customer.</P>



## Set up fiscal information for a customer

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Customers** \> **All customers**.

2.  Double-click a customer account, or on the **Action Pane**, click **Customer** to create a customer account. For more information, see [Create a customer record](create-a-customer-record.md).

3.  In the **Customers** form, on the **Fiscal information** FastTab, select the **Final user** check box to indicate that the customer is the final user.

4.  Select the **ICMS contributor** check box to indicate that the customer contributes Imposto Sobre Circulação de Mercadorias e Serviços (ICMS) tax.

5.  In the **Presence type** field, select the presence type of the fiscal operation.
    

    > [!NOTE]
    > <P>This control is available only if cumulative update 8 for AX2012 R3 is installed.</P>



6.  In the **CNPJ/CPF** and **IE** fields, enter the taxpayer registration number and state registration number of the customer.

7.  In the **CCM** field, enter the municipal registration number of the city where the customer is based.

8.  In the **NIT** field, enter the Número de Identificação do Trabalhador (NIT), or identification number, of the worker.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Person</STRONG> in the <STRONG>Record type</STRONG> field.</P>



9.  In the **INSS-CEI** field, enter the Instituto Nacional do Seguro Social – Cadastro específico do INSS (INSS-CEI) number, or Brazilian Security Institute number.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Person</STRONG> in the <STRONG>Record type</STRONG> field.</P>



10. In the **CNAE** field, enter the national classification of the economic activities of the customer.

11. In the **Foreigner ID** field, enter the unique identification number of a customer who is a foreign national. The length of the foreign ID must be between 5 and 20 characters.
    

    > [!NOTE]
    > <P>This control is available only if cumulative update 8 for AX2012 R3 is installed.</P>



12. Select the **Service on delivery address** check box to use service codes and Instituto Brasileiro de Geografia e Estatistica (IBGE) codes based on the city of the delivery address.

13. If the customer is located in the Superintendência da Zona Franca de Manaus (SUFRAMA) region, follow these steps:
    
    1.  Select the **SUFRAMA** check box to indicate that the customer belongs to the SUFRAMA region.
    
    2.  In the **SUFRAMA number** field, enter the subscription number of the customer at SUFRAMA.
        

        > [!NOTE]
        > <P>This field is available only if you select the <STRONG>SUFRAMA</STRONG> check box.</P>

    
    3.  Select the **Discount PIS and COFINS** check box to indicate that Programa de Integração Social (PIS) and Contribuição para o financiamente da securidade social (COFINS) are exempt for SUFRAMA customers.
        

        > [!NOTE]
        > <P>This field is available only if you select the <STRONG>SUFRAMA</STRONG> check box.</P>



14. Select the **Generate incoming fiscal document** check box to generate an incoming fiscal document when you post a customer invoice for a sales return.

## Set up fiscal information for a vendor

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.

2.  Double-click a vendor account, or on the **Action Pane**, click **Vendor** to create a vendor account. For more information, see [Create a vendor account](create-a-vendor-account.md).

3.  In the **Vendors** form, on the **Fiscal information** FastTab, in the **CNPJ/CPF** and **IE** fields, enter the taxpayer registration number and state registration number of the vendor.
    

    > [!NOTE]
    > <P>The <STRONG>IE</STRONG> field is available only if you select <STRONG>Organization</STRONG> in the <STRONG>Record type</STRONG> field.</P>



4.  In the **CCM** field, enter the municipal registration number of the city where the vendor is based.

5.  In the **NIT** field, enter the identification number of the worker.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Person</STRONG> in the <STRONG>Record type</STRONG> field.</P>



6.  In the **INSS-CEI** field, enter the Brazilian Security Institute number.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Person</STRONG> in the <STRONG>Record type</STRONG> field.</P>



7.  In the **CNAE** field, enter the national classification of economic activities of the vendor.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Organization</STRONG> in the <STRONG>Record type</STRONG> field.</P>



8.  In the **Foreigner ID** field, enter the unique identification number of a vendor who is a foreign national. The length of the foreign ID must be between 5 and 20 characters.
    

    > [!NOTE]
    > <P>This control is available only if cumulative update 8 for AX2012 R3 is installed.</P>



9.  Select the **Generate incoming fiscal document** check box to generate an incoming fiscal document when you post a vendor invoice.

10. Select the **Use and consumption** check box to indicate that the purchase that is made from the vendor is for consumption. If you select this check box, the ICMS tax base includes any Imposto sobre Produtos Industrializados (IPI) tax and freight charges.

11. In the **Income code** field, enter the income code of the vendor.

12. Select the **ICMS contributor** check box to indicate that the vendor contributes ICMS tax.

13. In the **Presence type** field, select the presence type of the fiscal operation.
    

    > [!NOTE]
    > <P>This control is available only if cumulative update 8 for AX2012 R3 is installed.</P>



14. Select the **Service on delivery address** check box to use service codes and IBGE codes based on the city of the delivery address.

## Set up fiscal information for a product

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Double-click a product, or on the **Action Pane**, click **Product** to create a released product. For more information, see [Key tasks: Release products](key-tasks-release-products.md) and [Key tasks: Define products](key-tasks-define-products.md).

3.  Depending on the version that you are using, do one of the following:
    
      - In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Released product details** form, on the **Fiscal information** FastTab, in the **Taxation origin** field, select one of the following options to indicate the taxation origin for the product:
        
          - **National, not related to codes 3 to 5**
        
          - **Imported, direct import, not related to code 6**
        
          - **Imported, acquired in internal market, and not related to code 7**
        
          - **National, import content greater than 40 percent**
        
          - **National, production compliant with Decreto-Lei nº 288/67, and laws nºs 8.248/91, 8.387/91, 10.176/01 e 11.484/07**
        
          - **National, import content lower than or equal to 40 percent**
        
          - **Imported, direct import, no similar item in internal market, and included in the CAMEX list and natural gas**
        
          - **Imported, acquired in internal market, with no similar in country/region, and included in the CAMEX list and natural gas**
    
      - In Microsoft Dynamics AX 2012 R2: In the **Taxation origin** field, select **National (produced in country/region)**, **Direct import (produced abroad)**, or **Import acquired internally (produced abroad)** as the taxation origin for the product.

4.  In the **Fiscal classification code** field, select the fiscal classification code for the product.
    

    > [!NOTE]
    > <P>This field is available only for products of type <STRONG>Item</STRONG>.</P>



5.  In the **Exception code** field, select the fiscal classification exception code.
    

    > [!NOTE]
    > <P>This field is available only for products of type <STRONG>Item</STRONG>.</P>



6.  In the **Product type** field, select the type of the product.

7.  In the **Service code** field, select the fiscal classification that is applied to the service.
    

    > [!NOTE]
    > <P>This field is available only for products of type <STRONG>Service</STRONG>.</P>



8.  Select the **ICMS on service** check box to indicate that ICMS tax is applied for the service.
    

    > [!NOTE]
    > <P>This field is available only for products of type <STRONG>Service</STRONG>.</P>



## See also

[(BRA) Fiscal establishments (form)](https://technet.microsoft.com/library/jj933531\(v=ax.60\))

[(BRA) Legal entities (modified form)](https://technet.microsoft.com/library/jj710585\(v=ax.60\))

[(BRA) Customers (modified form)](https://technet.microsoft.com/library/jj933537\(v=ax.60\))

[(BRA) Vendors (modified form)](https://technet.microsoft.com/library/jj933505\(v=ax.60\))

[(BRA) Released product details (modified form)](https://technet.microsoft.com/library/jj923408\(v=ax.60\))

  


