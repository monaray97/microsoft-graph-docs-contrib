---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = Application(
	display_name = "New display name",
)

result = await graph_client.applications.by_application_id('application-id').patch(body = request_body)


```