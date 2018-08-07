
| **Description for Platform (SIP)** | **Method** | **Production URL** | **Sandbox URL** |
| ---------------------------------- | ---------- | ------------------ | --------------- |
|Platform Pipeline Swagger UI|GET|platform.newdomain.com/visibility/pipeline/swagger-ui.html|platform-sandbox.newdomain.com/visibility/pipeline/swagger-ui.html|
|Platform Pipeline Open API Spec|GET|platform.newdomain.com/visibility/pipeline/v2/api-docs|platform-sandbox.newdomain.com/visibility/pipeline/v2/api-docs|
|Platform Pipeline Swagger Dependencies|GET|platform.newdomain.com/visibility/pipeline/*|platform-sandbox.newdomain.com/visibility/pipeline/*|
|Post Events|POST|platform.newdomain.com/visibility/v1/events/EXXX|platform-sandbox.newdomain.com/visibility/v1/events/EXXX|
|Platform Query Swagger UI|GET|platform.newdomain.com/visibility/query/swagger-ui.html|platform-sandbox.newdomain.com/visibility/query/swagger-ui.html|
|Platform Query Open API Spec|GET|platform.newdomain.com/visibility/query/v2/api-docs|platform-sandbox.newdomain.com/visibility/query/v2/api-docs|
|Platform Query Swagger Dependencies|GET|platform.newdomain.com/visibility/query/*|platform-sandbox.newdomain.com/visibility/query/*|
|Query events by delegation ID|GET|platform.newdomain.com/visibility/v1/events/{id}|platform-sandbox.newdomain.com/visibility/v1/events/{id}|
|Query all shipments|GET|platform.newdomain.com/visibility/v1/shipments/{id}|platform-sandbox.newdomain.com/visibility/v1/shipments/{id}|
|Query transport summary by ID|GET|platform.newdomain.com/visibility/v1/transportSummaries/{id}|platform-sandbox.newdomain.com/visibility/v1/transportSummaries/{id}|
|Query all country codes|GET|platform.newdomain.com/visibility/v1/countryCodes|platform-sandbox.newdomain.com/visibility/v1/countryCodes|
|Query all event types|GET|platform.newdomain.com/visibility/v1/eventTypes|platform-sandbox.newdomain.com/visibility/v1/eventTypes|
|Platform Subscription Swagger UI|GET|platform.newdomain.com/visibility/subscription/swagger-ui.html|platform-sandbox.newdomain.com/visibility/subscription/swagger-ui.html|
|Platform Subscription Open API Spec|GET|platform.newdomain.com/visibility/subscription/v2/api-docs|platform-sandbox.newdomain.com/visibility/subscription/v2/api-docs|
|Platform Subscription Swagger Dependencies|GET|platform.newdomain.com/visibility/subscription/*|platform-sandbox.newdomain.com/visibility/subscription/*|
|Get all subscriptions|GET|platform.newdomain.com/visibility/v1/subscriptions|platform-sandbox.newdomain.com/visibility/v1/subscriptions|
|Retrieve a subscription|GET|platform.newdomain.com/visibility/v1/subscriptions/{id}|platform-sandbox.newdomain.com/visibility/v1/subscriptions/{id}|
|Update the webhook for a subscription|PUT|platform.newdomain.com/visibility/v1/subscriptions/{id}|platform-sandbox.newdomain.com/visibility/v1/subscriptions/{id}|
|Delete a subscription|DELETE|platform.newdomain.com/visibility/v1/subscriptions/{id}|platform-sandbox.newdomain.com/visibility/v1/subscriptions/{id}|
|Create a country subscription|POST|platform.newdomain.com/visibility/v1/subscriptions/country|platform-sandbox.newdomain.com/visibility/v1/subscriptions/country|
|Create a port subscription|POST|platform.newdomain.com/visibility/v1/subscriptions/port|platform-sandbox.newdomain.com/visibility/v1/subscriptions/port|
|Create a delegation ID subscription|POST|platform.newdomain.com/visibility/v1/subscriptions/delegationId|platform-sandbox.newdomain.com/visibility/v1/subscriptions/delegationId|
|Create an org subscription|POST|platform.newdomain.com/visibility/v1/subscriptions/org|platform-sandbox.newdomain.com/visibility/v1/subscriptions/org|
|Create a terminal subscription|POST|platform.newdomain.com/visibility/v1/subscriptions/terminal|platform-sandbox.newdomain.com/visibility/v1/subscriptions/terminal|
|Get all subscriptions (filter by type)|GET|platform.newdomain.com/visibility/v2/subscriptions|platform-sandbox.newdomain.com/visibility/v2/subscriptions|
|||||
| **Description for Paperless Trade** | **Method** | **Production URL** | **Sandbox URL** |
|PT Swagger UI|GET|platform.newdomain.com/contentshare/swagger-ui.html|platform-sandbox.newdomain.com/contentshare/swagger-ui.html|
|PT Open API Spec|GET|platform.newdomain.com/contentshare/v2/api-docs|platform-sandbox.newdomain.com/contentshare/v2/api-docs|
|PT Swagger Dependencies|GET|platform.newdomain.com/contentshare/*|platform-sandbox.newdomain.com/contentshare/*|
|Get all shipments|GET|platform.newdomain.com/contentshare/v1/shipments|platform-sandbox.newdomain.com/contentshare/v1/shipments|
|Add new shipment|POST|platform.newdomain.com/contentshare/v1/shipments|platform-sandbox.newdomain.com/contentshare/v1/shipments|
|Delete shipment|DELETE|platform.newdomain.com/contentshare/v1/shipments/{id}|platform-sandbox.newdomain.com/contentshare/v1/shipments/{id}|
|Update a shipment|PATCH|platform.newdomain.com/contentshare/v1/shipments/{id}|platform-sandbox.newdomain.com/contentshare/v1/shipments/{id}|
|Get shipment documents|GET|platform.newdomain.com/contentshare/v1/shipments/{id}/documents|platform-sandbox.newdomain.com/contentshare/v1/shipments/{id}/documents|
|Add document to shipment|POST|platform.newdomain.com/contentshare/v1/shipments/{id}/documents|platform-sandbox.newdomain.com/contentshare/v1/shipments/{id}/documents|
|Get shipment document|GET|platform.newdomain.com/contentshare/v1/shipments/{id}/documents/{id}|platform-sandbox.newdomain.com/contentshare/v1/shipments/{id}/documents/{id}|
|Update shipment document|PATCH|platform.newdomain.com/contentshare/v1/shipments/{id}/documents/{id}|platform-sandbox.newdomain.com/contentshare/v1/shipments/{id}/documents/{id}|
|Get shipment document attachments|GET|platform.newdomain.com/contentshare/v1/shipments/{id}/documents/{id}/attachments|platform-sandbox.newdomain.com/contentshare/v1/shipments/{id}/documents/{id}/attachments|
|Add shipment document attachment|POST|platform.newdomain.com/contentshare/v1/shipments/{id}/documents/{id}/attachments|platform-sandbox.newdomain.com/contentshare/v1/shipments/{id}/documents/{id}/attachments|
|Get shipment document attachment|GET|platform.newdomain.com/contentshare/v1/shipments/{id}/documents/{id}/attachments/{id}|platform-sandbox.newdomain.com/contentshare/v1/shipments/{id}/documents/{id}/attachments/{id}|
|Update shipment document attachment|PATCH|platform.newdomain.com/contentshare/v1/shipments/{id}/documents/{id}/attachments/{id}|platform-sandbox.newdomain.com/contentshare/v1/shipments/{id}/documents/{id}/attachments/{id}|
|Get all shipment document events|GET|platform.newdomain.com/contentshare/v1/shipments/{id}/documents/{id}/events|platform-sandbox.newdomain.com/contentshare/v1/shipments/{id}/documents/{id}/events|
|Get next actions for shipment|GET|platform.newdomain.com/contentshare/v1/shipments/{id}/nextActions|platform-sandbox.newdomain.com/contentshare/v1/shipments/{id}/nextActions|
|Get all workflows|GET|platform.newdomain.com/contentshare/v1/workflows|platform-sandbox.newdomain.com/contentshare/v1/workflows|
|Create a workflow|POST|platform.newdomain.com/contentshare/v1/workflows|platform-sandbox.newdomain.com/contentshare/v1/workflows|
|Get a workflow|GET|platform.newdomain.com/contentshare/v1/workflows/{id}|platform-sandbox.newdomain.com/contentshare/v1/workflows/{id}|
|Update a workflow|PATCH|platform.newdomain.com/contentshare/v1/workflows/{id}|platform-sandbox.newdomain.com/contentshare/v1/workflows/{id}|
|Delete a workflow|DELETE|platform.newdomain.com/contentshare/v1/workflows/{id}|platform-sandbox.newdomain.com/contentshare/v1/workflows/{id}|
|Get all workflow mappings|GET|platform.newdomain.com/contentshare/v1/workflowMappings|platform-sandbox.newdomain.com/contentshare/v1/workflowMappings|
|Create a workflow mapping|PUT|platform.newdomain.com/contentshare/v1/workflowMappings|platform-sandbox.newdomain.com/contentshare/v1/workflowMappings|
|Get a workflow mapping|GET|platform.newdomain.com/contentshare/v1/workflowMappings/{id}|platform-sandbox.newdomain.com/contentshare/v1/workflowMappings/{id}|
|Delete a workflow mapping|DELETE|platform.newdomain.com/contentshare/v1/workflowMappings/{id}|platform-sandbox.newdomain.com/contentshare/v1/workflowMappings/{id}|
|Get all workflow participant groups|GET|platform.newdomain.com/contentshare/v1/workflowParticipantGrps|platform-sandbox.newdomain.com/contentshare/v1/workflowParticipantGrps|
|Create a workflow participant group|POST|platform.newdomain.com/contentshare/v1/workflowParticipantGrps|platform-sandbox.newdomain.com/contentshare/v1/workflowParticipantGrps|
|Get a workflow participant group|GET|platform.newdomain.com/contentshare/v1/workflowParticipantGrps/{id}|platform-sandbox.newdomain.com/contentshare/v1/workflowParticipantGrps/{id}|
|Update a workflow participant group|PUT/PATCH|platform.newdomain.com/contentshare/v1/workflowParticipantGrps/{id}|platform-sandbox.newdomain.com/contentshare/v1/workflowParticipantGrps/{id}|
|Delete a workflow participant group|DELETE|platform.newdomain.com/contentshare/v1/workflowParticipantGrps/{id}|platform-sandbox.newdomain.com/contentshare/v1/workflowParticipantGrps/{id}|
|Get all transactions|GET|platform.newdomain.com/contentshare/v1/transactions|platform-sandbox.newdomain.com/contentshare/v1/transactions|
|Get a transaction|GET|platform.newdomain.com/contentshare/v1/transactions/{id}|platform-sandbox.newdomain.com/contentshare/v1/transactions/{id}|
|Get Visibility event mappings|GET|platform.newdomain.com/contentshare/v1/eventMappings|platform-sandbox.newdomain.com/contentshare/v1/eventMappings|
|Create a Visibility event mapping|POST|platform.newdomain.com/contentshare/v1/eventMappings|platform-sandbox.newdomain.com/contentshare/v1/eventMappings|
|Get a Visibility event mapping|GET|platform.newdomain.com/contentshare/v1/eventMappings/{id}|platform-sandbox.newdomain.com/contentshare/v1/eventMappings/{id}|
|Delete a Visibility event mapping|DELETE|platform.newdomain.com/contentshare/v1/eventMappings/{id}|platform-sandbox.newdomain.com/contentshare/v1/eventMappings/{id}|
|Fetch all the documentMetadata|GET|platform.newdomain.com/contentshare/v1/documentsMetadata|platform-sandbox.newdomain.com/contentshare/v1/documentsMetadata|
|Fetch documentMetadata|GET|platform.newdomain.com/contentshare/v1/documentsMetadata{id}|platform-sandbox.newdomain.com/contentshare/v1/documentsMetadata{id}|
