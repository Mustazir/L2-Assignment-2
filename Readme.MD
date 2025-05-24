


### What is PostgreSQL?
PostgreSQL is a powerful, open-source relational database management system (RDBMS). It is used to store, manage, and retrieve data efficiently. PostgreSQL supports standard SQL and also offers many advanced features like support for JSON, complex queries, custom data types, and ACID-compliant transactions. It is known for its reliability, security, and scalability, and is widely used in web applications, data analytics, and enterprise systems. Being open-source, it is freely available and supported by a strong developer community.

Here is an example.
```
CREATE TABLE students (
  id SERIAL PRIMARY KEY,
  name VARCHAR(100),
  age INT,
  department VARCHAR(50)
);

```