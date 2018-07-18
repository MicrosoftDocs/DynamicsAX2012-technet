---
title: Services Overview for Commerce Runtime
TOCTitle: Services Overview
ms:assetid: 29a419a4-e921-4379-b199-84238856839e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ916617(v=AX.60)
ms:contentKeyID: 50934007
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Services Overview for Commerce Runtime 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX retail services are scalable and extensible services that are empowered through a combination of the commerce data exchange and the commerce runtime.

## Commerce Runtime Configuration

Services are enumerated as types in the commerce runtime configuration file. You can add types in the commerce runtime configuration file to control which services are loaded in the commerce runtime.

Services are loaded in the order in which they are listed in the configuration file. All of the default services are loaded automatically, but if you add a new service above one of the default services, the new service will replace the default service. For more information, see [Integrate a Service into the Commerce Runtime](integrate-a-service-into-the-commerce-runtime.md).

## IService interface

The [IService](https://technet.microsoft.com/en-us/library/jj762665\(v=ax.60\)) interface is comprised of an execute method that takes a service request as input and returns a service response.

The service request object contains the data that is needed to carry out an operation. To add new functionality to your store, implement a new message. Then create a service that can handle that message. For more information, see [Integrate a Service into the Commerce Runtime](integrate-a-service-into-the-commerce-runtime.md).

## Default Services

Microsoft Dynamics AX offers many services in the commerce runtime that support the basic functionality of an online store. You can add your own services or extend the services that are included in Microsoft Dynamics AX. The following table describes some of the services that you might use for your online store. For more information about each service, see the [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md) reference documentation.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Service</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="addressservice-class-microsoft-dynamics-commerce-runtime-services.md">AddressService</a></p></td>
<td><p>Verifies addresses and gets location information like cities, counties, or states.</p></td>
</tr>
<tr class="even">
<td><p><a href="chargeservice-class-microsoft-dynamics-commerce-runtime-services.md">ChargeService</a></p></td>
<td><p>Calculates auto-charges, price charges, and shipping charges for a transaction.</p></td>
</tr>
<tr class="odd">
<td><p><a href="currencyservice-class-microsoft-dynamics-commerce-runtime-services.md">CurrencyService</a></p></td>
<td><p>Converts currencies based on exchange rates.</p></td>
</tr>
<tr class="even">
<td><p><a href="customerservice-class-microsoft-dynamics-commerce-runtime-services.md">CustomerService</a></p></td>
<td><p>Maintains customer information.</p></td>
</tr>
<tr class="odd">
<td><p><a href="https://technet.microsoft.com/en-us/library/jj761835(v=ax.60)">DimensionService</a></p></td>
<td><p>Enables customers to find items in your store based on criteria like category or color.</p></td>
</tr>
<tr class="even">
<td><p><a href="emailservice-class-microsoft-dynamics-commerce-runtime-services.md">EmailService</a></p></td>
<td><p>Sends email to customers based on an email template defined in Microsoft Dynamics AX.</p></td>
</tr>
<tr class="odd">
<td><p><a href="loyaltyservice-class-microsoft-dynamics-commerce-runtime-services.md">LoyaltyService</a></p></td>
<td><p>Implements a program that rewards repeat customers.</p></td>
</tr>
<tr class="even">
<td><p><a href="https://technet.microsoft.com/en-us/library/jj760878(v=ax.60)">PaymentService</a></p></td>
<td><p>You can connect your online store to a payment service to provide credit card authorization and utilize pre-configured payment processing. You can also extend the payment service to add additional third party payment processors.</p></td>
</tr>
<tr class="odd">
<td><p><a href="pricingservice-class-microsoft-dynamics-commerce-runtime-services.md">PricingService</a></p></td>
<td><p>Obtains the price of an item in real time. The price is adjusted based on the base price and any applicable discounts. Discounts can be customized for each retailer.</p></td>
</tr>
<tr class="even">
<td><p><a href="productavailabilityservice-class-microsoft-dynamics-commerce-runtime-services.md">ProductAvailabilityService</a></p></td>
<td><p>Calculates the quantities of products that are available to sell.</p></td>
</tr>
<tr class="odd">
<td><p><a href="roundingservice-class-microsoft-dynamics-commerce-runtime-services.md">RoundingService</a></p></td>
<td><p>Rounds the tender amount based on the tender type and store.</p></td>
</tr>
<tr class="even">
<td><p><a href="salesorderservice-class-microsoft-dynamics-commerce-runtime-services.md">SalesOrderService</a></p></td>
<td><p>Creates a sales order based on a customer shopping cart.</p></td>
</tr>
<tr class="odd">
<td><p><a href="shippingservice-class-microsoft-dynamics-commerce-runtime-services.md">ShippingService</a></p></td>
<td><p>Calculates shipping costs and determine shipping options for the current order. You can use shipping data from Microsoft Dynamics AX or from a third party shipping service. For more information about how to use a third party shipping service, see <a href="walkthrough-integrating-a-new-shipping-service.md">Walkthrough: Integrating a new Shipping Service</a>.</p></td>
</tr>
<tr class="even">
<td><p><a href="storelocatorservice-class-microsoft-dynamics-commerce-runtime-services.md">StoreLocatorService</a></p></td>
<td><p>Generates a list of stores based on criteria like proximity and product availability.</p></td>
</tr>
<tr class="odd">
<td><p><a href="taxservice-class-microsoft-dynamics-commerce-runtime-services.md">TaxService</a></p></td>
<td><p>Calculates the sales tax for the current order. You can use sales tax information from Microsoft Dynamics AX or from a third party sales tax service.</p></td>
</tr>
<tr class="even">
<td><p><a href="totalingservice-class-microsoft-dynamics-commerce-runtime-services.md">TotalingService</a></p></td>
<td><p>Calculates the totals on the sales transactions and sales lines.</p></td>
</tr>
</tbody>
</table>


## See also

[Online Store](online-store.md)

[Retail Modern Point of Sale](retail-modern-point-of-sale.md)

  


