This section describes the components in the REST API Web Server in more details.

The main components are:
- REST API: A web API layer exposing the functionalities of the system in REST convention. This layer serves as the backend for the Visual Designer but also potentially as integration point with external systems in the future.
- Template Service: A code component contains all business logic for pipeline templates.
- Workflow Service: A code component contains all business logic for workflows.
- Workflow Transformer: A component for transforming the presentation model of the pipeline into the workflow model. This component abstracts away visual definition of the pipelines from the rest of the backend processing.
- DSL Transformer: A component for transforming the workflow model into DSL. This component abstracts away the details of DSL from the rest of backend processing.
- Template Repository: A component for persisting data related to pipeline templates. This component abstracts away the details of data storage logic.
- Workflow Repository: A component for persisting data related to pipelines. Same as the Template Repository, this component abstracts away the details of data storage logic.
