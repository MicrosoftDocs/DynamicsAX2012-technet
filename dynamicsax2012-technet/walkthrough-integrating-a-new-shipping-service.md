---
title: 'Walkthrough: Integrating a new Shipping Service'
TOCTitle: 'Walkthrough: Integrating a new Shipping Service'
ms:assetid: d807c6ed-f6d9-4b84-a06a-3cf9bb48766b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ916622(v=AX.60)
ms:contentKeyID: 50934012
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Walkthrough: Integrating a new Shipping Service 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The commerce runtime (CRT) includes a shipping service to calculate shipping costs and determine shipping options for the current order. As with all services in the CRT, you can use the default shipping service from Microsoft Dynamics AX or you can use a third party shipping service. This topic describes how to integrate a new Contoso shipping service into the CRT.

Shipping functionality in the CRT is comprised of the shipping service and the shipping carrier adapter service. You use the shipping service for any shipping-related information. The shipping service calls into the shipping carrier adapter service if additional real time information from the actual shipping carrier (like FedEx) is needed. For example,

  - Rather than a flat shipping rate, a retailer needs custom rates from the shipping carrier for each package.

  - A retailer wants to display the latest tracking information from the shipping carrier.

  - A retailer wants to validate that a shipping address is valid for the shipping carrier before an order is placed.

To integrate a new shipping service,

