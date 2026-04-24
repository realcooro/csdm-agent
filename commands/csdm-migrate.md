# /csdm-migrate

## Description
Generates a step-by-step migration plan for CSDM v4 → v5.
Includes impact analysis for Business Service → Service Instance transition and a rollback plan.

## Usage
```
/csdm-migrate [current state description]
```

### Examples
```
/csdm-migrate 50 Application Services, referenced by ITSM Incidents
/csdm-migrate 30 Service Mapping services, Service Offering linkages in place
```

## Behavior
1. Assesses current v4 configuration
2. Identifies all impacted tables and products
3. Outputs a step-by-step migration plan (Steps 1–6)
4. Includes rollback scenario
5. Provides a pre-migration validation checklist
