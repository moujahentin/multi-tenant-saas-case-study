# Architecture

## High-Level Design

User
 ├── Dashboard Application
 │   └── Backend API
 │       └── Database
 │
 └── Public Tenant Website
     ├── Tenant Resolution
     └── CMS / Content API

## Components

### Backend API
Handles:
- authentication
- business logic
- data access

### Dashboard Frontend
Internal interface for managing data and operations.

### Public Site Frontend
Tenant-based dynamic websites.

### CMS
Handles dynamic content and publishing.

---

## Key Principles

- separation of concerns
- modular services
- shared authentication layer
- tenant isolation
