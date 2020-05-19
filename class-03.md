# Data Modeling & NoSQL Databases

- Why would a developer choose to make data models?
A data model not only improves the conceptual quality of an application, it also lets you leverage database features that improve data quality. Developers can weave constraints into the fabric of a model and the resulting database. For example, every table should normally have a primary key. The database can enforce other unique combinations of fields. Referential integrity can ensure that foreign keys are bona fide and not dangling.

- What purpose do CRUD operations serve? To make the models able to provide four basic types of functionality. The model must be able to Create, Read, Update, and Delete resources.

- What kind of database is Postgres? What kind of database is MongoDB?
Postgres : object-relational database management system.
MongoDB : document-oriented database program.

- What is Mongoose and why do we need it? Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node. js. It manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB.

- Define three related pieces of data in a possible application.An example for a store application might be Product, Category and Department. Describe the constraints and rules on each piece of data and how you would relate these pieces to each other. For example, each Product has a Category and belongs in a Department.

---------------------------------------------------------------------------------------------------------------

# Vocabulary Terms:

- Database:

- Data model: Data models can facilitate interaction among the designer, the applications programmer, and the end user. A well-developed data model can even foster improved understanding of the organization for which the database design is developed. In short, data models are a communication tool.

- CRUD: create, read, update, and delete[1] (CRUD) are the four basic functions of persistent storage.

- Schema: The database schema of a database is its structure described in a formal language supported by the database management system (DBMS). The term "schema" refers to the organization of data as a blueprint of how the database is constructed (divided into database tables in the case of relational databases).

- Sanitize: Data sanitization is the process of deliberately, permanently and irreversibly removing or destroying the data stored on a memory device to make it unrecoverable. A device that has been sanitized has no usable residual data, and even with the assistance of advanced forensic tools, the data will not ever be recovered.

- Structured Query Language (SQL): SQL is a domain-specific language used in programming and designed for managing data held in a relational database management system, or for stream processing in a relational data stream management system.

- Non SQL (NoSQL): A NoSQL (originally referring to "non SQL" or "non relational") database provides a mechanism for storage and retrieval of data that is modeled in means other than the tabular relations used in relational databases.

- MongoDB: MongoDB is a cross-platform document-oriented database program. Classified as a NoSQL database program, MongoDB uses JSON-like documents with schema. MongoDB is developed by MongoDB Inc. and licensed under the Server Side Public License.

- Mongoose: Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node. js. It manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB.

- Record: a record is a group of related data held within the same structure. More specifically, a record is a grouping of fields within a table that reference one particular object. The term record is frequently used synonymously with row.

- Document: A document database is a type of nonrelational database that is designed to store and query data as JSON-like documents. Document databases make it easier for developers to store and query data in a database by using the same document-model format they use in their application code.

- Object Relation Mapping (ORM): Object-relational mapping in computer science is a programming technique for converting data between incompatible type systems using object-oriented programming languages. This creates, in effect, a "virtual object database" that can be used from within the programming language.

