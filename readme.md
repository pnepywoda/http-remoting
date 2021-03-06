HTTP Remoting Utilities
=======================
This repository holds a small collection of useful utilties for use with HTTP Remoting setups,
in particular those that use Feign as a client and Jersey as a server.

http-clients
--------------
Provides Feign decoders for translating HTTP error codes to appropriate JAX-RS Java exceptions,
and utilities for creating Feign clients in commonly used configurations. Additionally,
offers a basic round-robin failover client configuration for basic failover between multiple
equivalent endpoints.

trust-stores
------------
Provides utiltiies for interacting with Java trust stores and acquiring `SSLSocketFactory`
instances using those trust stores, as well as a configuration class for use in server
configuration files.

error-handling
--------------
Provides utilities for relaying Java exceptions across JVM boundaries by serializing exceptions
as JSON POJOs.

http-servers
------------
Provides Dropwizard/Jersey exception mappers for translating common JAX-RS exceptions to
appropriate HTTP error codes.

License
-------
This repository is made available under the [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0).