1.  Create a shipping carrier class that inherits from the [Service](https://technet.microsoft.com/en-us/library/jj823840\(v=ax.60\)) abstract class and implements the [IShippingCarrierService](https://technet.microsoft.com/en-us/library/jj782080\(v=ax.60\)) interface.

2.  Create classes to encapsulate business logic for the shipping service.

3.  Update the CommerceRuntime.config file to include the new shipping service.

4.  Configure the shipping adapter in Microsoft Dynamics AX.

## Creating a Shipping Carrier Class

The shipping carrier adapter service provides an entry point for a CRT entity to communicate with an external shipping carrier. Both the shipping service and the shipping carrier adapter service can be replaced independently of each other, as long as the replacements implement IShippingService and IShippingCarrierService, respectively. In this section you create a class that inherits from the [Service](https://technet.microsoft.com/en-us/library/jj823840\(v=ax.60\)) class and implements the [IShippingCarrierService](https://technet.microsoft.com/en-us/library/jj782080\(v=ax.60\)) interface.

### To create a class project

1.  Create a new C\# class library project in Visual Studio. For this example, name it ContosoShippingCarrier.

2.  Click **PROJECT** \> **ContosoShippingCarrier Properties…**

3.  Click **Signing**, and then select **Sign the assembly**.

4.  In **Choose a strong name key file**, specify a key file.

5.  In Solution Explorer, right-click **ContosoShippingCarrier**, and then click **Add Reference**.

6.  Add the following references:
    

    > [!NOTE]
    > <P>Browse to find the CRT assemblies. You can find the system assemblies under Assemblies &gt; Framework.</P>

    
      - Microsoft.Dynamics.Commerce.Runtime
    
      - Microsoft.Dynamics.Commerce.Runtime.Services.Messages
    
      - System.ComponentModel.DataAnnotations
    
      - System.Runtime.Serialization

## Shipping Carrier Code

Open the C\# class in your project and write logic for your shipping adapter. Consider the following as you write your code:

  - Decorate the class with the \[Export(typeof(IService))\] attribute.

  - Inherit from the Service class and implement the IShippingCarrierService interface.

  - The ExecuteRequest(ServiceRequest) method determines the type of a request and handles it accordingly.

  - If the carrier adapter requires a set of specific configuration values to contact a web service, provide those adapter configuration values as part of a parameter set inside the ServiceRequest object that is passed into the shipping carrier.

  - The **Name** property serves as a unique identifier for the adapter binary. For each delivery mode, the CRT determines which adapter to instantiate based on this string value. This value must match one of the rows in the RetailShipCarrierInterface table.

  - We recommend that you encapsulate the logic of each of the major tasks that are supported by the carrier into separate classes. For example, address validation, rate calculation, and tracking information.

  - If the carrier expects the country codes and state codes in a format different from what is used by the CRT, add a country region mapper.

The following code shows an example of a shipping carrier adapter:

    namespace ContosoShippingCarrier
    {
        using System;
        using System.Collections.Generic;
        using System.Collections.ObjectModel;
        using System.ComponentModel.Composition;
        using Microsoft.Dynamics.Commerce.Runtime;
        using Microsoft.Dynamics.Commerce.Runtime.DataModel;
        using Microsoft.Dynamics.Commerce.Runtime.Services;
        using Microsoft.Dynamics.Commerce.Runtime.Services.Messages;
    
        /// <summary>
        /// Encapsulates code for the contoso shipping carrier adapter.
        /// </summary>
        [Export(typeof(IService))]
        public sealed class ContosoShippingCarrierAdapter : Service, IShippingCarrierService
        {
            /// <summary>
            /// Enumerates a list of services that are supported by the carrier.
            /// </summary>
            private enum WebServiceType
            {
                /// <summary>
                /// Lists webservices that this adapter supports.
                /// </summary>
                AddressValidation = 1,
                Tracking = 2,
                Rating = 3
            };
    
            /// <summary>
            /// Identifies an adapter binary.
            /// </summary>
            public string Name
            {
                get { return "Contoso"; }
            }
    
            /// <summary>
            /// Executes the specified request.
            /// </summary>
            /// <typeparam name="TResponse">The type of the response.</typeparam>
            /// <param name="request">The request.</param>
            /// <returns>The response.</returns>
            protected override TResponse ExecuteRequest<TResponse>(ServiceRequest request)
            {
                if (request == null)
                {
                    throw new ArgumentNullException("request");
                }
    
                object response;
                Type requestType = request.GetType();
    
                if (requestType == typeof(GetShippingRateFromCarrierServiceRequest))
                {
                    response = GetShippingRate((GetShippingRateFromCarrierServiceRequest)request);
                }
                else if (requestType == typeof(GetTrackingInformationFromCarrierServiceRequest))
                {
                    response = GetTrackingDetails((GetTrackingInformationFromCarrierServiceRequest)request);
                }
                else if (requestType == typeof(ValidateShippingAddressCarrierServiceRequest))
                {
                    response = ValidateShippingAddress((ValidateShippingAddressCarrierServiceRequest)request);
                }
                else
                {
                    throw new NotSupportedException(string.Format("Request '{0}' is not supported.", request));
                }
    
                return (TResponse)response;
            }
    
            /// <summary>
            /// Called for service-specific initialization.
            /// </summary>
            /// <param name="runtime">The runtime.</param>
            public void Initialize(CommerceRuntime runtime)
            {
                // Any service initiliation code goes here.
                // Example: Instantiation of data mapper, etc.
            }
    
            /// <summary>
            /// Called for services-specific deinitialization.
            /// </summary>
            public void Uninitialize()
            {
                // Any service-specific deinitialization code goes here.
            }
    
            /// <summary>
            /// Validates the shipping address.
            /// </summary>
            /// <param name="request">The request.</param>
            /// <returns>The address validation response.</returns>
            private static ValidateShippingAddressCarrierServiceResponse ValidateShippingAddress(ValidateShippingAddressCarrierServiceRequest request)
            {
                if (request.AddressToValidate == null)
                {
                    throw new ArgumentNullException("request.AddressToValidate");
                }
                if (request.AdapterConfig == null)
                {
                    throw new ArgumentNullException("request.AdapterConfig");
                }
    
                IEnumerable<Address> suggestedAddresses = new Collection<Address>();
                bool isValid = false;
    
                try
                {
                    isValid = AddressValidator.ValidateShippingAddress(request.AddressToValidate, request.SuggestAddress, request.AdapterConfig, out suggestedAddresses);
                }
                catch (Exception ex)
                {
                    ContosoErrorHandler(ex, WebServiceType.AddressValidation);
                }
    
                return new ValidateShippingAddressCarrierServiceResponse(isValid, suggestedAddresses);
            }
    
            /// <summary>
            /// Gets the shipping rate.
            /// </summary>
            /// <param name="request">The request.</param>
            /// <returns>The shipping rate response from the carrier.</returns>
            private static GetShippingRateFromCarrierServiceResponse GetShippingRate(GetShippingRateFromCarrierServiceRequest request)
            {
                if (request.ShippingRateInfo == null)
                {
                    throw new ArgumentNullException("request.ShippingRateInfo");
                }
    
                if (request.AdapterConfig == null)
                {
                    throw new ArgumentNullException("request.AdapterConfig");
                }
    
                decimal rates = 0;
    
                try
                {
                    rates = RateCalculator.GetShippingRate(request.ShippingRateInfo, request.AdapterConfig);
                }
                catch (Exception ex)
                {
                    ContosoErrorHandler(ex, WebServiceType.Rating);
                }
    
                return new GetShippingRateFromCarrierServiceResponse(rates);
            }
    
    
            /// <summary>
            /// Gets tracking details.
            /// </summary>
            /// <param name="request">The request.</param>
            /// <returns>The tracking details response from carrier.</returns>
            private static GetTrackingInformationFromCarrierServiceResponse GetTrackingDetails(GetTrackingInformationFromCarrierServiceRequest request)
            {
                if (request.AdapterConfig == null)
                {
                    throw new ArgumentNullException("request.AdapterConfig");
                }
    
                if (request.TrackingNumbers == null)
                {
                    throw new ArgumentNullException("request.TrackingNumbers");
                }
    
                IEnumerable<TrackingInfo> trackingDetails = new Collection<TrackingInfo>();
                try
                {
                    trackingDetails = Tracker.GetTrackingDetails(request.AdapterConfig, request.TrackingNumbers);
                }
                catch (Exception ex)
                {
                    ContosoErrorHandler(ex, WebServiceType.Tracking);
                }
    
                return new GetTrackingInformationFromCarrierServiceResponse(trackingDetails);
            }
    
            /// <summary>
            /// Handles exceptions for all Contoso shipping adapter services.
            /// </summary>
            /// <param name="exception">The exception.</param>
            /// <param name="serviceType">Type of the service that triggered the exception.</param>
            /// <exception cref="CommunicationException">To notify called of any exception with customized message</exception>
            private static void ContosoErrorHandler(Exception exception, WebServiceType serviceType)
            {
                Type exceptionType = exception.GetType();
                Exception translatedException = null;
    
                if (exceptionType == typeof(System.Web.Services.Protocols.SoapException))
                {
                    var ex = exception as System.Web.Services.Protocols.SoapException;
    
    
                    translatedException = new CommunicationException(CommunicationErrors.ExternalProviderError,
                                                    "Soap exception in Contoso adapter." + exception.Message,
                                                    exception);
    
                }
                else
                {
                    translatedException = new CommunicationException(CommunicationErrors.ProviderCommunicationFailure,
                                                "Unable to communicate with Contoso." + exception.Message,
                                                exception);
    
                }
                throw translatedException;
            }
        }
    }

## Address Validation Code

We recommend that you encapsulate business logic for address validation in a separate class. The following code shows an example of an address validation class for your shipping carrier adapter:

    namespace ContosoShippingCarrier
    {
        using System;
        using System.Collections.Generic;
        using Microsoft.Dynamics.Commerce.Runtime;
        using Microsoft.Dynamics.Commerce.Runtime.DataModel;
    
        /// <summary>
        /// Static class to call into Contoso Address Validation WebService.
        /// </summary>
        internal static class AddressValidator
        {
            /// <summary>
            /// Validates the shipping address.
            /// </summary>
            /// <param name="enteredAddress">The entered address.</param>
            /// <param name="suggestAddress">A value indicating whether the service should suggest addresses.</param>
            /// <param name="adapterConfig">The adapter config.</param>
            /// <param name="suggestedAddresses">The suggested addresses.</param>
            /// <returns>
            /// Returns true if address was valid.
            /// </returns>
            public static bool ValidateShippingAddress(Address enteredAddress, bool suggestAddress, ParameterSet adapterConfig, out IEnumerable<Address> suggestedAddresses)
            {
                if (enteredAddress == null)
                {
                    throw new ArgumentNullException("enteredAddress");
                }
    
                if (adapterConfig == null)
                {
                    throw new ArgumentNullException("adapterConfig");
                }
    
                suggestedAddresses = null;
    
                Boolean isValid = true;
    
                // This is where a call to carrier web service would be made to validate the address and get suggestions.
                // Currently the code always returns true.
    
                return isValid;
            }
        }
    }

## Rate Calculation Code

We recommend that you encapsulate business logic for rate calculation in a separate class. The following code shows an example of a rate calculation class for your shipping carrier adapter:

    namespace ContosoShippingCarrier
    {
        using System;
        using Microsoft.Dynamics.Commerce.Runtime;
        using Microsoft.Dynamics.Commerce.Runtime.DataModel;
    
        /// <summary>
        /// Static class to call into ContosoShipping Rate WebService.
        /// </summary>
        internal static class RateCalculator
        {
            /// <summary>
            /// Gets the shipping rate.
            /// </summary>
            /// <param name="shippingRateInfo">The shipping rate info.</param>
            /// <param name="adapterConfig">The adapter config.</param>
            /// <returns>
            /// Shipping Rate
            /// </returns>
            public static decimal GetShippingRate(ShippingRateInfo shippingRateInfo, ParameterSet adapterConfig)
            {
                if (adapterConfig == null)
                {
                    throw new ArgumentNullException("adapterConfig");
                }
    
                if (shippingRateInfo == null)
                {
                    throw new ArgumentNullException("shippingRateInfo");
                }
    
                if (shippingRateInfo.ToAddress == null)
                {
                    throw new ArgumentNullException("shippingRateInfo.ToAddress");
                }
    
                if (shippingRateInfo.FromAddress == null)
                {
                    throw new ArgumentNullException("shippingRateInfo.FromAddress");
                }
    
                if (shippingRateInfo.GrossWeight <= 0)
                {
                    throw new ArgumentOutOfRangeException("shippingRateInfo.GrossWeight","Gross weight cannot be zero or negative.");
                }
    
                decimal totalCharges = 0M;
                
                // Call external service to get rate by using info in ShippingRateInfo (FromAddress, GrossWeight, ToAddress).
    
                // Our sample code returns a preset shipping charge
                if (shippingRateInfo.GrossWeight < 10M)
                {
                    decimal ChargePerUnitOfWeight = 2;
                    totalCharges = shippingRateInfo.GrossWeight * ChargePerUnitOfWeight;
                }
                else
                {
                    totalCharges = 20M;
                }
                
                return totalCharges;
            }
    
    
        }
     }

## Tracking Information Code

We recommend that you encapsulate business logic for tracking information in a separate class. The following code shows an example of a tracking information class for your shipping carrier adapter:

    namespace ContosoShippingCarrier
    {
        using System;
        using System.Collections.Generic;
        using System.Collections.ObjectModel;
        using Microsoft.Dynamics.Commerce.Runtime;
        using Microsoft.Dynamics.Commerce.Runtime.DataModel;
    
        /// <summary>
        /// Static class to call into ContosoShipping Track WebService.
        /// </summary>
        internal static class Tracker
        {
            /// <summary>
            /// Message contents of response from webservice when a shipment's information is not in their database.
            /// </summary>
            private const string ShipmentNotReceivedYet = "No information for the following shipments has been received by our system yet";
    
            /// <summary>
            /// Gets the tracking details using tracking numbers specified inside <see cref="TrackingInfo"/>.
            /// Makes multiple calls to the webservice. One call per tracking number.
            /// </summary>
            /// <param name="adapterConfig">The adapter configuration.</param>
            /// <param name="trackingNumbers">The tracking numbers.</param>
            /// <returns>Tracking details for all the tracking numbers.</returns>
            public static ReadOnlyCollection<TrackingInfo> GetTrackingDetails(ParameterSet adapterConfig, IEnumerable<string> trackingNumbers)
            {
                if (adapterConfig == null)
                {
                    throw new ArgumentNullException("adapterConfig");
                }
    
                if (trackingNumbers == null)
                {
                    throw new ArgumentNullException("trackingNumbers");
                }
    
                Collection<TrackingInfo> trackingDetails = new Collection<TrackingInfo>();
    
                // Call external web service to get tracking info.
    
    
                foreach (string trackingNumber in trackingNumbers)
                {
    
                    TrackingInfo trackingInfo = new TrackingInfo { TrackingNumber = trackingNumber };
                    // Use web service response to set trackingInfo porperties such as ShippedOnDate, DeliveredOnDate, DestinationAddress, EstimatedDeliveryDate, OriginAddress, 
                    // PackageWeight, PackagingType, ServiceType, ShipmentProgress, ShippedOnDate, ShippingCharge, Status, TrackingNumber, TrackingUrl.
    
                    trackingDetails.Add(trackingInfo);
                }  
    
                return trackingDetails.AsReadOnly();
            }
        }
    }

## Adapter Configuration Fields Code

We recommend that you encapsulate all configuration keys required by the carrier inside a separate class. These keys will be used to look up corresponding values inside the adapter configuration parameter set that is passed in as part of the ServiceRequest object. The following code shows an example of adapter configuration fields code:

    namespace ContosoShippingCarrier
    {
        /// <summary>
        /// Container of name of all the fields that are read from the adapter configuration for ContosoShipping.
        /// </summary>
        internal static class AdapterConfigurationFields
        {
            /// <summary>
            /// Name of field that contains the web service url in adapter configuration. 
            /// </summary>
            public const string TrackWebServiceUrl = "TrackWebServiceUrl";
    
            /// <summary>
            /// Name of field that contains the web service url in adapter configuration.
            /// </summary>
            public const string RateWebServiceUrl = "RateWebServiceUrl";
    
            /// <summary>
            /// Adapter configuration field.
            /// </summary>
            public const string UserCredentialKey = "UserCredentialKey";
    
            /// <summary>
            /// Adapter configuration field.
            /// </summary>
            public const string UserCredentialPassword = "UserCredentialPassword";
    
            /// <summary>
            /// Adapter configuration field.
            /// </summary>
            public const string AccountNumber = "AccountNumber";
    
            /// <summary>
            /// Adapter configuration field.
            /// </summary>
            public const string MeterNumber = "MeterNumber";
    
            /// <summary>
            /// Adapter configuration field.
            /// </summary>
            public const string DropOffType = "DropOffType";
    
            /// <summary>
            /// Adapter configuration field.
            /// </summary>
            public const string RateRequestType = "RateRequestType";
    
            /// <summary>
            /// Adapter configuration field.
            /// </summary>
            public const string ServiceType = "ServiceType";
    
            /// <summary>
            /// Adapter configuration field.
            /// </summary>
            public const string PackagingType = "PackagingType";
    
            /// <summary>
            /// Adapter configuration field.
            /// </summary>
            public const string WeightUnits = "WeightUnits";
    
            /// <summary>
            /// Adapter configuration field.
            /// </summary>
            public const string LinearUnits = "LinearUnits";
    
            /// <summary>
            /// Adapter configuration field.
            /// </summary>
            public const string CurrencyCode = "CurrencyCode";
        }
    }

## Modifying the CRT Configuration File (CommerceRuntime.config)

The CRT configuration file contains an enumeration of services as types, and it controls which types to load. By default, all types that are included with Microsoft Dynamics AX are loaded. To replace a service in the CRT, remove the type that represents that service from the file and add the type that represents the service you want to use.


> [!NOTE]
> <P>Types are loaded in the order they are listed in the configuration file. Instead of removing a type to replace it with a customized type, you can add your customized type above it in the file and it will be used instead.</P>



### To modify the CRT configuration file

1.  Open commerceRuntime.config in your solution.
    

    > [!NOTE]
    > <P>The location of this file varies based on your deployment. If you are customizing the SharePoint starter store, you can find the file by using the Internet Information Services (IIS) Manager. In IIS Manager, find the starter store under the <STRONG>Sites</STRONG> node. Right-click the public starter store, and then click <STRONG>Explore</STRONG>.</P>



2.  Add a line to include your new service. For this example, something like:
    
        <add source="assembly" value="ContosoShippingCarrier, Version=1.0.0.0, Culture=neutral, PublicKeyToken=6598494e9dab8361, processorArchitecture=MSIL" />

## Configuring the Shipping Adapter in Microsoft Dynamics AX

To configure the shipping adapter, you must:

1.  Create a shipping carrier account.

2.  Create a unique identifier for the shipping adapter.

3.  Map the shipping carrier account to the new shipping adapter.

4.  Map the delivery mode to the new carrier ID.

5.  Run the jobs and synchronize the tables to update the delivery mode mapping in the CRT database

The shipping carrier account is set up in the [Carrier company](https://technet.microsoft.com/en-us/library/hh209693\(v=ax.60\)) form. For more information, see [Set up shipping carriers](set-up-shipping-carriers.md).

Each external shipping adapter in the CRT is uniquely identified by the **Name** property of the [IShippingCarrierService](https://technet.microsoft.com/en-us/library/jj782080\(v=ax.60\)) interface that is implemented by each shipping adapter. This information is reflected in Microsoft Dynamics AX in the RetailShipCarrierInterface table. To register a new shipping adapter in Microsoft Dynamics AX, add the name and description for the adapter in the RetailShipCarrierInterface table by using the AddRetailShippingCarrier job below.

Use the [Carrier IDs](https://technet.microsoft.com/en-us/library/hh209608\(v=ax.60\)) form to map the shipping carrier account to the new shipping adapter. For more information, see [Set up shipping carriers](set-up-shipping-carriers.md).

Use the [Modes of delivery](https://technet.microsoft.com/en-us/library/aa619881\(v=ax.60\)) form to map the deliver mode to a carrier ID. For more information, see [Set up modes of delivery](set-up-modes-of-delivery.md).

### To create the shipping carrier account in Microsoft Dynamics AX

1.  In Microsoft Dynamics AX, click **Inventory and Warehouse Management** \> **Setup** \> **Shipping Carrier** \> **Carrier Company**.

2.  Click **New**.

3.  Enter the carrier and charges in the **Carrier** and **General Charges** fields, respectively.

4.  Under **Accounts**, click **Add**.

5.  Enter an **Account Code**, **Carrier Account Number**, and **Currency** for the shipping carrier.

6.  Click **Configuration**.

7.  Specify any values that are required for the external carrier adapter in the CRT.
    

    > [!NOTE]
    > <P>For example, the web service URL of the external shipping carrier, the login credentials for the web service, or units of measure.</P>



### To create a unique identifier for the shipping adapter in Microsoft Dynamics AX

  - Add the name of the shipping adapter to the [RetailShipCarrierInterface](https://technet.microsoft.com/en-us/library/jj781068\(v=ax.60\)) table by using the following job:
    
        static void AddRetailShippingCarrier(Args _args)
        {
            RetailShipCarrierInterfaceId carrierAdapterId = 'Contoso';
            str carrierDescription = "Contoso Shipping Adapter";
            RetailShipCarrierInterface loc_RetailShipCarrierInterface;
            
            ttsBegin;
            
            select forUpdate loc_RetailShipCarrierInterface where loc_RetailShipCarrierInterface.CarrierAdapterId == carrierAdapterId;
            
            if (loc_RetailShipCarrierInterface.RecId == 0)
            {
                loc_RetailShipCarrierInterface.CarrierAdapterId = carrierAdapterId;
                loc_RetailShipCarrierInterface.Description = carrierDescription;
                
                loc_RetailShipCarrierInterface.insert();
            }
            
            ttsCommit;
        }

### To map a shipping carrier account in Microsoft Dynamics AX to the new shipping adapter in Microsoft Dynamics AX

1.  Click **Inventory and Warehouse Management** \> **Setup** \> **Shipping Carrier** \> **Carrier IDs**.

2.  Click **New**.

3.  Enter a unique carrier identifier in the **Carrier ID** field and a description in the **Carrier service description** field. For example, C01 for Contoso.

4.  Enter Contoso in **Carrier company**.

### To map a delivery mode to a carrier ID

1.  Click **Sales and Marketing** \> **Setup** \> **Distribution** \> **Modes of Delivery**.

2.  Specify a Mode of delivery or create a new one. For more information, see [Set up modes of delivery](set-up-modes-of-delivery.md).

3.  Under **Setup**, select a **Service**.

4.  Select the carrier ID that you specified in the previous procedure. This populates the **Carrier Company** and **Account Code** fields.
    

    > [!NOTE]
    > <P>If multiple accounts are associated with a carrier company, select the account code that has the associated adapter configuration.</P>



### To update the delivery mode mapping to the CRT database

1.  Click **Retail** \> **Periodic** \> **Process delivery modes**. Click **OK**.

2.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Create Actions**.

3.  Run the following jobs:
    
    A-1120\_OC
    
    N-1120\_OC
    

    > [!NOTE]
    > <P>The jobs will synchronize these tables:</P>
    > <P><A href="https://technet.microsoft.com/en-us/library/jj781040(v=ax.60)">RetailShipCarrierAccountConfiguration</A></P>
    > <P><A href="https://technet.microsoft.com/en-us/library/gg857952(v=ax.60)">ShipCarrierCompanyAccounts</A></P>
    > <P><A href="https://technet.microsoft.com/en-us/library/jj781068(v=ax.60)">RetailShipCarrierInterface</A></P>
    > <P><A href="https://technet.microsoft.com/en-us/library/gg873889(v=ax.60)">ShipCarrierTable</A></P>
    > <P><A href="https://technet.microsoft.com/en-us/library/gg951962(v=ax.60)">DlvMode</A></P>



## See also

[Online Store](online-store.md)

[Retail Modern Point of Sale](retail-modern-point-of-sale.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

