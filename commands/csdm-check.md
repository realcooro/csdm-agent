# /csdm-check

## Description
Validates the consistency of your current CSDM configuration and surfaces improvement areas.

## Usage
```
/csdm-check [target area]
```

### Examples
```
/csdm-check Business Service configuration
/csdm-check Service Offering linkages
/csdm-check IRE relationship setup
/csdm-check v4 to v5 migration readiness
```

## Behavior
1. Analyzes the specified target area
2. Lists validation items for related tables and reference relationships
3. Checks cross-product impact
4. Outputs prioritized recommendations

## Output Format
```
## CSDM Check Results

### ✅ Healthy
- ...

### ⚠️ Needs Improvement
- ...

### ❌ Issues Found
- ...

### Recommendations
- ...
```
