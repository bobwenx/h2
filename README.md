h2
==

This project provides patch for h2 database, it add HTTP transport support.It is used when a separate servlet engine (or application server) such as Tomcat or Resin provides access to the database. The Servlet Mode cannot be started independently from the servlet engine.

Both HTTP Server and Servlet modes can be accessed using the JDBC driver at the client end. They do not provide a web front end to the database. The Servlet mode can serve multiple databases.
