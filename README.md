# ![LOGO](logo.png) FabricAdminClient **flow**ground Connector

## Description

A generated **flow**ground connector for the FabricAdminClient API (version 2016-05-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-ScaleUnitNode/2016-05-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:34+03:00

## API Description

Scale unit node operation endpoints and objects.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns a list of all scale unit nodes in a location.

*Tags:* `ScaleUnitNodes`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `location` - _required_ - Location of the resource.
* `api-version` - _required_ - Client API Version.
* `$filter` - _optional_ - OData filter parameter.

### Return the requested scale unit node.

*Tags:* `ScaleUnitNodes`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `location` - _required_ - Location of the resource.
* `scaleUnitNode` - _required_ - Name of the scale unit node.
* `api-version` - _required_ - Client API Version.

### Power off a scale unit node.

*Tags:* `ScaleUnitNodes`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `location` - _required_ - Location of the resource.
* `scaleUnitNode` - _required_ - Name of the scale unit node.
* `api-version` - _required_ - Client API Version.

### Power on a scale unit node.

*Tags:* `ScaleUnitNodes`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `location` - _required_ - Location of the resource.
* `scaleUnitNode` - _required_ - Name of the scale unit node.
* `api-version` - _required_ - Client API Version.

### Repairs a node of the cluster.

*Tags:* `ScaleUnitNodes`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `location` - _required_ - Location of the resource.
* `scaleUnitNode` - _required_ - Name of the scale unit node.
* `api-version` - _required_ - Client API Version.

### Shutdown a scale unit node.

*Tags:* `ScaleUnitNodes`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `location` - _required_ - Location of the resource.
* `scaleUnitNode` - _required_ - Name of the scale unit node.
* `api-version` - _required_ - Client API Version.

### Start maintenance mode for a scale unit node.

*Tags:* `ScaleUnitNodes`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `location` - _required_ - Location of the resource.
* `scaleUnitNode` - _required_ - Name of the scale unit node.
* `api-version` - _required_ - Client API Version.

### Stop maintenance mode for a scale unit node.

*Tags:* `ScaleUnitNodes`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `location` - _required_ - Location of the resource.
* `scaleUnitNode` - _required_ - Name of the scale unit node.
* `api-version` - _required_ - Client API Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-scale-unit-node-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
