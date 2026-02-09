# Music Streaming Data Engineering Project
**MSc Data Science | University of Europe for Applied Sciences, Potsdam**

## Project Overview
This repository contains a complete data engineering workflow for a music streaming service, ranging from relational modeling to REST API implementation.

## Step 1: Data Modeling
![Entity Relationship Diagram](./Step-1-Modeling/Data%20engineering%20STEP%201.png)

* **Architecture**: 8-table relational schema designed for the 2025 music industry.
* **Normalization**: Features complex many-to-many relationships using junction tables for `playlist_songs` and `song_genres`.
* **Integrity**: Utilizes composite primary keys, foreign keys, and strict constraints (NOT NULL, UNIQUE).

## Repository Structure
* **/Step-1-Modeling**: Schema design and ERD visual.
* **/Step-2-Implementation**: SQL scripts and database report for Supabase (PostgreSQL).
* **/Step-3-API**: Documented Postman collection with 20+ CRUDL endpoints.

## Technical Highlights
* **Advanced SQL**: Implementation of aggregate subqueries, multi-table joins, and window functions like `DENSE_RANK`.
* **API Operations**: Comprehensive coverage including batch creation, fuzzy search (ilike), and pagination.

## Contact
**Jhanavi Venkatesh**
jhanaviv6@gmail.com
