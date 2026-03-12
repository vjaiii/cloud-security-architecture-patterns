# Zero Trust Cloud Pattern

## Purpose

Reduce implicit trust and enforce strong identity, validation, and segmentation across cloud services.

## Core ideas

- Authenticate every access path
- Authorize based on least privilege
- Limit direct exposure of internal services
- Use private network paths where possible
- Log access and administrative actions

## Typical architecture components

- Identity provider
- Application gateway or proxy
- Private workloads
- Segmented network zones
- Centralized logging and monitoring

## Review questions

- Which services are internet-facing
- Which services should be private only
- Are identities scoped correctly
- Is administrative access protected
