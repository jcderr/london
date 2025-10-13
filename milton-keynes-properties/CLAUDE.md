# Instructions for New Property Evaluation Research

## Core Task
Evaluate specific rental properties in Milton Keynes for family suitability, focusing on school catchment verification, neighborhood quality, and local amenities.

## Required Input Format
For each property evaluation, provide:
- **Full address** (street name, house number, postcode)
- **Postcode** (to verify catchment areas)
- **Any property listing details** (optional but helpful)

## Research Requirements

### 1. Secondary School Catchment Verification (Priority #1)
**Goal:** Confirm the property gives access to target schools for 12-year-old autistic son entering Year 7 (January/February 2026 mid-year)

**Target Schools (in priority order):**
1. **Milton Keynes Academy** (MK6 5LA) - 6:1 ratio, 540 spare places, catchment priority
2. **Radcliffe School** (MK12 5BT) - 15-place autism ARP, PAN 270, Good SEND
3. **Shenley Brook End School** (MK5 7ZT) - PAN 300, wellbeing hub
4. **Denbigh School** (MK5 6EX) - Top performer but heavily oversubscribed

**Required Analysis:**
- Exact straight-line distance from property to each target school (using mapping tools)
- Confirm which school is designated catchment for the postcode
- Reference 2024 admission data (furthest distance offered) to assess realistic admission prospects
- **Critical:** State clearly whether mid-year Year 7 admission is "highly likely," "moderate," or "unlikely" based on catchment status and distance

### 2. Primary School Options (Priority #2)
**Goal:** Identify viable Year 5 options for 10-year-old daughter (January/February 2026 mid-year entry, then Year 6 September 2026)

**Required Analysis:**
- List all primary schools within 1.5 miles of property
- Note Ofsted ratings (Outstanding/Good/Requires Improvement/Inadequate)
- Identify catchment school if applicable
- Check for any autism/SEND provision (not essential but helpful)
- Note capacity/oversubscription status if available
- **State clearly:** Which school(s) offer realistic Year 5 mid-year admission prospects

### 3. Neighborhood Demographics & Safety
**Required Data Points:**
- **Postcode demographics:** Average age, ethnic diversity, household composition, deprivation indices
- **Crime statistics:** Use police.uk or similar - compare to Milton Keynes average
  - Overall crime rate (per 1,000 residents)
  - Types of crime (violence, burglary, ASB, vehicle crime)
  - Crime trend (increasing/decreasing/stable over last 12 months)
- **Safety perception:** Reference any community forums, local council reports
- **Family-friendliness indicators:** Parks, playgrounds, youth facilities within walking distance

### 4. Local Amenities & Distances

**Pubs:**
- Name and distance to nearest 3 pubs
- Note if family-friendly (food service, garden)

**Grocery Stores:**
- Nearest supermarket (Tesco/Sainsbury's/Asda/Morrisons) - name, type (Express/Local/Superstore), distance
- Nearest convenience store/corner shop - distance
- Any specialty stores (international foods, organic markets) nearby

**Shopping Centers:**
- Nearest shopping center/retail park - name, distance, what stores it contains
- Milton Keynes Central (The Centre:MK) - distance and transport access

**Additional:**
- GP surgery - distance to nearest
- Pharmacy - distance to nearest
- Parks/green spaces - nearest names and distances
- Public transport stops - bus routes within 5 minutes walk

## Output Format

Structure the analysis as:

### Property Summary
[Address, postcode, brief description]

### Secondary School Access Analysis
[Table showing: School name | Distance | Catchment status | 2024 admission distance | Admission prospect]
**Recommendation:** [Clear statement on viability]

### Primary School Options
[Table: School name | Distance | Ofsted | Catchment | Mid-year prospect]
**Recommendation:** [Clear statement on best option(s)]

### Neighborhood Profile
- Demographics overview (2-3 key stats)
- Crime rate vs MK average (state if higher/lower/similar)
- Safety assessment (1 paragraph)
- Family suitability rating (High/Medium/Low with brief justification)

### Local Amenities Map
**Pubs:** [List with distances]
**Groceries:** [List with distances]
**Shopping:** [List with distances]
**Healthcare:** [GP, pharmacy distances]
**Green spaces:** [Nearest parks]
**Transport:** [Bus routes available]

### Final Verdict
**Proceed with viewing:** Yes/No/Maybe
**Key strengths:** [2-3 bullet points]
**Key concerns:** [2-3 bullet points]
**Overall suitability score:** X/10

## Critical Success Factors

**Deal-breakers that should result in "No" verdict:**
- Property is NOT in catchment for any target secondary school AND distance ranks it unlikely for admission
- Nearest primary school is rated Inadequate
- Crime rate >50% higher than Milton Keynes average with increasing trend
- No grocery store within 1 mile walking distance

**Red flags to highlight prominently:**
- Distance to target schools >3 miles (reduces admission prospects)
- Primary school options all heavily oversubscribed
- High antisocial behavior or violence rates in immediate postcode
- Limited public transport if property distant from amenities

## Data Sources to Use

- **School catchments:** Milton Keynes Council website, individual school admissions pages
- **Distances:** Google Maps straight-line measurement tool
- **Crime data:** police.uk postcode search (last 12 months)
- **Demographics:** Office for National Statistics, Milton Keynes Council ward profiles
- **Amenities:** Google Maps radius search, Milton Keynes Council local area guides
- **Ofsted ratings:** Ofsted website school search
- **Admission data:** Individual school websites, Milton Keynes Council admissions reports

## Example Property Input Format

When providing properties for evaluation, use this format:

```
PROPERTY FOR EVALUATION:
Address: 45 Simpson Road, Milton Keynes, MK6 3AR
Postcode: MK6 3AR
Bedrooms: 3
Notes: Semi-detached, garden, available January 2026
```

## Notes
- Prioritize secondary school catchment verification above all else
- Be explicit about admission likelihood - avoid vague language
- Flag any missing data clearly rather than guessing
- Compare multiple properties if provided to make relative recommendations
- January/February 2026 arrival timing is fixed - focus on mid-year admission prospects