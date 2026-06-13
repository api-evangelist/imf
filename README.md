# IMF Data API - APIs.json Profile

This repository contains an APIs.json 0.19 profile for the International Monetary Fund (IMF) Data API.

## Overview

The IMF provides free, public access to hundreds of statistical datasets through its SDMX 3.0 Data API. Data covers macroeconomic indicators, fiscal statistics, monetary and financial data, balance of payments, exchange rates, and international financial data across all IMF member countries.

- **Base URL:** https://api.imf.org/external/sdmx/3.0
- **Authentication:** None required
- **Standard:** SDMX 3.0
- **Rate Limit:** 50 requests/second (application-based)

## Key Datasets

- International Financial Statistics (IFS)
- World Economic Outlook (WEO)
- Fiscal Monitor (FM)
- Government Finance Statistics (GFS)
- Monetary and Financial Statistics (MFS)
- Balance of Payments (BOP)
- Public Sector Balance Sheet (PSBS)
- Direct Investment (DIP)
- Coordinated Portfolio Investment Survey (CPIS)
- Producer Price Index (PPI)

## Files

- `apis.yml` - APIs.json 0.19 provider profile
- `openapi.yml` - OpenAPI 3.0 specification
- `plans/imf-plans-pricing.yml` - Pricing and plan details (free)
- `rate-limits/imf-rate-limits.yml` - Rate limiting documentation
- `finops/imf-finops.yml` - FinOps considerations for API consumers

## Resources

- [IMF Data Portal](https://data.imf.org/)
- [API Documentation](https://datahelp.imf.org/knowledgebase/articles/667294-using-json-restful-web-service)
- [IMF Website](https://www.imf.org/en/Data)
