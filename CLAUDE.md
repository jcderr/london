# UK Family Relocation: Property Evaluation System

## Purpose

This repository contains specialized evaluation frameworks for analyzing UK rental properties for a family relocating in January/February 2026, with particular focus on mid-year school admissions and autism SEND support.

## Family Context

- **Children:**
  - 12-year-old son with autism (Year 7 mid-year entry)
  - 10-year-old daughter (Year 5 mid-year entry)
- **Move date:** January/February 2026
- **Key priorities:** Autism support, mid-year school placement, safe neighborhoods

---

## How to Use This System

**Based on your evaluation needs, I will route you to the appropriate specialized framework:**

### 1. Evaluating Commuter Towns (General Location Research)

**Use when:** Researching towns/cities within commuting distance to a job location, comparing multiple broad locations.

**Framework:** `/commuter-town-evaluations/CLAUDE.md`

**Best for:**
- Comparing multiple towns/cities (e.g., "Should I consider St Albans, Bedford, or Luton?")
- Understanding education systems in different areas
- Broad-level filtering before property searching
- Multi-location comparison to identify strongest prospects

**Key features:**
- Single location deep analysis OR multi-location comparison modes
- Deal-breaker identification (grammar school areas, crime rates, school distance)
- Secondary AND primary school assessment
- Neighborhood profiling with crime statistics

---

### 2. Evaluating Specific Properties in Milton Keynes

**Use when:** Analyzing specific rental listings in Milton Keynes with full addresses/postcodes.

**Framework:** `/milton-keynes-properties/CLAUDE.md`

**Best for:**
- Detailed analysis of specific rental properties
- Exact catchment verification for Milton Keynes schools
- Distance calculations to target schools (Milton Keynes Academy, Radcliffe School, etc.)
- Amenity mapping (pubs, shops, healthcare within walking distance)

**Key features:**
- Targets 4 specific secondary schools with known autism provision
- Primary school mid-year admission likelihood assessment
- Postcode-level crime statistics
- Walking distance amenity mapping
- Clear proceed/no-proceed verdicts

---

### 3. Evaluating Properties Across the UK (Any Location)

**Use when:** Analyzing specific properties outside Milton Keynes, in any UK location.

**Framework:** `/uk-wide-location-evaluations/CLAUDE.md`

**Best for:**
- Properties anywhere in England, Scotland, Wales
- Understanding unfamiliar local authority education systems
- Researching selective (grammar) vs. comprehensive areas
- SEND provision across different local authorities

**Key features:**
- Comprehensive area context (education system type, EHCP processing)
- Local authority SEND service assessment
- Cost of living comparisons
- Detailed scoring rubric (1-10 scale with clear criteria)
- Transport infrastructure analysis

---

## Automatic Routing Logic

When you provide property information or research requests, I will automatically select the appropriate framework:

**If you say:** "Evaluate properties in Stevenage, Luton, and Bedford"
**→ I use:** `commuter-town-evaluations` (multi-location comparison)

**If you say:** "Analyze 23 Acorn Drive, Milton Keynes, MK6 3AR"
**→ I use:** `milton-keynes-properties` (specific MK property)

**If you say:** "What about this flat in Bristol at BS5 9XX?"
**→ I use:** `uk-wide-location-evaluations` (property outside MK)

---

## What Information to Provide

### For Town/City Comparisons:
- Town/city names or general areas
- Optional: specific neighborhoods or postcodes for focused research

### For Specific Properties:
- Full address (street name, house number)
- Postcode
- Optional: bedrooms, rent, listing link

---

## Universal Deal-Breakers

Regardless of framework used, these are automatic disqualifiers:

1. No viable secondary school within 3 miles
2. Nearest primary school rated Inadequate by Ofsted
3. Crime rate >50% above local authority average with increasing trend
4. No grocery store within 1 mile walking distance

---

## Expected Outputs

All frameworks provide:
- ✅ Clear proceed/reconsider/eliminate recommendations
- ✅ School-by-school distance and admission likelihood analysis
- ✅ Neighborhood safety assessment with crime statistics
- ✅ Local amenities mapping
- ✅ Key strengths and concerns highlighted
- ✅ Specific next actions required

---

## Getting Started

Simply describe your property evaluation need, and I'll route you to the correct framework and begin research.

**Examples:**

"I want to compare Northampton, Peterborough, and Cambridge as potential locations"

"Can you evaluate 15 Simpson Road, Milton Keynes, MK6 2AB?"

"What about properties in York? Here's a listing at YO24 3QQ"
