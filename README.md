 # CreatorPulse: Social Media Content Performance Tracker

**Student Name:** Odile IRIHO  
**Student ID:** 28965  
**Course:** INSY 8311 - PL/SQL  
**Group:** Wednesday Group C

## 1. Project Overview

CreatorPulse is a social media content performance tracking system designed for individual content creators and social media managers. It will help users monitor, compare and analyze the performance of their published content using statistics such as views, likes, comments, shares and saves.

The system will use an Oracle database and PL/SQL to manage content performance data, calculate engagement rates and identify top-performing posts.

## 2. Problem Statement

Content creators and social media managers often struggle to keep track of how their published content performs. When performance statistics are scattered across different platforms, comparing posts and identifying successful content becomes difficult.

CreatorPulse aims to address this problem by providing a centralized system for storing, organizing and analyzing social media content performance data.

## 3. Project Objectives

The main objectives are to:

- Store and manage social media accounts and published posts.
- Record post performance statistics, including views, likes, comments, shares and saves.
- Calculate engagement rates for individual posts.
- Identify and compare top-performing content.
- Generate reports that help users understand their content performance.
- Provide useful information to support future content planning and decision-making.

## 4. Data Source

The initial dataset will be obtained from Hugging Face:

**Dataset:** TikTok Videos Dataset  
**Source:** DataHive AI  
**Link:** https://huggingface.co/datasets/datahiveai/Tiktok-Videos

The dataset will be inspected to identify relevant attributes and determine which records and fields can be used in the system. The initial implementation will use TikTok data, while the database design will consider the possibility of supporting additional social media platforms in the future.

## 5. Planned Innovation

The project will include an interactive analytics dashboard developed using **Streamlit**.

The dashboard is intended to allow users to:

- View social media content performance.
- Compare engagement across posts.
- Identify top-performing content.
- Explore performance statistics through charts and reports.

The dashboard will connect to the Oracle database to display information processed and stored by the system.

## 6. Planned Database Tables

The following tables are proposed for the initial database design. Their final structure will be determined after dataset inspection and normalization.

| Table | Purpose |
|---|---|
| SYSTEM_USERS | Stores system user information. |
| PLATFORMS | Stores supported social media platforms. |
| SOCIAL_ACCOUNTS | Stores users' social media accounts. |
| ACCOUNT_ACCESS | Manages access to social media accounts. |
| CONTENT_CATEGORIES | Stores categories of published content. |
| POSTS | Stores information about published posts. |
| POST_METRICS | Stores performance statistics for posts. |
| PERFORMANCE_ALERTS | Stores alerts about post performance. |

## 7. Planned PL/SQL Features

The project will demonstrate the following PL/SQL concepts:

- **Procedures:** To register and manage posts and their performance records.
- **Functions:** To calculate engagement rates.
- **Cursors:** To retrieve and analyze top-performing posts.
- **Packages:** To organize related content management and analytics operations.
- **Triggers:** To generate performance alerts when specified conditions are met.
- **Exception Handling:** To handle invalid data and database errors.

## 8. Expected Outcome

The expected outcome is a functional social media content performance tracking system backed by an Oracle database. It will help content creators and social media managers organize performance data, understand engagement patterns and identify content that performs well.

## 9. References

1. DataHive AI. *TikTok Videos Dataset*. Hugging Face. https://huggingface.co/datasets/datahiveai/Tiktok-Videos
2. Oracle. *PL/SQL Language Reference*. https://docs.oracle.com/en/database/oracle/oracle-database/23/lnpls/

Additional academic papers, industry reports and existing-system references will be documented in the project's research log as the research phase progresses.

---

**Project Status:** Phase 0 - Topic Proposal and Registration  
**Project Name:** CreatorPulse
