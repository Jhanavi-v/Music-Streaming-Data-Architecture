# Music Streaming Data Engineering Project
**MSc Data Science | [cite_start]University of Europe for Applied Sciences, Potsdam** [cite: 1202]

## Project Overview
[cite_start]This repository contains a complete data engineering workflow for a music streaming service, ranging from relational modeling to REST API implementation[cite: 1203, 1208].

## Step 1: Data Modeling
![Entity Relationship Diagram](./Step-1-Modeling/Data%20engineering%20STEP%201.png)

* [cite_start]**Architecture**: 8-table relational schema designed for the 2025 music industry[cite: 1209, 1214].
* **Normalization**: Features complex many-to-many relationships using junction tables for `playlist_songs` and `song_genres`[cite: 1209, 1210].
* [cite_start]**Integrity**: Utilizes composite primary keys, foreign keys, and strict constraints (NOT NULL, UNIQUE)[cite: 1211, 1216].

## Repository Structure
* [cite_start]**/Step-1-Modeling**: Schema design and ERD visual[cite: 1208].
* **/Step-2-Implementation**: SQL scripts and database report for Supabase (PostgreSQL)[cite: 1212, 1213].
* [cite_start]**/Step-3-API**: Documented Postman collection with 20+ CRUDL endpoints[cite: 1219, 1220].

## Technical Highlights
* [cite_start]**Advanced SQL**: Implementation of aggregate subqueries, multi-table joins, and window functions like `DENSE_RANK`[cite: 1218].
* [cite_start]**API Operations**: Comprehensive coverage including batch creation, fuzzy search (ilike), and pagination[cite: 1223, 1227].

[cite_start]**Jhanavi Venkatesh** [cite: 1206]
*MSc Data Science Student, UE Potsdam*