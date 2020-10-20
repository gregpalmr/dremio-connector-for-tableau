# dremio-connector-for-tableau
A tutorial for using the Dremio Connector for Tableau

---

In the past, Tableau users utilized the Dremio ODBC driver to connect to the Dremio Data Lake Engine from their Tableau workbooks using the “Other Database” option. Now Dremio offers a customized connector for Tableau that is available from the Tableau Extension Gallery. This new connector was created using the Tableau Connector SDK and offers better performance and more features over the basic driver, including:

* Better live query support. Allows a customized SQL dialect to generate queries that are optimized for Dremio. 
* Simpler connection experience. Users don’t need to enter obscure JDBC URL strings or create a DSN or configure odbc.ini files. The connector provides a simple Dremio connection dialog.
* Runs in Tableau Desktop and Tableau Server. No configuration is required once you install the connector.
* Enables the use of Tableau’s “Impersonate using embedded password” feature combined with Dremio’s “Inbound Impersonation” feature.

### Architecture

The Dremio Connector for Tableau architecture is illustrated in the following diagram.

(/images/dremio-connector-for-tableau-architecture.png "Title")

### The Tutorial

The Tutorial on using the Dremio Tableau Connector is located [a here.][1]

####
Please direct comments or questions to greg@dremio.com

[1]: /documents/Using_the_Dremio_Connector_for_Tableau.pdf
