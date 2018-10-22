# Syndesis Quickstarts

## Introduction to Syndesis

Syndesis is a cloud native application targeted at systems integration. It leverages Apache Camel, and adds a UI layer that helps developers, and more importantly the more technically business analysist, to create integrations without writing any code. Integrations are deployed as Spring Boot applications inside a container onto OpenShift. You can sign up with the online version of Syndesis called "Fuse Online" or you can stay with the Syndesis project code for now, and run it on MiniShift. Please see the https://syndesis.io site for installation intruction of Syndesis on Minishift. Here we will assume you have Syndesis running. Hop onto IRC (#ipaas-dev) to chat with us if you need help with any of this.

## Let's run some QuickStarts

Syndesis lets you build application without writing any code. Perhaps the easiest way to learn about Syndesis is to simply run to quickstarts. The quickstarts are zero code, so instead we offer Syndesis integration `exports` from scenarios we built for you. You can try them out by `importing` an export as an integration into Syndesis. After the import you sometimes may need to re-enter some connection information like passwords. The accompanying README should detail this. We have ordered the Quickstarts loosely ordered by simplicity, so it is recommended to start from the top of this list. Good luck, asnd please give us feedback, become part of our community and start contributing some code back! We love you!

  * [Hello World](https://github.com/syndesisio/syndesis-quickstarts/tree/master/hello-world)
  * [DB 2 DB](https://github.com/syndesisio/syndesis-quickstarts/tree/master/db-2-db)
  * [API Connector](https://github.com/syndesisio/syndesis-quickstarts/tree/master/api-provider)
