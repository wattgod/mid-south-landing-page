# Mid South Landing Page Data

Complete race data file for The Mid South gravel race landing page generator.

## File Structure

- `data.json` - Complete race data following the Gravel God rating system schema

## Race Overview

**The Mid South** - Oklahoma's weather lottery with a $100K prize purse and a guaranteed Bobby hug.

- **Distance:** 100 miles
- **Location:** Stillwater, Oklahoma
- **Date:** Mid-March annually (2026: March 13-14)
- **Gravel God Rating:** 85/100 (Tier 1)

## Data Schema

This file follows the same schema as the Unbound 200 data file, including:

- Race vitals (distance, elevation, location, dates)
- Climate and terrain characteristics
- Gravel God ratings (Course Profile: 21/35, Biased Opinion: 32/35)
- Detailed ratings breakdown (Length, Technicality, Elevation, Climate, Altitude, Logistics, Adventure)
- Biased opinion ratings (Prestige, Race Quality, Experience, Community, Field Depth, Value, Expenses)
- History and notable moments
- Course description and suffering zones
- Black pill reality check
- Final verdict and alternatives
- Logistics information
- Training plans structure (15 plans across 4 tiers)

## Usage

This data file is designed to work with the landing page generator at `/gravel-landing-page-project/scripts/generate_landing_page.py`.

### Generate Landing Page

```bash
python3 /path/to/gravel-landing-page-project/scripts/generate_landing_page.py \
  data.json \
  /path/to/gravel-landing-page-project/templates/elementor-base-template.json \
  output/mid-south-elementor.json
```

### Validation

```bash
python3 /path/to/gravel-landing-page-project/scripts/validate_race_data.py data.json
```

## Training Plans

**Note:** TrainingPeaks URLs are currently placeholders and need to be researched and updated once plans are live on the TrainingPeaks marketplace.

### Plan Structure

- **Ayahuasca:** 4 plans (Beginner, Intermediate, Masters 50+, Save My Race)
- **Finisher:** 5 plans (Beginner, Intermediate, Advanced, Masters 50+, Save My Race)
- **Compete:** 4 plans (Intermediate, Advanced, Masters 50+, Save My Race)
- **Podium:** 2 plans (Advanced, G.O.A.T.)

## Placeholders Requiring Research

1. **RideWithGPS ID:** Currently `PLACEHOLDER_NEEDS_RESEARCH`
2. **TrainingPeaks Plan IDs:** All 15 plans have `PLACEHOLDER_NEEDS_RESEARCH` for `tp_id`

## Updates

- **Created:** 2025-01-XX
- **Last Updated:** 2025-01-XX


