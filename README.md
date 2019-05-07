# ![LOGO](logo.png) EventHub2018PreviewManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the EventHub2018PreviewManagementClient API (version 2018-01-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/eventhub-EventHub-preview/2018-01-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:10+03:00

## API Description

Azure Event Hubs client for managing Event Hubs Cluster, IPFilter Rules and VirtualNetworkRules resources.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Event Hub REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client API version.

### Lists all the available Namespaces within a subscription, irrespective of the resource groups.

*Tags:* `Namespaces`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists the available Event Hubs Clusters within an ARM resource group.

*Tags:* `Event Hubs Clusters`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `api-version` - _required_ - Client API version.

### Gets the resource description of the specified Event Hubs Cluster.

*Tags:* `Event Hubs Cluster`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `clusterName` - _required_ - The name of the Event Hubs Cluster.
* `api-version` - _required_ - Client API version.

### Modifies mutable properties on the Event Hubs Cluster. This operation is idempotent.

*Tags:* `Event Hubs Cluster`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `clusterName` - _required_ - The name of the Event Hubs Cluster.
* `api-version` - _required_ - Client API version.

### Get all Event Hubs Cluster settings - a collection of key/value pairs which represent the quotas and settings imposed on the cluster.

*Tags:* `Event Hubs Cluster Configuration`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `clusterName` - _required_ - The name of the Event Hubs Cluster.
* `api-version` - _required_ - Client API version.

### Replace all specified Event Hubs Cluster settings with those contained in the request body. Leaves the settings not specified in the request body unmodified.

*Tags:* `Event Hubs Cluster Configuration`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `clusterName` - _required_ - The name of the Event Hubs Cluster.
* `api-version` - _required_ - Client API version.

### Lists the available Namespaces within a resource group.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes an existing namespace. This operation also removes all associated resources under the namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the description of the specified namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a namespace. Once created, this namespace's resource manifest is immutable. This operation is idempotent.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a namespace. Once created, this namespace's resource manifest is immutable. This operation is idempotent.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a list of IP Filter rules for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes an IpFilterRule for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `ipFilterRuleName` - _required_ - The IP Filter Rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets an IpFilterRule for a Namespace by rule name.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `ipFilterRuleName` - _required_ - The IP Filter Rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates an IpFilterRule for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `ipFilterRuleName` - _required_ - The IP Filter Rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets NetworkRuleSet for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create or update NetworkRuleSet for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a list of VirtualNetwork rules for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes an VirtualNetworkRule for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `virtualNetworkRuleName` - _required_ - The Virtual Network Rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets an VirtualNetworkRule for a Namespace by rule name.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `virtualNetworkRuleName` - _required_ - The Virtual Network Rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates an VirtualNetworkRule for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `virtualNetworkRuleName` - _required_ - The Virtual Network Rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-eventhub-event-hub-preview-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
