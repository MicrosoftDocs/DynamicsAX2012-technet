---
title: Retail product kits (Retail essentials)
TOCTitle: Retail product kits (Retail essentials)
ms:assetid: b505380a-d8a3-4777-85a3-9f07adb24b88
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn859567(v=AX.60)
ms:contentKeyID: 63820141
ms.date: 12/17/2014
mtps_version: v=AX.60
---

# Retail product kits (Retail essentials) 


This topic describes the process flow for setting up retail product kits. You use product kits to group and package individual products as one sellable unit. By selling products as a kit, you can reduce the costs that are associated with order fulfillment and shipping. A product kit can include multiple products, variants for those products, and product substitutes. Customers can select a product substitute to replace a standard kit product. If the product substitute costs more than the standard kit product, the kit price is adjusted to include the additional cost. The products that are included in a kit are referred to as components. The sets of products that make up a product kit are referred to as kit configurations. One product kit can include many components and kit configurations.

## 1\. Create a product kit

A product kit includes a group of separate products, product variants, and product substitutes. To create a product kit, you create a new product and designate it as a product kit. After you create the product kit, you can add products and product variants to the kit as kit components. You can also add product substitutes for any of the kit components. For more information about how to set up a product kit, see [Create retail product kits (Retail essentials)](create-retail-product-kits-retail-essentials.md).

## 2\. Add products and product substitutes to the product kit

After you set up the base information for the product kit, the next step is to add the kit components and product substitutes to the kit. The combinations of kit components and product substitutes define the various product configurations for the kit. Product configurations represent every product combination that a product kit might offer. For example, if you set up a product kit that contains three products, and there are two product substitutes for one of the three products, you can offer three product configurations.

After you set up the kit components and product substitutes, you can also set the kit options. For example, you can allow disassembly of the product kit. Product kits can be disassembled at either the warehouse or the store. If a product kit can be disassembled at the store, a store employee can sell one or more components of the product kit separately, instead of selling the whole kit. This option applies only to product kits that are sold in a brick-and-mortar store by using the point of sale (POS) register. Product kits that are disassembled at the warehouse are just broken down, and the individual products are returned to on-hand inventory.

After you have added all the kit components and product substitutes to the kit and set the kit options, you must set the kit to an approved status.

## 3\. Release the product kit configurations to your legal entities

Before you can generate assembly orders for the product kit, you must release the product kit configurations to the legal entities in which the kit can be sold. You release kit products by using the same steps that you use to release any other type of product.

## 4\. Set the standard properties for the released product kits

After you release the product kit to your legal entities, you must set up any standard properties for the product kit. For example, you can assign the kit to a product category or set up distribution codes. For information about how to set the standard properties for released products, see [Set up retail products (Retail essentials)](set-up-retail-products-retail-essentials.md).

## 5\. Define kit pricing and generate trade agreements

After you release the product kit to your legal entities and set the basic product properties for the kit, the next step is to price the kit. Each component of the product kit is assigned a base price, and the sum of the base prices equals the base price of the product kit. The base price for each kit component is the price of the product at the time that it was added to the product kit. If you want to specify a different price for the kit, you can enter a new total kit price for the kit. This new price is then distributed across all the products in the kit. The price adjustment for each product is based on the percentage that the product’s base price contributes to the total base price for the product kit.

When you add product substitutes to a product kit, you can also specify whether there is an additional charge when customers select a product substitute instead of the standard component. The additional cost is included when the kit price is calculated.

## 6\. Generate assembly orders

After all the components are defined and priced, and the kit configurations are released to your legal entities, the next step is to generate the assembly orders. When you generate assembly orders, you indicate the number of kits that must be assembled and the warehouse for which the assembly order is created.

## 7\. Assemble kit products

After the assembly orders are generated, a warehouse worker can pick and pack the kit components and package the kit. The warehouse worker updates the assembled quantity for each kit configuration. When the warehouse worker has finished assembling all the kits in the order, he or she can post the bill of materials (BOM) journals. When the BOM journals are posted, on-hand inventory for the product kits is increased, and on-hand inventory for the individual components is decreased.

For more information about how to view and maintain assembly orders for product kits, see [Process kit assembly and disassembly orders (Retail essentials)](process-kit-assembly-and-disassembly-orders-retail-essentials.md).

## See also

[Create retail product kits (Retail essentials)](create-retail-product-kits-retail-essentials.md)

[Process kit assembly and disassembly orders (Retail essentials)](process-kit-assembly-and-disassembly-orders-retail-essentials.md)

  


