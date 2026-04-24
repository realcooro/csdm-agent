# /csdm-design

## Description
Generates a CSDM layer design based on the user's business requirements.
Automatically accounts for products in use and their service reference tables.

## Usage
```
/csdm-design [requirements description]
```

### Examples
```
/csdm-design Using ITSM and ITOM, want to define a 3-tier service hierarchy (L1/L2/L3)
/csdm-design Design a structure to expose Service Offerings through a CSM customer portal
/csdm-design Telecom service hierarchy for a carrier, v5 standard
```

## Behavior
1. Confirms products in use (prompts if not provided)
2. Confirms v4 or v5 target version
3. Generates a layer-by-layer design proposal
4. Analyzes cross-product reference table impact
5. Outputs design rationale and key considerations
