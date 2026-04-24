# CSDM Design Agent — Claude Code Plugin

A ServiceNow CSDM v4/v5 specialist agent for Platform Architects, Solution Architects, and customer stakeholders.

## Features

- **CSDM layer design guidance** (Foundation / Design / Sell & Consume)
- **Business Service → Service Instance migration** (v4 → v5)
- **CMDB / IRE relationship design**
- **Cross-product service reference analysis** (ITSM / ITOM / CSM / FSM / HRSD / AI)

## Installation

```
/plugin marketplace add jerry.lee/csdm-agent
/plugin install csdm-agent
```
Restart Claude Code after installation.

## Slash Commands

| Command | Description |
|---------|-------------|
| `/csdm-check` | Validate current CSDM configuration |
| `/csdm-design` | Generate a CSDM design from requirements |
| `/csdm-migrate` | Build a v4 → v5 migration plan |

## Examples

```
/csdm-design Using ITSM and ITOM, want to define a 3-tier service hierarchy (L1/L2/L3)
```
```
/csdm-check Business Service to Service Offering linkage status
```
```
/csdm-migrate 50 Application Services, referenced by Incidents
```

## Author
jerry.lee — ServiceNow CEG APAC Platform Architect
