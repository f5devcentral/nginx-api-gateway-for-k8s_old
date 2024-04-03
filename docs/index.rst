TechXchange 2024 Lab - NGINX API Gateway for K8S
################################################

Welcome
-------

Welcome to the |classbold| - |year|

|repoinfo|




**Lab Description:**
--------------------

F5 NGINX Plus Ingress Controller as an API Gateway for Kubernetes

You will find the UDF lab here: https://udf.f5.com/b/51ee6bf9-4f18-409a-9c29-80b847239211



**Prerequisites:**
----------------
- Kubernetes concepts: ingress, daemonset, service, etc.
- API concepts: REST API methods (GET, POST), HTTP headers (Authorization).




This is an intermediate level lab that adds API Gateway functionality to a Kubernetes NGINX Plus Ingress.
- Proxy TLS and route HTTP requests to API services based on host header and path
- API Schema Enforcement - Use OpenAPI Spec to define your API's schema and enforce the schema with an NGINX App Protect Policy
- API Authorization - Validate signed JSON Web Tokens for authorization
- API Rate-limiting - Rate-Limit API endpoints per client session to ensure fair use of the API



A big thanks to **Tony Marfil** for setting up this lab!

.. toctree::
   :maxdepth: 2
   :caption: Contents:
   :glob:

   intro*/intro*
   class*/class*
   
