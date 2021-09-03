# TheHoneydewList
a small app, to host a huge list, allow taskers to add items, allow doers to feel like they are making progress

Brain dump:
* Typescript All the Things!!
* guiding principles
  * SOLID
  * Inversion of control ~ Dependencies are provided to constructors to satisfy interfaces to keep code loosely coupled.
    * https://inversify.io/
  * Manager/Engine/Dal/Repository pattern to promote separation of concerns while keeping code organized
    * managers ~ orchestrate business logic
    * Engines ~ do CPU intense work
    * Dals ~ control CRUD on domain models
    * Repositories ~ control CRUD with a specific data store
* AWS apiGateway interop
* AWS Lambda middle teir
  * Lambda ~ controller
* AWS Dynamodb storage
  * items
  * users
* AWS elastiCache 
  * sessionStore
* AWS S3 storage
  * Site host.  
    *  React front-end
  * Asset storage
  * finished project storage
* Jest, ~ Tests (no joke ;)
* CDK deployment pipeline
