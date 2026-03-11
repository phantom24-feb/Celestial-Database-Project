CELESTIAL DATABASE PROJECT
A relational database designed as part of the freecodecamp Relational Database Certification. This project
demonstrates the ability to architect a multi level data hierachy using PostgreSQL, focusing on referential integrity, complex data types, and relational schema design.

PROJECT OVERVIEW
the "Universe" database stores structured information about the cosmos, organized into a four tier hierachy:
1. Galaxies (Parent to Stars).
2. Star (Parent to Planets).
3. Planet (Parent to Moons).
4. Moons (Leaf nodes).

TECHNICAL FEATURES
. Relational Mapping: Implements One-to-Many relationships using foreign keys.
. Data Integrity: Uses NOT NULL and UNIQUE constraints to ensure data quality.
. Diverse Data Types: Utilizes INT, NUMERIC,(for astronomical distances/ages), BOOLEAN (for physical properties), and TEXT.
. Scalable Schema: Designed to handle nested structures, such as linking 15+ moons to their respective parent planet.

DATABASE SCHEMA
The ddatabase consists of the following tables:
. galaxy: Stores 6 unique galaxies with properties.
. star: Contains 6 stars, each referencing a parent galaxy.
. planet: Contains 12 planets, each referencing a parent star.
. moon: Contains 20 moons, each referencing a parent planet.

HOW TO RUN
To recreat this database locally:
1. Ensure you have PostgreSQL installed.
2. Create a database named universe.
3. Import the schema and data from the .sql file.

AUTHOR
Udegbunam Tochukwu Donatus
Aspiring Backend Developer and Mechatronics Engineer.
