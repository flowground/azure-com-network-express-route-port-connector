# ![LOGO](logo.png) NetworkManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the NetworkManagementClient API (version 2018-12-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/network-expressRoutePort/2018-12-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:32+03:00

## API Description

The Microsoft Azure Network management API provides a RESTful set of web services that interact with Microsoft Azure Networks service to manage your network resources. The API has entities that capture the relationship between an end user and the Microsoft Azure Networks service.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List all the ExpressRoutePort resources in the specified subscription

*Tags:* `ExpressRoutePorts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.

### Retrieves all ExpressRoutePort peering locations. Does not return available bandwidths for each location. Available bandwidths can only be obtained when retrieving a specific peering location.

*Tags:* `ExpressRoutePortsLocations`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.

### Retrieves a single ExpressRoutePort peering location, including the list of available bandwidths available at said peering location.

*Tags:* `ExpressRoutePortsLocations`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.
* `locationName` - _required_ - Name of the requested ExpressRoutePort peering location.

### List all the ExpressRoutePort resources in the specified resource group.

*Tags:* `ExpressRoutePorts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.
* `resourceGroupName` - _required_ - The name of the resource group.

### Deletes the specified ExpressRoutePort resource.

*Tags:* `ExpressRoutePorts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.
* `resourceGroupName` - _required_ - The name of the resource group.
* `expressRoutePortName` - _required_ - The name of the ExpressRoutePort resource.

### Retrieves the requested ExpressRoutePort resource.

*Tags:* `ExpressRoutePorts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.
* `resourceGroupName` - _required_ - The name of the resource group.
* `expressRoutePortName` - _required_ - The name of ExpressRoutePort.

### Update ExpressRoutePort tags

*Tags:* `ExpressRoutePorts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.
* `resourceGroupName` - _required_ - The name of the resource group.
* `expressRoutePortName` - _required_ - The name of the ExpressRoutePort resource.

### Creates or updates the specified ExpressRoutePort resource.

*Tags:* `ExpressRoutePorts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.
* `resourceGroupName` - _required_ - The name of the resource group.
* `expressRoutePortName` - _required_ - The name of the ExpressRoutePort resource.

### Retrieve the ExpressRouteLink sub-resources of the specified ExpressRoutePort resource.

*Tags:* `ExpressRouteLinks`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.
* `resourceGroupName` - _required_ - The name of the resource group.
* `expressRoutePortName` - _required_ - The name of the ExpressRoutePort resource.

### Retrieves the specified ExpressRouteLink resource.

*Tags:* `ExpressRouteLinks`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.
* `resourceGroupName` - _required_ - The name of the resource group.
* `expressRoutePortName` - _required_ - The name of the ExpressRoutePort resource.
* `linkName` - _required_ - The name of the ExpressRouteLink resource.

## License

**flow**ground :- Telekom iPaaS / azure-com-network-express-route-port-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
