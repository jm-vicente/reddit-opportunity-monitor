# Reddit Opportunity Monitor

**Portfolio case study | n8n workflow architecture | Non-executable example**

## Overview

This project illustrates a scheduled automation for monitoring public Reddit discussions against configurable search terms. It demonstrates an approach to collecting RSS data, extracting relevant posts, filtering and de-duplicating results, and routing records for logging and notifications.

## Technologies represented

- n8n for workflow orchestration
- JavaScript code nodes for query preparation and post processing
- HTTP requests and RSS/XML parsing for public feed retrieval
- Google Sheets nodes for simple record lookups and tracking
- Slack node for team notifications

## High-level workflow

1. Start a scheduled workflow and prepare keyword/subreddit search combinations.
2. Retrieve publicly available RSS results and parse the feed data.
3. Extract post details and apply relevance, recency and duplicate checks.
4. Log selected records and prepare a notification for review.

## Files

- `workflow-structure.json`: sanitized n8n-style **structural reference** preserving generic node types, relative layout and connections. This is **not runnable**: scripts, node parameters, credentials, IDs, original names and service configuration are intentionally omitted.

## Technical concepts

Scheduled execution · workflow branching · data extraction · XML parsing · duplicate checks · rate-aware processing · record keeping · messaging integrations.

## My role

_[Before publishing, describe only the stages you personally designed, developed, maintained or tested. Avoid claiming sole ownership if this was collaborative.]_

## Confidentiality & scope

This case study is intentionally high-level. The JSON is a non-executable architectural illustration, not an original deployable workflow. It excludes internal URLs, record IDs, connection details, scripts, credentials, and business-specific search configurations. Sharing generalized architecture may still require permission from the rights holder. No endorsement or company ownership is implied.
