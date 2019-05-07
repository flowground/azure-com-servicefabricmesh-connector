# ![LOGO](logo.png) SeaBreezeManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SeaBreezeManagementClient API (version 2018-09-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/servicefabricmesh/2018-09-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:59+03:00

## API Description

APIs to deploy and manage resources to SeaBreeze.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available operations.

> Lists all the available operations provided by Service Fabric SeaBreeze resource provider.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.

### Gets all the application resources in a given subscription.

> Gets the information about all application resources in a given resource group. The information include the description and other properties of the application.

*Tags:* `Applications`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.

### Gets all the gateway resources in a given subscription.

> Gets the information about all gateway resources in a given resource group. The information include the description and other properties of the gateway.

*Tags:* `Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.

### Gets all the network resources in a given subscription.

> Gets the information about all network resources in a given resource group. The information include the description and other properties of the network.

*Tags:* `Networks`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.

### Gets all the secret resources in a given subscription.

> Gets the information about all secret resources in a given resource group. The information include the description and other properties of the secret.

*Tags:* `Secrets`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.

### Gets all the volume resources in a given subscription.

> Gets the information about all volume resources in a given resource group. The information include the description and other properties of the volume.

*Tags:* `Volumes`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.

### Gets all the application resources in a given resource group.

> Gets the information about all application resources in a given resource group. The information include the description and other properties of the Application.

*Tags:* `Applications`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name

### Deletes the application resource.

> Deletes the application resource identified by the name.

*Tags:* `Applications`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `applicationResourceName` - _required_ - The identity of the application.

### Gets the application resource with the given name.

> Gets the information about the application resource with the given name. The information include the description and other properties of the application.

*Tags:* `Applications`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `applicationResourceName` - _required_ - The identity of the application.

### Creates or updates an application resource.

> Creates an application resource with the specified name, description and properties. If an application resource with the same name exists, then it is updated with the specified description and properties.

*Tags:* `Applications`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `applicationResourceName` - _required_ - The identity of the application.

### Lists all the service resources.

> Gets the information about all services of an application resource. The information include the description and other properties of the Service.

*Tags:* `Services`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `applicationResourceName` - _required_ - The identity of the application.

### Gets the service resource with the given name.

> Gets the information about the service resource with the given name. The information include the description and other properties of the service.

*Tags:* `Services`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `applicationResourceName` - _required_ - The identity of the application.
* `serviceResourceName` - _required_ - The identity of the service.

### Gets replicas of a given service.

> Gets the information about all replicas of a given service of an application. The information includes the runtime properties of the replica instance.

*Tags:* `ServiceReplicas`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `applicationResourceName` - _required_ - The identity of the application.
* `serviceResourceName` - _required_ - The identity of the service.

### Gets the given replica of the service of an application.

> Gets the information about the service replica with the given name. The information include the description and other properties of the service replica.

*Tags:* `ServiceReplicas`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `applicationResourceName` - _required_ - The identity of the application.
* `serviceResourceName` - _required_ - The identity of the service.
* `replicaName` - _required_ - Service Fabric replica name.

### Gets the logs from the container.

> Gets the logs for the container of the specified code package of the service replica.

*Tags:* `CodePackages`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - Azure resource group name
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `applicationResourceName` - _required_ - The identity of the application.
* `serviceResourceName` - _required_ - The identity of the service.
* `replicaName` - _required_ - Service Fabric replica name.
* `codePackageName` - _required_ - The name of code package of the service.
* `tail` - _optional_ - Number of lines to show from the end of the logs. Default is 100.

### Gets all the gateway resources in a given resource group.

> Gets the information about all gateway resources in a given resource group. The information include the description and other properties of the Gateway.

*Tags:* `Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name

### Deletes the gateway resource.

> Deletes the gateway resource identified by the name.

*Tags:* `Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `gatewayResourceName` - _required_ - The identity of the gateway.

### Gets the gateway resource with the given name.

> Gets the information about the gateway resource with the given name. The information include the description and other properties of the gateway.

*Tags:* `Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `gatewayResourceName` - _required_ - The identity of the gateway.

### Creates or updates a gateway resource.

> Creates a gateway resource with the specified name, description and properties. If a gateway resource with the same name exists, then it is updated with the specified description and properties. Use gateway resources to create a gateway for public connectivity for services within your application.

