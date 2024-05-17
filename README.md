# Neo4j-Streaming-Demo

### postgresql
```
INSERT INTO Customers VALUES(300,'Alfreds Futterkiste','Maria Anders','Obere Str. 57','Berlin','12209','Germany');
```
### Neo4j
```
MATCH (c:Customer {CustomerID: 200})
RETURN c
```
### Postgresql
```
DELETE FROM Customers
WHERE CustomerID = 200;
```
### Neo4j
```
MATCH (c:Customer {CustomerID: 200})
RETURN c
```
