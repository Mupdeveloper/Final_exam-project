# Final_exam-project
# Campus Lost and Found Management System

**Course:** DMBS with PL/SQL  
**Student:** Mukunzi Prince  
**Student ID:** 20252IMA 128  
**Group:** B – Tuesday  
**Project Domain:** Other  
**Project Status:** Proposed – Awaiting Title Approval

## 1. Project Overview

The Campus Lost and Found Management System is a proposed database management system designed to organize the reporting, recording, tracking, and recovery of lost and found items within a university campus.

The system will provide a centralized database where students, staff, and authorized administrators can record lost belongings and items that have been found on campus. Each item will have relevant information, including its description, category, location, date reported, and current status.

The system will also support the process of submitting and reviewing ownership claims before an item is returned. This will help maintain accurate records of reported items and their recovery status.

The project will use Oracle Database and PL/SQL to organize and manage the information. It will demonstrate how database tables, relationships, constraints, SQL queries, procedures, functions, triggers, and reports can support a practical information management process.

## 2. Problem Statement

Students and staff may lose personal belongings such as identity cards, phones, books, keys, bags, and other personal items while on campus.

In many situations, information about these items is shared through informal conversations, class groups, notice boards, or separate reports. These approaches can make it difficult to keep information organized and accessible.

The main problems include:

- **Scattered information:** Lost and found item details may be shared through different communication channels.
- **Difficulty finding items:** People may not know whether an item they lost has already been found.
- **Unorganized records:** Without a centralized record, it can be difficult to track reported items and their current status.
- **Ownership verification:** An item may be claimed by someone without a properly recorded verification process.
- **Limited tracking:** It may be difficult to determine whether an item is still missing, has been found, has a pending claim, or has been returned.
- **Lack of reports:** Administrators may not have a clear record of the number of lost items, found items, successful claims, and unreturned belongings.

This project proposes a centralized database system to address these challenges by organizing item reports, recording claims, supporting ownership verification, and tracking the return of belongings.

## 3. Proposed Project Structure

The project will be organized into the following sections:

```text
Campus-Lost-and-Found-Management-System/
│
├── README.md
│
├── docs/
│   ├── project_overview.md
│   ├── problem_statement.md
│   ├── requirements.md
│   └── database_design.md
│
├── database/
│   ├── schema/
│   │   ├── create_tables.sql
│   │   ├── primary_foreign_keys.sql
│   │   └── constraints.sql
│   │
│   ├── sample_data/
│   │   └── insert_sample_data.sql
│   │
│   ├── procedures/
│   │
│   ├── functions/
│   │
│   ├── triggers/
│   │
│   ├── packages/
│   │
│   └── reports/
│
└── diagrams/
    ├── er_diagram.png
    └── database_relationships.png
```

### Proposed Main Database Entities

The database is expected to include the following entities:

- **USERS:** Stores information about students, staff, and administrators.
- **ITEMS:** Stores details of lost and found belongings.
- **CATEGORIES:** Organizes items into categories.
- **LOCATIONS:** Records where an item was lost or found.
- **CLAIMS:** Stores ownership claims submitted for found items.
- **HANDOVERS:** Records the return of verified items to their owners.



## 4. Initial Project Scope

The proposed system will focus on:

1. Recording lost and found items.
2. Searching and viewing reported items.
3. Managing item categories and locations.
4. Recording ownership claims.
5. Tracking item status.
6. Recording verified item handovers.
7. Generating reports about lost, found, claimed, and returned items.

