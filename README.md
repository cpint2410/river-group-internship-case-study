
# Financial Records Management Application

### Python | Flask | PostgreSQL | SQL | SharePoint | Render

A financial records management application independently developed during my IT Support & Software Development internship at River Group Content Ltd.

The application provides authenticated users with searchable access to financial invoice records through a web-based interface.

**Project confidentiality:** The original application and its source code are maintained in a private company repository. This public repository documents my individual engineering contributions and technical experience without exposing proprietary implementation details, company data or internal infrastructure.

---

## Project Overview

The organisation required a centralised solution for accessing and searching financial invoice records that had previously been maintained in legacy data files.

I independently developed a Python/Flask web application and migrated approximately 12,000 legacy financial records into a structured PostgreSQL database.

The application enables authorised users to search financial records, filter results and access associated invoice documents stored within the organisation's existing SharePoint environment.

## Key Achievements

- Migrated approximately 12,000 legacy financial records.
- Designed a relational PostgreSQL database containing approximately 7–8 related tables.
- Achieved 100% matching when validating migrated records against the original source dataset.
- Independently developed the Flask application and its database integration.
- Implemented authenticated access using Flask-Login.
- Developed search and filtering functionality.
- Integrated SharePoint document retrieval.
- Deployed the application and database using Render.
- Produced technical handover documentation for continued organisational use.

## Technical Contributions

### 1. Backend Development

Developed the application's backend using Python and Flask.

- Implemented application routes and backend logic.
- Integrated Flask with PostgreSQL.
- Developed search and filtering functionality.
- Implemented authentication using Flask-Login.
- Added input validation and protections against SQL injection.

### 2. Database Engineering

Designed and implemented a relational PostgreSQL database.

- Structured financial records across related database tables.
- Established appropriate keys and relationships.
- Migrated approximately 12,000 legacy records.
- Developed SQL queries for searching and retrieving financial information.
- Used pgAdmin for database administration and backups.

### 3. Data Migration and Validation

Performed migration of legacy financial data from .dat files through Microsoft Access and Excel into PostgreSQL.

- Processed and structured legacy records.
- Transformed records into a relational database structure.
- Validated migrated data against the original source.
- Achieved 100% matching across the relevant validated fields.

### 4. Application Integration

Integrated the application with the organisation's existing SharePoint environment.

- Linked database records with associated invoice documents.
- Enabled users to access relevant PDF documents.
- Connected application search results with document storage.

### 5. Deployment and Testing

Configured and deployed the application using Render.

- Configured application deployment and environment variables.
- Integrated GitHub with the deployment workflow.
- Troubleshot deployment and database connectivity issues.
- Tested authentication, search functionality, invalid inputs, missing records and document links.
- Prepared technical documentation and supported application handover.

## Technology Stack

| Category | Technologies |
|---|---|
| Programming | Python |
| Backend | Flask, Flask-Login |
| Database | PostgreSQL, SQL |
| Frontend | HTML, CSS, JavaScript, Bootstrap |
| Data Migration | Microsoft Access, Excel |
| Integration | SharePoint |
| Deployment | Render |
| Administration | pgAdmin |
| Version Control | Git, GitHub |

## Application Architecture

The application followed a layered approach:

1. User interface: HTML, CSS, JavaScript and Bootstrap.
2. Application backend: Python and Flask.
3. Authentication: Flask-Login.
4. Data storage: Relational PostgreSQL database.
5. Document integration: SharePoint.
6. Hosting: Render.

## Professional Experience

**River Group Content Ltd**

IT Support & Software Development Intern  
July 2026 – August 2026

Worked independently on the development, deployment and handover of a financial records management application.

The original implementation remains private and is not included in this repository.

## Confidentiality

This repository intentionally excludes:

- Original application source code.
- Company financial records.
- Supplier and customer information.
- Database credentials and connection strings.
- Internal infrastructure configurations.
- Proprietary company documentation.

This case study is intended to demonstrate my individual software engineering experience while respecting organisational confidentiality.
