MongoDB Regulatory Compliance Database
Overview
This project aims to create a MongoDB database to track regulatory requirements and compliance efforts for government agencies and regulated entities. The database will consist of multiple collections to store information about agencies, regulations, entities, requirements, and compliance efforts.

Database Schema
Collections:
agencies: Stores information about government agencies.

Fields: name, abbreviation, location, type
regulations: Stores information about regulations.

Fields: name, type, status
entities: Stores information about regulated entities.

Fields: name, type, location
requirements: Stores information about regulatory requirements.

Fields: category, description, agency
compliance_efforts: Stores information about compliance efforts made by entities.

Fields: requirement_id, entity, status
Usage
Setting Up the Database:

Install MongoDB on your system.
Create a database named regulatory_compliance.
Populating the Database:

Insert documents into each collection using the provided data or your own data.
Importing Data from Excel:

Prepare Excel files containing data for each collection.
Use mongoimport command to import data from Excel files into the database.
Performing CRUD Operations:

Use insertOne, insertMany, updateOne, updateMany, findOne, find, deleteOne, and deleteMany commands to perform CRUD operations.
Query Optimization:

Create indexes based on common queries to improve performance.
Aggregation and Analysis:

Utilize MongoDB aggregation functions and pipelines for data analysis.
Workload Analysis
Common Queries:

List of common queries and their execution stats.
Query 1: Find all agencies located in a specific city.
Query 2: Retrieve regulations related to water quality.
Query 3: Find entities of a specific type.
Query 4: List compliance efforts for a particular regulation.
Query 5: Retrieve requirements for a specific entity.
Indexing:

Create indexes based on workload to optimize query performance.
Aggregation:

Show implementation of 7 different MongoDB aggregation functions.
Show at least 3 different aggregation pipelines using MongoDB.
