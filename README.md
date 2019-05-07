# ![LOGO](logo.png) Cenit IO - REST API Specification **flow**ground Connector

## Description

A generated **flow**ground connector for the Cenit IO - REST API Specification API (version v1).

Generated from: https://api.apis.guru/v2/specs/cenit.io/v1/swagger.json<br/>
Generated at: 2019-05-07T17:39:54+03:00

## API Description

Cenit IO is an Open Platform for Data and Business Integration (iPaaS)


## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### Returns a list of connections

> Returns a list of connections you've previously created. The connections are returned in sorted order, with the most recent connection appearing first.

*Tags:* `Connection`

### Create or update a connection

> Creates or updates the specified connection by setting the values of the parameters passed. Any parameters not provided will be left unchanged.

*Tags:* `Connection`

### Delete a connection

> Permanently deletes a connection. It cannot be undone.

*Tags:* `Connection`

#### Input Parameters
* `id` - _required_ - Connection ID

### Retrieve an existing connection

> Retrieves the details of an existing connection. You need only supply the unique connection identifier that was returned upon connection creation.

*Tags:* `Connection`

#### Input Parameters
* `id` - _required_ - Connection ID

### Returns a list of connection roles

> Returns a list of connection roles you've previously created. The connection roles are returned in sorted order, with the most recent connection role appearing first.

*Tags:* `Connection Role`

### Create or update a connection role

> Creates or updates the specified connection role by setting the values of the parameters passed. Any parameters not provided will be left unchanged.

*Tags:* `Connection Role`

### Delete a connection role.

> Deletes the specified connection role.

*Tags:* `Connection Role`

#### Input Parameters
* `id` - _required_ - Connection role ID

### Return a connection role

> Returns a connection role

*Tags:* `Connection Role`

#### Input Parameters
* `id` - _required_ - Connection role ID

### Returns a list of data types

> Returns a list of data types you've previously created. The data types are returned in sorted order, with the most recent DataType appearing first.

*Tags:* `Data Type`

### Create or update a data type

> Creates or updates the specified data type by setting the values of the parameters passed. Any parameters not provided will be left unchanged.

*Tags:* `Data Type`

### Delete a data type

> Deletes the specified data type.

*Tags:* `Data Type`

#### Input Parameters
* `id` - _required_ - data type ID

### Retrieve a data type

> Retrieves the details of an existing data type. You need only supply the unique data  type identifier that was returned upon DataType creation.

*Tags:* `Data Type`

#### Input Parameters
* `id` - _required_ - data type ID

### Returns a list of flows

> Returns a list of flows you've previously created. The flows are returned in sorted order, with the most recent flow appearing first.

*Tags:* `Flow`

### Create or update a flow

> Creates or updates the specified flow. Any parameters not provided will be left unchanged.

*Tags:* `Flow`

### Delete a flow.

> Deletes the specified flow.

*Tags:* `Flow`

#### Input Parameters
* `id` - _required_ - Flow ID

### Retrieve an existing flow

> Retrieves the details of an existing flow. You need only supply the unique flow identifier that was returned upon flow creation.

*Tags:* `Flow`

#### Input Parameters
* `id` - _required_ - Flow ID

### Returns a list of namespaces

> Returns a list of namespaces you've previously created. The namespaces are returned in sorted order, with the most recent namespace appearing first.

*Tags:* `Namespace`

### Create or update a namespace

> Creates or updates the specified namespace. Any parameters not provided will be left unchanged.

*Tags:* `Namespace`

### Delete a namespace

> Deletes the specified namespace.

*Tags:* `Namespace`

#### Input Parameters
* `id` - _required_ - Namespace ID.

### Retrieve an existing namespace

> Retrieves the details of an existing namespace. You need only supply the unique webhook namespace that was returned upon namespace creation.

*Tags:* `Namespace`

#### Input Parameters
* `id` - _required_ - Namespace ID.

### Returns a list of events

> Returns a list of events you've previously created. The events are returned in sorted order, with the most recent event appearing first.

*Tags:* `Data Event`

### Create or update an event

> Creates or updates the specified event observer. Any parameters not provided will be left unchanged.

*Tags:* `Data Event`

### Delete an event

> Deletes the specified event observer.

*Tags:* `Data Event`

#### Input Parameters
* `id` - _required_ - Observer ID

### Retrieve an existing event

> Retrieves the details of an existing event. You need only supply the unique event identifier that was returned upon event creation.

*Tags:* `Data Event`

#### Input Parameters
* `id` - _required_ - Observer ID

### Returns a list of schedulers

> Returns a list of schedulers you've previously created. The schedulers are returned in sorted order, with the most recent scheduler appearing first.

*Tags:* `Scheduler`

### Create or update an scheduler

> Creates or updates the specified scheduler. Any parameters not provided will be left unchanged.

*Tags:* `Scheduler`

### Delete an schedule

> Deletes the specified scheduler.

*Tags:* `Scheduler`

#### Input Parameters
* `id` - _required_ - Scheduler ID

### Retrieve an existing schedule

> Retrieves the details of an existing scheduler. You need only supply the unique scheduler identifier that was returned upon scheduler creation.

*Tags:* `Scheduler`

#### Input Parameters
* `id` - _required_ - Scheduler ID

### Returns a list of schemas

> Returns a list of schemas you've previously created. The schemas are returned in sorted order, with the most recent schema appearing first.

*Tags:* `Schema`

### Create or update an schema

> Creates or updates the specified schema. Any parameters not provided will be left unchanged.

*Tags:* `Schema`

### Delete an schema.

> Deletes the specified schema.

*Tags:* `Schema`

#### Input Parameters
* `id` - _required_ - Schema ID

### Retrieve an existing schema

> Retrieves the details of an existing schema. You need only supply the unique schema identifier that was returned upon schema creation.

*Tags:* `Schema`

#### Input Parameters
* `id` - _required_ - Schema ID

### Returns a list of translators

> Returns a list of translators you've previously created. The translators are returned in sorted order, with the most recent translator appearing first.

*Tags:* `Translator`

### Create or update a translator

> Creates or updates the specified translator. Any parameters not provided will be left unchanged.

*Tags:* `Translator`

### Delete a translator

> Deletes the specified translator.

*Tags:* `Translator`

#### Input Parameters
* `id` - _required_ - Translator ID.

### Retrieve an existing translator

> Retrieves the details of an existing translator. You need only supply the unique translator identifier that was returned upon translator creation.

*Tags:* `Translator`

#### Input Parameters
* `id` - _required_ - Translator ID.

### Returns a list of webhooks

> Returns a list of webhooks you've previously created. The webhooks are returned in sorted order, with the most recent webhook appearing first.

*Tags:* `Webhook`

### Create or update a webhook

> Creates or updates the specified webhook. Any parameters not provided will be left unchanged.

*Tags:* `Webhook`

### Delete a webhook

> Deletes the specified webhook.

*Tags:* `Webhook`

#### Input Parameters
* `id` - _required_ - Webhook ID.

### Retrieve an existing webhook

> Retrieves the details of an existing webhook. You need only supply the unique webhook identifier that was returned upon webhook creation.

*Tags:* `Webhook`

#### Input Parameters
* `id` - _required_ - Webhook ID.

## License

**flow**ground :- Telekom iPaaS / cenit-io-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
