---
title: API
layout: rancher-api-default-v1.2
version: v1.2
lang: zh
---

## loadBalancerServiceLink



### Resource Fields

#### Writeable Fields

Field | Type | Create | Update | Default | Notes
---|---|---|---|---|---
ports | array[string] | Optional | - | - | 
serviceId | [service]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/service/) | Yes | - | - | The unique identifier of the associated service


#### Read Only Fields

Field | Type   | Notes
---|---|---
uuid | string  | The universally unique identifier for the loadBalancerServiceLink. This will always be unique across Rancher installations.


<br>
