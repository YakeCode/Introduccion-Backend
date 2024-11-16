# Bases de Datos

Las Bases de datos son un servicio en el cual se almacenan datos del negocio. En este mismo servidor podríamos tener varias bases de datos corriendo en conjunto, incluso de tecnologías diferentes.

Las APIS por lo general consumen cpu y ram, mientras que las bases de datos al tener un manejo de datos mas extenso lo que van hacer es a consumir mas almacenamiento,

La forma en como se conectan los servidores con las bases de datos es a traves de drivers los cuales son la estructura en como se van a registrar y solicitar los datos. Dichos Drivers pueden utilizarse en varios lenguajes de programación.

# SQL Bases de datos relacionales

Tienen un lenguaje en común el cual se llama SQL

- My SQL

- PostgreSQL

- ORACLE

**ORMS :** object relational Mapping -> es una forma de abstraer la conexión a las bases de datos utilizando la programación orientada a objetos, enfocándose a hacer peticiones a base de datos siendo un poco agnóstico, lo cual quiere decir que podemos cambiar entre bases de datos **SQL** fácilmente

# NoSQL Bases de datos no relacionales

No tienen un lenguaje en común

- mongoDB

- Cassandra

- Couchbase
