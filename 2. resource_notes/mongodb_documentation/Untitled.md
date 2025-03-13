MongoDb Atlas: 
The fully managed service for MongoDB

Atlas UI:
Is a multi-cloud database service that simplifies deploying and managing your databases on the cloud providers of your choice.

MongoDB Enterprise: 
The subcription-based, self-managed version of MongoDB

MongoDB Community: 
The source-available, free-to-use, and self-managed version of MongoDB

Document:
A record in MongoDB, which is a data structure composed of field and value pairs.
Similar to JSON objects.
The value of fields may include other documents, arrays, and arrays of documents.
MongoDB stores data records as documents (specifically BSON documents)
MongoDB documents are composed of field-and-value pairs.

BSON:
Is a binary representation of JSON documents, though it contains more data types than JSON.
Is a binary serialization format used to store documents and make remote procedure calls in MongoDB.

Collections:
MongoDB stores documents in Collections.
Collections are analogous to tables in relational databases.
Documents are gathered together in Collections.

MongoDB Shell (mongosh):
Is a JavaScript and Node.js REPL environment for interacting with MongoDB deployments in Atlas, locally, or on another remote host.
Use the MongoDB Shell to test queries and interact with the data in your MongoDB database.

Database:
Stores one or more collections of documents.

MongoDB Compass:
Is a powerful GUI for querying, aggregating, and analyzing your MongoDB data in a visual environment.

A MongoDB View:
Is a read-only queryable object whose contents are defined by an aggregation pipeline on other collections or views.

On-demand Materialized View:
Is a pre-computed aggregation pipeline result that is stored on and read from disk.
On-demand materialized views are typically the results of a $merge or $out stage.

Capped Collections: 
Are fixed-size collections that insert and retrieve documents based on insertion order. Work similarly to circular buffers: once a collection fills its allocated space, it makes room for new documents by overwriting the oldest documents in the collection.

Clustered Collections: 
Store indexed documents in the same WiredTiger file as the index specification.
Are created with a clustered index.

Clustered Index:
Specifies the order in which documents are stored.

MongoDB Query API 
Is the mechanism that you use to interact with your data.
Comprises two ways to query data in MongoDB:
1. CRUD Operations
2. Aggregation Pipelines

ObjectIds:
Are small, likely unique, fast to generate, and ordered. 
Values are 12 bytes in length

`binData`:
Value is a byte array.
Value has a subtype that indicates how to interpret the binary data.

BSON Timestamp:
Is **not** associated with the regular Date type.
is a 64 bit value 

BSON Date:
Is a 64-bit integer that represents the number of milliseconds since the Unix epoch (Jan 1, 1970).
Type is signed.