---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const application = {
  displayName: "New display name"
};

let res = await client.api('/applications/{id}')
	.update(application);

```