*Tags:* `Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `gatewayResourceName` - _required_ - The identity of the gateway.

### Gets all the network resources in a given resource group.

> Gets the information about all network resources in a given resource group. The information include the description and other properties of the Network.

*Tags:* `Networks`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name

### Deletes the network resource.

> Deletes the network resource identified by the name.

*Tags:* `Networks`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `networkResourceName` - _required_ - The identity of the network.

### Gets the network resource with the given name.

> Gets the information about the network resource with the given name. The information include the description and other properties of the network.

*Tags:* `Networks`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `networkResourceName` - _required_ - The identity of the network.

### Creates or updates a network resource.

> Creates a network resource with the specified name, description and properties. If a network resource with the same name exists, then it is updated with the specified description and properties.

*Tags:* `Networks`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `networkResourceName` - _required_ - The identity of the network.

### Gets all the secret resources in a given resource group.

> Gets the information about all secret resources in a given resource group. The information include the description and other properties of the Secret.

*Tags:* `Secrets`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name

### Deletes the secret resource.

> Deletes the secret resource identified by the name.

*Tags:* `Secrets`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `secretResourceName` - _required_ - The name of the secret resource.

### Gets the secret resource with the given name.

> Gets the information about the secret resource with the given name. The information include the description and other properties of the secret.

*Tags:* `Secrets`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `secretResourceName` - _required_ - The name of the secret resource.

### Creates or updates a secret resource.

> Creates a secret resource with the specified name, description and properties. If a secret resource with the same name exists, then it is updated with the specified description and properties.

*Tags:* `Secrets`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `secretResourceName` - _required_ - The name of the secret resource.

### List names of all values of the specified secret resource.

> Gets information about all secret value resources of the specified secret resource. The information includes the names of the secret value resources, but not the actual values.

*Tags:* `SecretValues`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `secretResourceName` - _required_ - The name of the secret resource.

### Deletes the specified  value of the named secret resource.

> Deletes the secret value resource identified by the name. The name of the resource is typically the version associated with that value. Deletion will fail if the specified value is in use.

*Tags:* `SecretValues`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `secretResourceName` - _required_ - The name of the secret resource.
* `secretValueResourceName` - _required_ - The name of the secret resource value which is typically the version identifier for the value.

### Gets the specified secret value resource.

> Get the information about the specified named secret value resources. The information does not include the actual value of the secret.

*Tags:* `SecretValues`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `secretResourceName` - _required_ - The name of the secret resource.
* `secretValueResourceName` - _required_ - The name of the secret resource value which is typically the version identifier for the value.

### Adds the specified value as a new version of the specified secret resource.

> Creates a new value of the specified secret resource. The name of the value is typically the version identifier. Once created the value cannot be changed.

*Tags:* `SecretValues`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `secretResourceName` - _required_ - The name of the secret resource.
* `secretValueResourceName` - _required_ - The name of the secret resource value which is typically the version identifier for the value.

### Lists the specified value of the secret resource.

> Lists the decrypted value of the specified named value of the secret resource. This is a privileged operation.

*Tags:* `SecretValues`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `secretResourceName` - _required_ - The name of the secret resource.
* `secretValueResourceName` - _required_ - The name of the secret resource value which is typically the version identifier for the value.

### Gets all the volume resources in a given resource group.

> Gets the information about all volume resources in a given resource group. The information include the description and other properties of the Volume.

*Tags:* `Volumes`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name

### Deletes the volume resource.

> Deletes the volume resource identified by the name.

*Tags:* `Volumes`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `volumeResourceName` - _required_ - The identity of the volume.

### Gets the volume resource with the given name.

> Gets the information about the volume resource with the given name. The information include the description and other properties of the volume.

*Tags:* `Volumes`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `volumeResourceName` - _required_ - The identity of the volume.

### Creates or updates a volume resource.

> Creates a volume resource with the specified name, description and properties. If a volume resource with the same name exists, then it is updated with the specified description and properties.

*Tags:* `Volumes`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `api-version` - _required_ - The version of the API. This parameter is required and its value must be `2018-09-01-preview`.
    Possible values: 2018-09-01-preview.
* `resourceGroupName` - _required_ - Azure resource group name
* `volumeResourceName` - _required_ - The identity of the volume.

## License

**flow**ground :- Telekom iPaaS / azure-com-servicefabricmesh-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
