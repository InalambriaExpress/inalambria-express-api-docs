# Inalambria Express API (v1.0.0)

Official API documentation for **Inalambria Express** — send SMS messages, run campaigns, check credit balance, and track async jobs. 

- Website: https://inalambria.express
- API Base URL: https://api.inalambria.express/docs/
- OpenAPI (OAS 3.1.0): [`openapi.yaml`](./openapi.yaml)

## Overview

**Inalambria Express API** provides endpoints for:
- Sending SMS to one or many recipients
- Sending batches (different messages to different recipient groups)
- Sending personalized messages using templates (`{{variable}}`)
- Viewing message history (consumption logs)
- Checking credit balance and budget limits
- Tracking async jobs and queue status

This repository is designed to be linkable and easy to embed in other docs, SDKs, and integrations.

## Authentication (Bearer)

Authentication uses a Bearer token in the `Authorization` header:

